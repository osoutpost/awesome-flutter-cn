# Flutter 资源大全中文版

[Flutter](https://flutter.dev/) 是 Google 出品的 UI 工具包，旨在使用一套代码构建精美的移动端、网页和桌面端的跨平台应用。Flutter 资源大全中文版翻译整理自[awesome-flutter](https://github.com/Solido/awesome-flutter)，在此基础上会不定期补充一些中文 Flutter 相关的资源。这个中文资源列表由微信公众号「开源前哨」维护。

## 内容

- [文章](#文章)
- [视频](#视频)
- [组件](#组件)
- [导航](#导航)
- [模板](#模板)
- [插件](#插件)
- [框架](#框架)
- [引擎](#引擎)
- [开源应用](#开源应用)
- [网页](#网页)
- [工具集](#工具集)
- [书](#书)

## 文章

### flutter 介绍

- [Google IO 2018](https://medium.com/flutter-io/building-beautiful-flexible-user-interfaces-with-flutter-material-theming-and-official-material-13ae9279ef19)  - 构建精美灵活的用户界面
- [Presentation](https://speakerdeck.com/hjjunior/why-i-chose-flutter) - [Helio S. Junior](https://github.com/hjJunior).
- [Flutter Web](https://medium.com/flutter-community/ins-and-outs-of-flutter-web-7a82721dc19a)  - Flutter Web 的来龙去脉，[Nash](https://github.com/nash0x7e2))

### 网站 / 博客

- [Welcome to Flutter](https://didierboelens.com) - 致力于解答 Flutter 的最常见问题的英语和法语博客，Didier Boelens.
- [SZAŁKO-BLOG](https://marcinszalek.pl/) - 一步一步优化设计，[Marcin Szalek](https://marcinszalek.pl).
- [Flutter by Example](https://flutterbyexample.com/) - 关于 Redux, Firebase, 自定义动画以及 UI 的教程
- [Flutter Institute](https://flutter.institute/) - 非常基础的教程，作者 [Brian Armstrong](https://twitter.com/flutterinst).
- [Iirokrankka.com](https://iirokrankka.com/) - 一些文章和教程， [Iiro Krankka](https://twitter.com/koorankka).
- [Norbert](https://medium.com/@norbertkozsir) - 一些有深度的文章，功能和应用实现，[Norbert515](https://github.com/Norbert515).
- [Flutter Tips](https://medium.com/@diegoveloper) - 一些开发中的奇技淫巧，[Diego Velásquez](https://twitter.com/diegoveloper).
- [FilledStacks](https://www.filledstacks.com/) - 一些开发指南，[Dane Mackier](https://www.instagram.com/filledstacks/).
- [Awesome Flutter tips](https://github.com/erluxman/awesomefluttertips/) - 开发中提升生产力的技巧，[erluxman](https://twitter.com/erluxman/).

### 教程

- [Animated Chat](https://codelabs.developers.google.com/codelabs/flutter/#0) - Google Code Labs 出品的关于构建精美 UI 的教程.
- [Firebase Chat](https://codelabs.developers.google.com/codelabs/flutter-firebase/#0) - Google Code Labs 出品的集成 Firebase 的教程.
- [Planets-Flutter: from design to app](http://sergiandreplace.com/2017/09/planets-flutter-from-design-to-app) - 详解 planents app 的设计开发过程.
- [Todo List](https://github.com/lesnitsky/todolist_flutter) – 手把手教你编写一个 Todo List 应用，[Andrei Lesnitsky](https://twitter.com/lesnitsky_dev)
- [Flutter and Dart development](https://suragch.medium.com/flutter-and-dart-development-articles-981be9ef7b23) - 开发教程，[Suragch](https://twitter.com/Suragch1).

### 入门

- [Roadmap to Flutter Development](https://github.com/olexale/flutter_roadmap) - 面向Flutter新手的可视化路线图与原则、模式和框架，[Olexandr Leuschenko](https://github.com/olexale).
- [Layout Cheat Sheet](https://medium.com/flutter-community/flutter-layout-cheat-sheet-5363348d037e) - 布局 widgets 的用例，[Tomek Polański](https://github.com/tomaszpolanski).
- [Getting Started with Flutter](https://www.raywenderlich.com/24499516-getting-started-with-flutter) - [raywenderlich.com](https://www.raywenderlich.com).
- [Beginner's Guide](https://github.com/antz22/ultimate-guide-to-flutter) - 关于 Flutter 和 Firebase 基础知识的综合指南，[Anthony](https://github.com/antz22).

### 中级

- [Flutter state management for minimalists](https://suragch.medium.com/flutter-state-management-for-minimalists-4c71a2f2f0c1?sk=6f9cedfb550ca9cc7f88317e2e7055a0) - 在不依赖第三方框架的情况下了解应用架构，[Suragch](https://twitter.com/Suragch1). 也可以看 [State Management](#state-management).

### 高级

- [Rendering Pipeline](https://www.youtube.com/watch?v=UUfXWzp0-DU) and [Let's build a render tree](https://www.youtube.com/watch?v=VsYbFnucHsU) - 引擎架构，Adam Barth.
- [Render Objects](https://medium.com/flutter-community/flutter-what-are-widgets-renderobjects-and-elements-630a57d05208)  - 什么是 Widgets, RenderObjects 以及 Elements? [Norbert515](https://github.com/Norbert515).
- [Streams and RxDart](https://skillsmatter.com/skillscasts/12254-flutter-with-streams-and-rxdart) - 技巧性的报告，[Brian Egan](https://github.com/brianegan).
- [Gesture System](https://medium.com/flutter-community/flutter-deep-dive-gestures-c16203b3434f)  - 深入 Flutter: 手势，[Nash](https://github.com/nash0x7e2).
- [Schemas](https://www.didierboelens.com/2018/06/widget---state---context---inheritedwidget/) - 关于 Widget, State, Context 以及 InheritedWidget 的讲解，[Didier Boelens](https://didierboelens.com).
- [Rendering Engine Tutorial](https://medium.com/saugo360/flutters-rendering-engine-a-tutorial-part-1-e9eff68b825d)  - Flutter 的渲染引擎，[AbdulRahman AlHamali](https://github.com/AbdulRahmanAlHamali/).
- [Inherited Widget](https://medium.com/@chemamolins/is-flutters-inheritedwidget-a-good-fit-to-hold-app-state-2ec5b33d023e) - 用 Flutter 的 InheritedWidget 进行状态管理，[Chema Molins](https://github.com/jmolins).
- [From Mobile to Desktop](https://medium.com/flutter-community/flutter-from-mobile-to-desktop-93635e8de64e) - 移动端和桌面端应用开发教程，[Marcelo Henrique Neppel](https://neppel.com.br).
- [Accessibility widgets](https://medium.com/flutter-community/a-deep-dive-into-flutters-accessibility-widgets-eb0ef9455bc)  - 深入了解无障碍环境的各方面信息，[Muhammed Salih Güler](https://twitter.com/salihgueler).
- [Profiling w/ Timeline](https://medium.com/flutter-io/profiling-flutter-applications-using-the-timeline-a1a434964af3)  - 通过使用时间轴，你可以通过以下方式找到并解决你的应用程序中的具体性能问题，[Chinmay Garde](https://medium.com/@chinmaygarde).

### 指南

- [Parallax Effect](https://marcinszalek.pl/flutter/tickets-challenge-parallax) - 视差和非线性动画，[Marcin Szalek](https://marcinszalek.pl).
- [Build Flavor](https://medium.com/@salvatoregiordanoo/flavoring-flutter-392aaa875f36)  - 定义构建配置并自由切换，[Salvatore Giordano](https://medium.com/@salvatoregiordanoo).
- [Build Flavor](https://medium.com/@angeloavv/easily-build-flavors-in-flutter-android-and-ios-with-flutter-flavorizr-d48cbf956e4) - 使用 flutter_flavorizr 轻松构建 flavors (包括 ios 和 android)，[Angelo Cassano](https://medium.com/@angeloavv).

## 视频

- [Boring Show](https://www.youtube.com/watch?v=CPmN4-i9zC8&list=PLOU2XLYxmsIK0r_D-zWcmJ1plIcDNnRkK) - 和 Flutter 团队一起探讨.
- [Tensor Programming](https://www.youtube.com/watch?v=WwhyaqNtNQY&list=PLJbE2Yu2zumDqr_-hqpAN0nIr6m14TAsd) [86🎬] - 丰富内容的频道， [Tensor Programming](http://tensor-programming.com/).
- [Mtechviral](https://www.youtube.com/watch?v=qWL1lGchpRA&list=PLR2qQy0Zxs_UdqAcaipPR3CG1Ly57UlhV) [245🎬] - [印地语/英语] Mtechviral 系列，[Pawan Kumar](https://github.com/iampawan).
- [Flutter in Practice](https://www.youtube.com/playlist?list=PLhXZp00uXBk5TSY6YOdmpzp1yG3QbFvrN) - 适合初学者的免费视频，[Zaiste](https://zaiste.net/).
- [Whatsupcoders](https://www.youtube.com/c/whatsupcoders) [82🎬] - 关于 Flutter Widgets 的免费视频，[Kamal](https://github.com/whatsupcoders).
- [Reso Coder](https://www.youtube.com/channel/UCSIvrn68cUk8CS8MbtBmBkA) - 中级和高级视频，[Matej Rešetár](https://github.com/ResoCoder).

## 组件

### Demo 演示

- [Official Gallery](https://github.com/flutter/gallery) - Flutter Team 基于 material design 的 widgets 演示 demo
- [Flutter Examples](https://github.com/nisrulz/flutter-examples) - 一个简单的独立应用开发演示，[Nishant Srivastava](https://github.com/nisrulz).
- [Flutter Catalog](https://github.com/X-Wei/flutter_catalog) - 和源码一起展示的 Flutter components 演示例子，[X-Wei](https://github.com/X-Wei).
- [Generative Art](https://github.com/Solido/flutter-d-art) - Generative Art，[Robert Felker](https://github.com/Solido).


### UI

- [StaggeredGridView](https://github.com/letsar/flutter_staggered_grid_view) - 具有不同大小瓦片的栅格系统，[Romain Rastel](https://github.com/letsar).
- [Radial Menu](https://github.com/xqwzts/flutter_radial_menu) - 带动画的径向菜单，[Victor Choueiri](https://github.com/xqwzts).
- [Tinder Cards](https://github.com/Ivaskuu/tinder_cards) - 类似于 Tinder 的卡片滑动效果，[Ivascu Adrian](https://github.com/Ivaskuu).
- [Flip Panel](https://github.com/hnvn/flutter_flip_panel) - 用内置动画实现翻板效果，[HungHD](https://github.com/hnvn).
- [Facebook Reactions](https://github.com/duytq94/facebook-reaction-animation) - Facebook reactions widget，[Duy Tran](https://github.com/duytq94).
- [Flushbar](https://github.com/AndreHaueisen/flushbar) - 高可定制的通知栏，[Andre Haueisen](https://github.com/AndreHaueisen).
- [Stepper Touch](https://github.com/Rahiche/stepper_touch) - 侧向滑动效果的计数器，[Raouf Rahiche](https://github.com/Rahiche).
- [Typeahead](https://github.com/AbdulRahmanAlHamali/flutter_typeahead) - 在用户输入时向他们显示联想词建议，[Abdul Rahman Al Hamali](https://github.com/AbdulRahmanAlHamali).
- [Snaplist](https://github.com/ariedov/flutter_snaplist) - 创建可移除项目的滑动展示列表，[David Leibovych](https://github.com/ariedov).
- [Pin Code](https://github.com/LiewJunTung/pin_code_text_field) - 可定制动画的 pin 码输入器，[Liew Jun Tung](https://github.com/liewjuntung).
- [Folding Cell](https://github.com/faob-dev/folding_cell) - 折叠你的 widget，[Faob](https://github.com/faob-dev).
- [Liquid Pull To Refresh](https://github.com/aagarwal1012/Liquid-Pull-To-Refresh) - 一个精美的刷新指示器，[Ayush Agarwal](https://github.com/aagarwal1012/).
- [Slide Container](https://pub.dev/packages/slide_container) 用于平滑的横向或者纵向滑动，[Quentin Le Guennec](https://github.com/quentinleguennec).
- [Direct Select](https://github.com/LanarsInc/direct-select-flutter) - 带幽灵效果的全屏选择器控件，[Ivan Yatsouba](https://github.com/iyatsouba).
- [Before After](https://github.com/xsahil03x/before_after) - 一个精美的滑动控件，用于优雅的展示图片处理前后的效果对比，[Sahil Kumar](https://github.com/xsahil03x).
- [Scratcher](https://github.com/vintage/scratcher) - 刮刮乐小工具，可暂时向用户隐藏内容，[Kamil Rykowski](https://github.com/vintage).
- [Image Sequence Animator](https://github.com/aliyigitbireroglu/flutter-image-sequence-animator) - 一个用于对 gif 文件生成的图片序列进行完全控制实现不同动画效果的小工具，[Ali Yigit Bireroglu](https://github.com/aliyigitbireroglu).
- [Beautiful_Popup](https://github.com/jaweii/Flutter_beautiful_popup) - 美化应用的弹出层，[jaweii](https://github.com/jaweii).
- [Credit Card Form](https://github.com/Origogi/Flutter-Credit-Card-Input) - 带动画的信用卡输入表单，[Origogi](https://github.com/Origogi).
- [Animated Selection Slide](https://github.com/sbilketay/animated_selection_slide) 一个带动画效果的滑动选择器部件，[Sezgin Bilgetay](https://github.com/sbilketay).
- [Flutter Tags](https://github.com/Dn-a/flutter_tags) - 可定制不同效果的标签组件，[Di Natale Antonino](https://github.com/Dn-a).
- [Flutter Neumorphic](https://github.com/Idean/Flutter-Neumorphic) - 使用 Neumorphic kit for Flutter 实现深色模式
- [Dough](https://github.com/HatFeather/flutter_dough) - 带弹性效果的用户界面部件，[Josiah Saunders](https://github.com/HatFeather).
- [Card Settings](https://github.com/codegrue/card_settings) - 用于构建设置表单的库，[codegrue](https://github.com/codegrue).
- [Timelines](https://github.com/chulwoo-park/timelines) - 强大又简单的时间轴库，[Chulwoo Park](https://github.com/chulwoo-park).
- [Timeline Tile](https://github.com/JHBitencourt/timeline_tile) - 一个用于构建精美可自定义的时间轴的工具库，[Julio Bitencourt](https://github.com/JHBitencourt).
- [Rounded Loading Button](https://github.com/chrisedg87/flutter_rounded_loading_button) - 带 loading 指示器，并在完成后带有成功/失败动画的按钮控件，[Chris Edgington](https://twitter.com/ChrisTheEdg).
- [PlutoGrid](https://github.com/bosskmk/pluto_grid) - 可以用键盘操控的网页端和桌面端的数据表格，[bosskmk](https://github.com/bosskmk).

#### 顶部固定

- [Sticky Infinite List](https://github.com/TatsuUkraine/flutter_sticky_infinite_list) - 顶部固定的高度可定制化的多向无限列表，[TatsuUkraine](https://github.com/TatsuUkraine).
- [Sticky Header](https://github.com/letsar/flutter_sticky_header) - 带顶部固定的 Sliver 封装方案，[Romain Rastel](https://github.com/letsar).
- [Sticky Headers](https://github.com/slightfoot/flutter_sticky_headers) - 可定制化的顶部固定方案，[Simon Lightfoot](http://www.devangels.london/).

#### 抽屉

- [Hidden Drawer Menu](https://github.com/RafaelBarbosatec/hidden_drawer_menu) - 带透视动画效果的抽屉菜单组件，[Rafael Almeida Barbosa](https://github.com/RafaelBarbosatec).
- [Flutter Inner Drawer](https://github.com/Dn-a/flutter_inner_drawer) - 一个使你可以创建一个左向或者右向的内置抽屉的简单组件，[Di Natale Antonino](https://github.com/Dn-a).

#### 底部菜单

- [Fancy Bottom Navigation](https://github.com/tunitowen/fancy_bottom_navigation) - 带动画的底部导航，[Tony Owen](https://github.com/tunitowen).
- [Circular Bottom Navigation](https://github.com/imaNNeoFighT/circular_bottom_navigation) - 精美的带动画的底部导航栏，[Iman Khoshabi](https://github.com/imaNNeoFighT).
- [Bottom Navy Bar](https://github.com/pedromassango/bottom_navy_bar) - 带动效的多种颜色的精美底部导航栏，[Pedro Massango](https://github.com/pedromassango).
- [Titled Navigation Bar](https://github.com/pedromassango/titled_navigation_bar) - 可以在文字和图标之间动效切换的底部导航栏，[Pedro Massango](http://github.com/pedromassango).
- [Google Nav Bar](https://github.com/sooxt98/google_nav_bar) - 一个 google 风格的现代导航栏，[Sooxt98](http://github.com/sooxt98).

#### 底部弹出层

- [Rubber Bottom Sheet](https://github.com/mcrovero/rubber) - 弹性效果的底部弹出层，[Mattia Crovero](https://github.com/mcrovero).
- [Modal Bottom Sheet](https://github.com/jamesblasco/modal_bottom_sheet) - 基于 Material, Cupertino iOS13 或者自定义外观的底部弹出层，[Jaime Blasco](https://github.com/jamesblasco).

#### 滑块/滑杆

- [RangeSlider](https://github.com/boeledi/RangeSlider) - 带两个滑块的区间选择器，[Didier Boelens](https://www.didierboelens.com).
- [Fluid Slider](https://github.com/rvamsikrishna/flutter_fluid_slider) - 一个基于 minimal design 具有液体动画效果的滑块，[Vamsi Krishna](https://github.com/rvamsikrishna).
- [Flutter Xlider](https://github.com/Ali-Azmoud/flutter_xlider) - 支持 RTL 的基于 material design 的滑块和区间选择器组件，[Ali-Azmoud](https://github.com/Ali-Azmoud).

#### UI 助手

- [Reorderables](https://github.com/hanshengchiu/reorderables) - 支持拖拽、可排序的、可单行或单列使用的栅格系统，[Hansheng Chiu](https://github.com/hanshengchiu).
- [Liquid Pull To Refresh](https://github.com/aagarwal1012/Liquid-Pull-To-Refresh) - 一个精美可定制的刷新指示器，[Ayush Agarwal](https://github.com/aagarwal1012/).
- [Infinite Listview](https://github.com/fluttercommunity/flutter_infinite_listview) - 支持横向或者纵向的无限列表，[Simon Lightfoot](https://github.com/slightfoot).
- [Offline](https://github.com/jogboms/flutter_offline) - 优雅的网络在线/离线提示器，[Jeremiah Ogbomo](https://twitter.com/jogboms).
- [Scroll To Index](https://github.com/quire-io/scroll-to-index) - 滚动到 SliverList/ListView 指定索引的元素，[Jerry Chen](https://github.com/jerrywell/).
- [In View Notifier List](https://github.com/rvamsikrishna/inview_notifier_list) - 一个带通知的 ListView，当该 widget 出现在屏幕的指定区域时发出通知，[Vamsi Krishna](https://github.com/rvamsikrishna).
- [ShowCaseView](https://github.com/simformsolutions/flutter_showcaseview) - 在 iOS 和 Android 上展示你的应用功能，[Simform](https://github.com/simformsolutions).

#### Material 设计

- [Unicorn Speed Dial](https://github.com/tiagojencmartins/unicornspeeddial) - 浮动操作按钮的快速启动部件，[Tiago Martins](https://github.com/tiagojencmartins).
- [Slidable](https://github.com/letsar/flutter_slidable) - 可以左右滑动的列表项，[Romain Rastel](https://github.com/letsar).

#### Cupertino 设计

- [Peek & Pop](https://github.com/aliyigitbireroglu/flutter-peek-and-pop) - 基于 iOS 功能的 Peek & Pop 实现，[Ali Yigit Bireroglu](https://github.com/aliyigitbireroglu).

#### 特效

- [Frosted Glass](http://stackoverflow.com/questions/43550853/how-do-i-do-the-frosted-glass-effect-in-flutter) - 毛玻璃效果，[Collin Jackson](http://www.collinjackson.com).
- [Parallax](https://github.com/FlutterRocks/page-transformer) - 视差效果，[Iiro Krankka](https://github.com/roughike).
- [Shimmer](https://github.com/hnvn/flutter_shimmer) - 内容加载时的微光效果，[HungHD](https://github.com/hnvn).
- [Wave](https://github.com/i-protoss/wave) - 可定制颜色、持续事件、浮动和模糊特效的波浪效果，[RockerFlower](https://github.com/RockerFlower).
- [Liquid Swipe](https://github.com/iamSahdeep/liquid_swipe_flutter) - 液态滑动效果，[Sahdeep Singh](https://github.com/iamSahdeep).
- [PhotoFilters](https://github.com/skkallayath/photofilters) - 图片滤镜，[Sharafudheen KK](https://github.com/skkallayath).
- [Shine](https://github.com/JonathanMonga/flutter_shine.dart) - 漂亮的阴影与动态灯光，[Jonathan Monga](https://github.com/JonathanMonga/).
- [Clay Containers](https://github.com/mcaubrey/clay_containers) - widget 的基础部件，可用于实现你自己的设计，[Michael Charles](https://github.com/mcaubrey).

#### 日历

- [Calendar Widget](https://github.com/pinkfish/flutter_calendar) - 日历 widget，[David Bennett](https://github.com/pinkfish).
- [Calendar Carousel Widget](https://github.com/dooboolab/flutter_calendar_carousel) <!-- stargazers:dooboolab/flutter_calendar_carousel--> - 翻页日历，[dooboolab](https://github.com/dooboolab/flutter_calendar_carousel)
- [Table Calendar](https://github.com/aleksanderwozniak/table_calendar) - 一个基于表格的日历，可以自动调整纵向高度，[Aleksander Woźniak](https://github.com/aleksanderwozniak).
- [Time Planner](https://github.com/Jamalianpour/time_planner) - 一个精美的跨移动端、桌面端和网页端的日期管理组件，[Mohammad Jamalianpour](https://github.com/Jamalianpour).
- [Infinite Calendar View](https://github.com/pickywawa/infinite_calendar_view) - 可无限滚动的日历视图（日程规划、单日、多日、月视图和事件列表），支持拖放、双指缩放和多列显示，[pickywawa](https://github.com/pickywawa).


#### 登录

- [Login Animation](https://github.com/GeekyAnts/flutter-login-home-animation) - 从登录到首页的平滑过渡效果，[Ruchika Gupta](https://github.com/geekruchika).
- [Flutter Login](https://github.com/NearHuscarl/flutter_login) - 带动画的登录 widget, [NearHuscarl](https://github.com/NearHuscarl).

#### 后端驱动

- [Dynamic Widget](https://github.com/dengyin2000/dynamic_widget) - 基于 json 动态生成 UI，[Denny Deng](https://github.com/dengyin2000).

### 图片

- [Carousel Slider](https://github.com/serenader2014/flutter_carousel_slider) - 支持无限滚动和自定义子元素的轮播 widget, [serenader](https://github.com/serenader2014).
- [Parallax Image](https://github.com/pulyaevskiy/parallax-image) - 图片视差组件，[Anatoly Pulyaevskiy](https://github.com/pulyaevskiy).
- [Photo View](https://github.com/renancaraujo/photo_view) - 带有加载占位符的可扩展图像视图，[Renan C. Araújo](https://github.com/renancaraujo).
- [SVG](https://github.com/dnfield/flutter_svg) - 基于 SVG 的解析、渲染和 widgets 库，[Dan Field](https://github.com/dnfield).
- [Image Cropper](https://github.com/hnvn/flutter_image_cropper) - 支持按比例、旋转和缩放的图片裁切组件，[HungHD](https://github.com/hnvn).
- [Cached Network Image](https://github.com/renefloor/flutter_cached_network_image) - 预览网络上的图片并将其缓存在指定位置
- [Lottie](https://github.com/xvrh/lottie-flutter) - 使用 airbnb's 的流行动画库 [After Effects Animation library](https://airbnb.design/lottie/)，[xvrh](https://github.com/xvrh/lottie-flutter).
- [Bitmap](https://github.com/renancaraujo/bitmap) - 在Dart FFI的帮助下进行位图操作（如对比度和曝光），[Renan C. Araújo](https://github.com/renancaraujo).
- [Crop](https://github.com/xclud/flutter_crop) - 跨平台的 widget/图片裁切组件，[Mahdi K. Fard](https://github.com/xclud/).

#### 图片选取器

- [Image Picker](https://github.com/flutter/plugins/tree/master/packages/image_picker) - 图片选取器，[Collin Jackson](http://www.collinjackson.com).
- [WeChat Assets Picker](https://github.com/fluttercandies/flutter_wechat_assets_picker) - 支持多选的微信风格资源选择器，[Alex Li](https://github.com/AlexV525).

### 地图

- [Google Map View](https://github.com/apptreesoftware/flutter_google_map_view) - 谷歌地图显示组件，[AppTree Software](https://www.linkedin.com/company/apptree-software/).
- [GeoCoder](https://github.com/aloisdeniel/flutter_geocoder) - 地理位置编码解码，[Aloïs Deniel](https://aloisdeniel.github.com).
- [Mapbox GL](https://github.com/mapbox/flutter-mapbox-gl) - 由 Mapbox 提供的交互式、可定制的矢量地图
- [AMap](https://github.com/fluttify-project/amap_map_fluttify) - 高德地图组件，[fluttify-project](https://github.com/fluttify-project).

### 图表

- [Circular Chart](https://github.com/xqwzts/flutter_circular_chart) - 带动画的径向图和饼状图，[Victor Choueiri](https://github.com/xqwzts).
- [Sparkline](https://github.com/xqwzts/flutter_sparkline) - 折线图，[Victor Choueiri](https://github.com/xqwzts).
- [Charts](https://github.com/google/charts) - google 图表
- [Candlesticks](https://github.com/trentpiercy/flutter-candlesticks) - OHLC 和交易量图表，[Trent Piercy](https://github.com/trentpiercy).
- [FCharts](https://github.com/thekeenant/fcharts) - 精美自适应带动画的图表，[Keenan Thompson](https://keenant.com).
- [FL Chart](https://github.com/imaNNeoFighT/fl_chart) - 超梦幻的图表，[Iman Khoshabi](http://www.ikhoshabi.com).
- [Bezier Chart](https://github.com/aeyrium/bezier-chart) - 漂亮的具有高度的互动性和可配置性的贝塞尔线图部件，[Diego Velasquez](https://twitter.com/diegoveloper).
- [Echarts](https://github.com/entronad/flutter_echarts) - 各种高级图表效果集，[LIN Chen](https://github.com/entronad).
- [Graphic](https://github.com/entronad/graphic) - 基于图形语法的数据可视化库，[LIN Chen](https://github.com/entronad).

### 导航

- [Fluro](https://github.com/goposse/fluro) - Flutter 中最闪亮、最时尚、最酷的路由组件，具有导航、通配符、查询和转换功能，[Posse](http://goposse.com).
- [PageView Indicator](https://github.com/leocavalcante/page_view_indicator) - 为 PageView 构建的页面指示器，[Leo Cavalcante](https://github.com/leocavalcante).
- [Deep Link Navigation](https://github.com/Dennis-Krasnov/Flutter-Deep-Link-Navigation) - Flutter 中完整的、优雅的抽象深层链接导航，[Dennis Krasnov](https://denniskrasnov.com).
- [Get](https://github.com/jonataslaw/get) -  在页面、显示通知、弹出层和底部栏之间去除上下文的快速导航组件，[Jonny Borges](https://github.com/jonataslaw).
- [Beamer](https://github.com/slovnicki/beamer) - 使用 Navigator 2.0 API 毫不费力地在受保护的页面堆栈和 URL 中导航，[Sandro Lovnički](https://github.com/slovnicki).

### 身份验证

- [Local Auth](https://github.com/flutter/plugins/tree/master/packages/local_auth) - iOS 和 Android 的 Touch ID，锁屏密码，指纹身份认证
- [Login](https://github.com/AppleEducate/flutter_login) - FaceID, TouchID, 和指纹读取器[Rody Davis](http://appleeducate.com).
- [Google Sign-In](https://github.com/flutter/plugins/tree/master/packages/google_sign_in) - Google OAuth.
- [Firebase Auth](https://github.com/FirebaseExtended/flutterfire/tree/master/packages/firebase_auth) - Firebase OAuth.
- [Facebook Login](https://github.com/roughike/flutter_facebook_login) - 使用原生 Android & iOS Facebook 登录 SDKs 身份验证，[Iiro Krankka](https://github.com/roughike).
- [Apple Sign-In](https://github.com/tomgilder/flutter_apple_sign_in) - Apple 登录，[Tom Gilder](https://github.com/tomgilder).
- [OAuth](https://github.com/hitherejoe/FlutterOAuth) - Buffer, Strava, Unsplash, Github OAuth，[Joe Birch](http://www.hitherejoe.com).
- [Firebase Phone Auth](https://medium.com/@gildaswise/flutter-adding-sign-in-with-google-and-phone-authentication-to-your-app-69f681518f9b)  - 短信验证组件，[Gildásio Filho](https://github.com/gildaswise).
- [SimpleAuth](https://github.com/Clancey/simple_auth) - 多种身份验证，包括：Azure Active Directory, Amazon, Dropbox, Facebook, Github, Google, Instagram, Linked In, Microsoft Live Connect, Github, OAuth, 以及基础验证，[James Clancey](https://github.com/Clancey).
- [Flutter AppAuth](https://github.com/MaikuB/flutter_appauth) - 支持 iOS 和 Android 的身份验证插件，[Michael Bui](https://github.com/MaikuB).

### （富）文本输入

- [Markdown](https://github.com/flutter/flutter_markdown) null - 用于 Flutter 的 Markdown 渲染器。它支持原始格式，但没有内联html
- [Zefyr](https://github.com/memspace/zefyr) - 轻量级的富文本编辑器，[Memspace](https://github.com/memspace/zefyr).
- [AutoSizeText](https://github.com/leisim/auto_size_text) - 自适应大小的文本编辑器，[Simon Leier](https://github.com/leisim).
- [Parsed Text](https://github.com/fayeed/flutter_parsed_text) - 基于内容识别的交互式文本编辑器，支持 Regex，[Fayeed Pawaskar](https://github.com/fayeed/).
- [TeX](https://github.com/shah-xad/flutter_tex) - 渲染数学公式，完全支持 HTML 和 JavaScript，[Shahzad Akram](https://github.com/shah-xad).
- [Code Field](https://github.com/BertrandBev/code_field) - 可自定义的代码显示组件，支持代码高亮，[Bertrand Bevillard](https://github.com/BertrandBev).

### 表单
- [Form Builder](https://github.com/danvick/flutter_form_builder) - 简单的表单框架，支持字段验证，响应字段变化，[Danvick Miller](https://github.com/danvick).
- [Reactive Forms](https://github.com/joanpablo/reactive_forms) - 受 Angular 的 Reactive Forms 启发的模型驱动方法来处理表单输入和验证的组件

### 分析

- [Usage](https://github.com/dart-lang/usage) - 可用于命令行工具、网页和 flutter 应用的 google 分析框架
- [Firebase Analytics](https://github.com/FirebaseExtended/flutterfire/tree/master/packages/firebase_analytics) - 连接 Firebase 分析 API.
- [Pure Mixpanel](https://github.com/seenickcode/pure_mixpanel) - 流行的 [Mixpanel.com](https://mixpanel.com) 分析工具，[Nick Manning](https://twitter.com/seenickcode).

### 国际化

- [GenLang](https://github.com/KingWu/gen_lang) - 国际化代码生成器，[King Wu](https://github.com/KingWu).
- [Flutter Translate](https://github.com/bratan/flutter_translate) - i18n 组件，[Florin Bratan](http://bratan.me).
- [attranslate](https://github.com/fkirc/attranslate) - 基于 [fkirc](https://github.com/fkirc) 的 ARB 或 JSON 半自动翻译工具


### 样式

- [Flutterial](https://github.com/rxlabz/flutterial) - Flutter Material 主题选择浏览器，[Erick Ghaumez](https://twitter.com/rxlabz).
- [Pigment](https://github.com/bregydoc/pigment) - 简单但有效的颜色工具

### 媒体

#### 音频

- [Flutter Audio Recorder](https://github.com/shadow-app/flutter_audio_recorder) - 提供全面的控制和访问记录细节，如多层叠加，[Wenyan Li](https://github.com/nikli2009).
- [Audio Recorder](https://github.com/ZaraclaJ/audio_recorder) - 录音并保存在本地的组件，[Jordan Alcaraz](https://twitter.com/jordanalcrz).
- [Flutter Sound](https://github.com/dooboolab/flutter_sound) - Flutter 的随手声音记录器，[dooboolab](https://github.com/dooboolab).
- [AssetsAudioPlayer](https://github.com/florent37/Flutter-AssetsAudioPlayer) - 可同时播放多种资源的跨平台播放器，[android / ios / web / macos]
- [Audio Service](https://pub.dev/packages/audio_service) - 系统级别的音频支援库，[Ryan Heise](https://github.com/ryanheise). [使用教程](https://suragch.medium.com/background-audio-in-flutter-with-audio-service-and-just-audio-3cce17b4a7d?sk=0837a1b1773e27a4f879ff3072e90305)，[Suragch](https://twitter.com/Suragch1).

#### 视频

- [WebRTC](https://github.com/cloudwebrtc/flutter-webrtc) - iOS/Android 的 WebRTC 插件，[CloudWebRtc](https://github.com/cloudwebrtc).
- [Chewie](https://github.com/brianegan/chewie) - 提供对视频播放的低级别访问，[Brian Egan](https://github.com/brianegan).
- [Video Trimmer](https://github.com/sbis04/video_trimmer) - 可视化剪切视频，[Souvik Biswas](https://github.com/sbis04).
- [CamerAwesome](https://github.com/Apparence-io/camera_awesome) - 摄像头插件合集，[Apparence.io studio](https://apparence.io).

#### 声音

- [Speech Recognition](https://github.com/rxlabz/speech_recognition) - 语音识别，[Erick Ghaumez](https://twitter.com/rxlabz).
- [OK Google](https://marcinszalek.pl/flutter/ok-google-flutter/) - 集成 google 助手，[Marcin Szalek](https://marcinszalek.pl/).

### 存储

- [Firebase Storage](https://github.com/FirebaseExtended/flutterfire/tree/master/packages/firebase_storage) - 使用 Firebase 作为存储方案
- [Secure Storage](https://github.com/mogol/flutter_secure_storage) - Keychain 和 Keystore 存储，[German Saprykin](https://github.com/mogol).

#### 持久化

- [Streaming Shared Preferences](https://github.com/roughike/streaming_shared_preferences)<!--stargazers:roughike/streaming_shared_preferences--> - 响应式键值存储，以流方式存储，[Iiro Krankka](https://github.com/roughike).

### 推广和盈利

- [Admob](https://pub.dev/packages/admob) - iOS 和 Android 端的 GoogleAdmob 广告推广集成，Brett Nesbitt.
- [Firebase AdMob](https://github.com/FirebaseExtended/flutterfire/tree/master/packages/firebase_admob) - 基于 Firebase 的广告集成
- [Inapp Purchase](https://github.com/dooboolab/flutter_inapp_purchase) - 源自 [react-native-iap](https://github.com/dooboolab/react-native-iap) 的内购功能集，[dooboolab](https://github.com/dooboolab).
- [Admob Flutter](https://github.com/kmcgill88/admob_flutter) - 使用平台内置风格的 Admob 插件，用于展示横幅广告，[Youssef Kababe](https://github.com/YoussefKababe) & [Kevin McGill](https://github.com/kmcgill88).
- [Facebook Audience Network](https://github.com/dreamsoftin/facebook_audience_network) - Facebook Audience Network 广告插件，显示横幅广告、插播广告、流媒体视频、奖励视频和原生广告，[Dreamsoft Innovations](https://github.com/dreamsoftin).
- [Square In-App Payments SDK](https://github.com/square/in-app-payments-flutter-plugin) - 通过在你的应用程序中嵌入一个卡片输入表单，从客户提供的卡片信息或数字钱包中产生非对称性加密的支付过程，[Square](https://github.com/orgs/square).

## 模板

- [Movie Details](https://github.com/FlutterRocks/movie-details-ui) - 电影详情页面模板，[Iiro Krankka](https://github.com/roughike).
- [Mates](https://github.com/CodemateLtd/FlutterMates) - 如何从 randomuser.me 的API中加载资料，以及一个漂亮的资料详情页面，[Iiro Krankka](https://github.com/roughike).
- [Weather](https://github.com/alessandroaime/Weather) - 通过天气应用来学习如何使用 Canvas 和动画，[Alessandro Aime](https://github.com/alessandroaime).
- [TodoMVC](https://github.com/brianegan/flutter_architecture_samples) - 基于不同的组件（Vanilla, Redux, built_redux）实现可用的 todo list 应用，[Brian Egan](https://github.com/brianegan).
- [Restaurant Menu](https://github.com/braulio94/menu_flutter) - 酒店菜单应用，[Braulio Cassule](https://github.com/braulio94).
- [UI Challenges](https://github.com/tomialagbe/flutter_ui_challenges) - 简介，旅游，食品应用，[Tomi Alagbe](https://github.com/tomialagbe).
- [Cupertino Settings](https://github.com/matthinc/flutter_cupertino_settings) - iOS 设置，[Matthias Rupp](https://github.com/matthinc).
- [Music Player](https://github.com/thosakwe/flutter_music_player) - 音乐播放器组件，[Tobe O](https://thosakwe.com/).
- [Dashboard](https://github.com/Ivaskuu/dashboard) - 仪表盘组件，[Ivascu Adrian](https://github.com/Ivaskuu).
- [Todo](https://github.com/littlemarc2011/FlutterTodo) - 基于 Dribble 的 todo list 模板，[Marc L](https://www.marc-little.com/).
- [Card Swipe Animation](https://github.com/geekruchika/FlutterCardSwipe) - 滑动卡片模板，[Ruchika Gupta](https://github.com/geekruchika).
- [UI Kit](https://github.com/iampawan/Flutter-UI-Kit) - 有用的 UI 组件合集，[Pawan Kumar](https://github.com/iampawan).
- [Book](https://github.com/putraxor/flutter-book-app) - 书架应用，[Ardiansyah Putra](https://github.com/putraxor).
- [The Gorgeous Login](https://github.com/huextrat/TheGorgeousLogin) - 丝滑的登录模板，[Hugo Extrat](https://github.com/huextrat).
- [Liquid Pay Payment App](https://github.com/longhoang2984/flutter_payment_app_ui) - 液态效果的支付模板，[Long Hoang](https://github.com/longhoang2984).
- [DrawApp](https://github.com/SnakeyHips/drawapp) - 绘画应用 demo，演示如何让用户在画布上用颜色选择器和画笔厚度滑块进行绘画，[Jake Gough](https://github.com/SnakeyHips).
- [Starter Kit](https://github.com/KingWu/flutter_starter_kit) - 通过实现 App Store 应用来学习 Bloc, RxDart, Sqflite, Fluro and Dio，[King Wu](https://github.com/KingWu).
- [Feather](https://github.com/jhomlala/feather) - 漂亮的天气应用，集成了 RxDart, Dio, BLoC, i18n, unit 以及 widget tests， [Jakub Homlala](https://github.com/jhomlala).
- [Clone UI Challenges](https://github.com/javico2609/flutter-challenges) - 有用的 UI 合集，[Javier González](https://github.com/javico2609).
- [FlutterFoodybite](https://github.com/JideGuru/FlutterFoodybite) - 精美的美食应用模板，[JideGuru](https://github.com/JideGuru).
- [Flutter Samples](https://github.com/diegoveloper/flutter-samples) - 精美的 flutter 例子集合，[Diego Velásquez](https://github.com/diegoveloper).
- [ActingWeb First_App](https://github.com/gregertw/actingweb_firstapp) - 具有基础元素，适合团队开发的起步模板，[Greger Wedel](https://github.com/gregertw).
- [Smart Washing Machine](https://github.com/pawlik92/flutter_whirlpool) - 使用 Box2D 物理引擎模拟的智能洗衣机 UI 挑战，[Tomasz Pawlikowski](https://github.com/pawlik92).
- [Beautiful Timelines](https://github.com/JHBitencourt/beautiful_timelines) - 漂亮的时间轴应用集合，[Julio Bitencourt](https://github.com/JHBitencourt).

### 代码仓库

- [GitTouch](https://github.com/pd4d10/git-touch) - 开源的移动端代码库客户端支持 GitHub, GitLab, Bitbucket 以及 Gitea，[Rongjian Zhang](https://github.com/pd4d10).

### 机器学习

- [MLKit](https://github.com/azihsoyn/flutter_mlkit) - Firebase 机器学习组件，[Naoya Yoshizawa](https://github.com/azihsoyn).
- [m2cgen](https://github.com/BayesWitnesses/m2cgen) - 命令行工具，用于将 ML 模型转化为 Dart 代码，[BayesWitnesses](https://github.com/BayesWitnesses).

### 视觉效果

- [ML Vision Camera Stream](https://github.com/santetis/flutter_camera_ml_vision) - ML视觉识别（二维码，人脸，等等）与实时摄像头流，[Aumard Jimmy](https://github.com/jaumard) 以及 [Santetis](https://github.com/santetis).
- [Google Mobile Vision](https://github.com/edufolly/flutter_mobile_vision) - Google 移动视觉，[Eduardo Folly](https://github.com/edufolly).

#### AR 增强现实

- [ARKit Plugin](https://github.com/olexale/arkit_flutter_plugin) - ARKit 组件 - Apple 公司的 AR 平台，[Olexandr Leuschenko](https://github.com/olexale).
- [ARCore Plugin](https://github.com/giandifra/arcore_flutter_plugin) - ARCore 平台组件，[Gian Marco Di Francesco](https://github.com/giandifra).

## 插件

- [Pub packages](https://pub.dev/flutter/packages) - Dart Pub Repository 依赖包精选
- [Plugins](https://github.com/flutter/plugins/tree/master/packages) - 官方插件

### 设备

- [WebView](https://github.com/dart-flitter/flutter_webview_plugin) - 加载网页内容，[Hadrien Lejard](https://twitter.com/HadrienLejard).
- [Location](https://github.com/Lyokone/flutterlocation) - 地理位置信息，通过回调持续获取位置信息，[Lyokone](https://github.com/Lyokone).
- [Battery](https://pub.dev/packages/battery) - 获取电池相关信息
- [Proximity Sensor Plugin](https://pub.dev/packages/proximity_plugin) - 一个近场通信信息获取组件，[Manoj NB](https://github.com/Samaritan1011001).
- [Geolocation](https://github.com/loup-v/geolocation) - 完整的地理位置信息组件：当前位置，位置更新，地理位置编码，附近设施以及其他，[Loup](http://intheloup.io).
- [Local Notifications](https://github.com/MaikuB/flutter_local_notifications) - 用于显示本地通知的插件，[Michael Bui](https://github.com/MaikuB).
- [Device Calendar](https://github.com/builttoroam/flutter_plugins/tree/master/device_calendar) - 用于更改用户日历的插件，[Built to Roam](http://builttoroam.com).
- [Badger](https://github.com/g123k/flutter_app_badger) - 更新启动页面图标，[Edouard Marquez](https://twitter.com/g123k).
- [UDID](https://github.com/GigaDroid/flutter_udid) - 支持应用重装的持久化 uuid，[Leon Kukuk](https://kukuk.me).
- [Downloader](https://github.com/hnvn/flutter_downloader) - 创建和管理下载任务，[HungHD](https://github.com/hnvn).
- [InAppWebView](https://github.com/pichillilorenzo/flutter_inappwebview) - 在组件内嵌 WebView，或者在应用内部打开一个浏览器窗口，[Lorenzo Pichilli](https://github.com/pichillilorenzo).
- [AppAvailability](https://github.com/pichillilorenzo/flutter_appavailability) - 列出、启动和检查已安装应用，[Lorenzo Pichilli](https://github.com/pichillilorenzo).
- [File Picker](https://github.com/miguelpruivo/plugins_flutter_file_picker) - 使用内置文件管理器打开并选择文件，[Miguel Ruivo](https://github.com/miguelpruivo).
- [VPN](https://github.com/X-dea/Flutter_VPN)<!--stargazers:X-dea/Flutter_VPN--> - 调取 VPN 服务，[Jason C.H](https://github.com/ctrysbita).
- [Geolocator](https://github.com/baseflow/flutter-geolocator)<!--stargazers:baseflow/flutter-geolocator--> - 一个 Flutter 地理位置插件，用于接入平台特殊的位置服务，[Baseflow](https://baseflow.com).
- [Permission Handler](https://github.com/baseflow/flutter-permission-handler)<!--stargazers:baseflow/flutter-permission-handler--> - 一个 Flutter 权限管理插件，提供一个跨平台 (iOS, Android) 的 API 服务，用于申请和检查系统权限，[Baseflow](https://baseflow.com).
- [WidgetKit](https://github.com/fasky-software/flutter_widgetkit)<!--stargazers:baseflow/fasky-software/flutter_widgetkit--> - 一个用于开发 iOS 小部件的插件，[Thomas Leiter](https://github.com/tomLadder).

#### 扫描

- [QR Code Reader](https://github.com/villela/flutter_qrcode_reader) - 二维码读取器，[Matheus Villela](https://github.com/villela).
- [Fast QR Reader View](https://github.com/facundomedica/fast_qr_reader_view) - 混合扫码器，[Facundo Medica](https://github.com/facundomedica).

#### 蓝牙 / NFC / Beacon

- [Blue](https://github.com/pauldemarco/flutter_blue) - 蓝牙，[Paul DeMarco](https://github.com/pauldemarco).
- [Beacons](https://github.com/loup-v/beacons) - Flutter beacons 插件，[Loup](http://intheloup.io).
- [NFC Reader](https://github.com/matteocrippa/flutter-nfc-reader) - 跨平台 NFC 读取器（iOS, Android），[Matteo Crippa](https://github.com/matteocrippa).
- [Beacon broadcast](https://github.com/pszklarska/beacon_broadcast) - 用你的手机模拟一个 beacon，[Paulina Szklarska](https://github.com/pszklarska/).
- [Reactive Ble](https://github.com/PhilipsHue/flutter_reactive_ble) - 处理多个设备的 BLE 操作，[Philips Hue](https://github.com/PhilipsHue).
- [NFC Manager](https://github.com/okadan/flutter-nfc-manager) - 支持 iOS 和 Android 的通用 NFC 插件，[Naoki Okada](https://github.com/okadan).

### 存储

- [Sqflite](https://github.com/tekartik/sqflite) - SQLite flutter 插件，[Alexandre Roux](https://www.linkedin.com/in/alextekartik/).
- [Moor](https://github.com/simolus3/moor) - Moor 是一个易于使用、响应式、类型安全的 Dart 和 Flutter 持久性库，[.
Simon Binder](https://github.com/simolus3)

### 服务

- [Dialogflow](https://github.com/VictorRancesCode/flutter_dialogflow) - DialogFlow 集成组件，[Victor Rances](https://github.com/VictorRancesCode/).
- [Intercom](https://pub.dev/packages/intercom) - Intercom 集成组件，[Maido Kaara](https://github.com/v3rm0n).
- [OneSignal](https://github.com/OneSignal/OneSignal-Flutter-SDK) - 推送服务，[OneSignal](https://github.com/OneSignal).
- [Place Dialog](https://github.com/pinkfish/flutter_places_dialog) - 基于 google map 服务的场所选择器，[David Bennett](https://github.com/pinkfish).
- [App Rating](https://github.com/AppleEducate/app_review) - 查询和编写 app store 和 google play 应用评价 [Rody Davis](http://appleeducate.com).


## 框架

### 状态管理

#### 基本的

- [Bloc](https://github.com/felangel/bloc) - 帮助实现 BLoC 设计模式的包的集合，[Felix Angelov](https://github.com/felangel).
- [MobX](https://github.com/mobxjs/mobx.dart) - 使用透明函数响应式编程 (TFRP) 在你的应用程序中加强状态管理
- [Provider](https://github.com/rrousselGit/provider) - Flutter 状态管理库，[Remi Rousselet](https://github.com/rrousselGit).
- [RiverPod](https://github.com/rrousselGit/river_pod) - 类似于 Provider，但略有不同，[Remi Rousselet](https://github.com/rrousselGit).
- [GetX](https://github.com/jonataslaw/getx) <!--jonataslaw/getx--> - 忽略上下文的状态管理和导航，[Jonny Borges](https://github.com/jonataslaw).
- [Binder](https://github.com/letsar/binder) - 一个轻量级但功能强大的状态管理库，[Romain Rastel](https://github.com/letsar).

#### Redux / ELM / 依赖注入

- [Built redux](https://github.com/davidmarne/flutter_built_redux) - 在构建模式下自动订阅你的 redux stores，[David Marne](https://github.com/davidmarne).
- [Redux.dart](https://github.com/johnpryan/redux.dart) - 带有中间件，Flutter 集成，以及时序监测的 Redux 开发者工具，[John Ryan](https://github.com/johnpryan) and [Brian Egan](https://gitlab.com/users/brianegan/projects).
- [Redux](https://github.com/brianegan/flutter_redux) - 让你可以轻松构建 Redux Store 的工具集
- [Inject](https://github.com/google/inject.dart) - Google 开发的编译时依赖注入工具
- [Flux](https://github.com/google/flutter_flux) - Google 出品的 Flux 框架实现
- [Fish](https://github.com/alibaba/fish-redux) - 阿里巴巴 Redux 实现
- [Async Redux](https://pub.dev/packages/async_redux) - 支持同步和异步的 Redux 工具，[Marcelo Glasberg](https://github.com/marcglasberg/).

### Widgets

- [Hooks](https://github.com/rrousselGit/flutter_hooks) - widgets 之间交换数据，[Remi Rousselet](https://github.com/rrousselGit).
- [Functional widget](https://github.com/rrousselGit/functional_widget) - 代码生成器，可将 widget 编写为带有注释的函数，[Remi Rousselet](https://github.com/rrousselGit).

### 数据

- [Graphql](https://github.com/zino-app/graphql-flutter) - Graphql 组件，[Zino App B.V.](https://github.com/zino-app).
- [GeoFlutterFire](https://github.com/DarshanGowda0/GeoFlutterFire) -  GeoFirestore for flutter 组件，[Darshan Gowda](https://darshann.me/).
- [Ferry](https://github.com/gql-dart/ferry) - 强大且具有扩展性的 GraphQL 客户端，[Sat Mandir Khalsa](https://github.com/smkhalsa).


### 后端

- [Dynamic Widget](https://github.com/dengyin2000/dynamic_widget) - 基于 json 动态生成 UI，[Denny Deng](https://github.com/dengyin2000).
- [NETCoreSync](https://github.com/aldycool/NETCoreSync) - 用于多个客户端的集中式数据库同步框架，[Moor](https://github.com/simolus3/moor)，[Aldy J](https://github.com/aldycool).
- [Parse for Flutter](https://github.com/parse-community/Parse-SDK-Flutter/tree/master/packages/flutter) - 开源的后端框架，[ParsePlatform](https://parseplatform.org/).

### 动画

- [Sequence Animation](https://github.com/Norbert515/flutter_sequence_animation) - 各种组合动画，[Norbert Kozsir](https://twitter.com/norbertkozsir).
- [SpinKit](https://github.com/jogboms/flutter_spinkit) - loading 指示器动画，[Jeremiah Ogbomo](https://twitter.com/jogboms).
- [Villains](https://github.com/Norbert515/flutter_villains) - 页面跳转间动画，[Norbert Kozsir](https://twitter.com/norbertkozsir).
- [AnimatedTextKit](https://github.com/aagarwal1012/Animated-Text-Kit) - 酷炫的文字动画集合，[Ayush Agarwal](https://github.com/aagarwal1012/).
- [Drawing Animation](https://github.com/biocarl/drawing_animation) - 基于 SVG 的线条绘画动画特效，[Carl Hauck](https://twitter.com/cahaucks).
- [Simple Animations](https://github.com/felixblaschke/simple_animations) - 简单又酷炫的动画集合，[Felix Blaschke](https://github.com/felixblaschke).
- [Flutter-animation-set](https://github.com/efoxTeam/flutter-animation-set) - 简单的动画合集，[efoxTeam](https://github.com/efoxTeam).
- [Staggered Animations](https://github.com/mobiten/flutter_staggered_animations) - 为你的 ListView, GridView, Column 以及 Row 创建转场动画，[mobiten](https://mobiten.com/).
- [Animate Do](https://pub.dev/packages/animate_do) - 灵感来自于 Animate.css 的动画集，[Fernando Herrera](https://twitter.com/Fernando_Her85).
- [Funvas](https://github.com/creativecreatorormaybenot/funvas) - 基于 fun 和 canvas 的动画库，[creativecreatorormaybenot](https://twitter.com/creativemaybeno).


### 测试


- [Flutter Gherkin](https://github.com/jonsamwell/flutter_gherkin) - 全功能的 Gherkin 解析器和 UI 自动化测试运行器，[Jon Samwell](https://github.com/jonsamwell).

### 网页

- [Responsive Framework](https://github.com/Codelessly/ResponsiveFramework) - UI 自适应框架，[Codelessly](https://codelessly.com).

## 引擎

### 渲染

- [Graphx](https://github.com/roipeker/graphx) - 灵感来自于 Flash 的动画库，使绘画和制作动画变得无比简单，[Roi Peker](https://github.com/roipeker).

### 游戏

- [Flame](https://github.com/flame-engine/flame) - 极简的动画引擎，[Luan Nico](https://github.com/luanpotter).
- [SpriteWidget](https://github.com/spritewidget/spritewidget) - 用于构建复杂、高性能动画和 2D 游戏的工具集，[Viktor Lidholt](https://github.com/vlidholt).

#### 开源游戏

- [Flip](https://github.com/RedBrogdon/flutterflip) - 翻转游戏，[Andrew Brogdon](https://github.com/RedBrogdon).
- [2048](https://github.com/anuranBarman/2048) - 2048，[Anuran Barman](https://github.com/anuranBarman).
- [TRex](https://github.com/renancaraujo/trex-flame) - 经典的 Chrome 小恐龙游戏，[Renan C. Araújo](https://github.com/renancaraujo).
- [Crush](https://github.com/boeledi/flutter_crush) - 如何编写一个三消游戏，例如糖果传奇和宝石迷阵，[Didier Boelens](https://didierboelens.com).
- [Slide Puzzle](https://github.com/kevmoo/slide_puzzle) - 经典的滑块解谜，[Kevin Moore](https://github.com/kevmoo).
- [Tetris](https://github.com/boyan01/flutter-tetris) - 俄罗斯方块，[YangBin](https://github.com/boyan01).
- [Party Charades](https://github.com/vintage/party_flutter) - 聚会猜谜游戏，[Kamil Rykowski](https://github.com/vintage).
- [Ghost Rigger](https://github.com/Float-like-a-dash-Sting-like-a-dart/GhostRigger) - 幽灵跳线，是一款赛博朋克风格的解谜游戏，[Iain Smith](https://github.com/b099l3) 以及 [Julio Ernesto Rodríguez Cabañas](https://github.com/ernestoyaquello).
- [Space Empires](https://github.com/satyamx64/space_empires) - 一款以4X空间为主题的战略游戏，[Satyam Sharma](https://github.com/satyamx64).

#### 游戏引擎资源

- [Awesome Flame](https://github.com/flame-engine/awesome-flame)<!--stargazers:flame-engine/awesome-flame--> - 精心策划的最佳 Flame 游戏、项目、库、工具、教程、文章等的集合，[Flame Engine](https://github.com/flame-engine)


## 开源应用

### 高品质的

- [History Of Everything](https://github.com/2d-inc/HistoryOfEverything) - 垂直时间轴动画应用，展示了从宇宙大爆炸到网络时代的事件时间线，[2D, Inc](https://www.2dimensions.com/).
- [Developer Quest](https://github.com/2d-inc/developer_quest)  - 成为技术领导者，消灭 bug，[2D, Inc](https://www.2dimensions.com/).
- [AppFlowy](https://github.com/AppFlowy-IO/appflowy) - 开源的 Notion 替代品，你可以用它管理你的数据和知识库，使用 Flutter 和 Rust 开发，[AppFlowy team](https://www.appflowy.io/).

### 热门的

- [Flutter Team Samples](https://github.com/flutter/samples) - 实例合集 (包括 maps, json, Material 以及 Cupertino)，[Flutter team](https://github.com/orgs/flutter/people).
- [Flutter Common Widgets](https://github.com/alibaba/flutter-common-widgets-app) - 官方中文 widget 演示和文档的集合，帮助开发者快速学习，[Alibaba Auction Frontend Team](https://github.com/alibaba-paimai-frontend).
- [Meme Chat](https://github.com/efortuna/memechat) - 团队开发的聊天应用，集成了 Firebase，Google 登录，以及设备摄像头
- [Flitter](https://github.com/dart-flitter/flitter) - Gitter 客户端，项目使用了 Redux 和 Jaguar，[Hadrien Lejard](https://twitter.com/HadrienLejard) 和 [Kevin Segaud](https://twitter.com/kevin_segaud)
- [Lime](https://github.com/fablue/lime-flutter) - Lime 客户端，Sebastian Sellmair.
- [Planets](https://github.com/sergiandreplace/flutter_planets_tutorial) - 具有丰富 UI 的星球浏览器演示版本，[Sergi Martínez](http://sergiandreplace.com).
- [NewsBuzz](https://github.com/theankurkedia/NewsBuzz) - 集成 Firebase 和 news API 的新闻阅读器，[Ankur Kedia](https://github.com/theankurkedia).
- [DroidKaigi2018-flutter](https://github.com/konifar/droidkaigi2018-flutter) - DroidKaigi 2018 Toky 的非官方会议应用程序
[konifar](https://github.com/konifar).
- [Music Player](https://github.com/iampawan/Flutter-Music-Player) - 全功能的音乐播放器，[Pawan Kumar](https://about.me/imthepk).
- [WhatTodo](https://github.com/burhanrashid52/WhatTodo) - 仿 Todoist 的应用，[Burhanuddin Rashid](https://about.me/burhanrashid52).
- [FlutterGram](https://github.com/mdanics/fluttergram) - 基于 Firestore 和 Google Functions 的完整 Instagram 客户端，[MDanics](https://github.com/mdanics).
- [BookSearch](https://github.com/Norbert515/BookSearch) - 电子书架应用，[Norbert515](https://github.com/Norbert515).
- [Cinematic](https://github.com/aaronoe/FlutterCinematic) - 为 Movie DB 公开 API 编写的 UI 界面，[Aaron Oertel](https://github.com/aaronoe).
- [Beer-Me-Up](https://github.com/benoitletondor/Beer-Me-Up) - 设计精美的喝啤酒记录应用，[Benoit Letondor](https://github.com/benoitletondor).
- [Trace](https://github.com/trentpiercy/trace) - 现代且强大的数字资产投资/市场浏览器，[Trent Piercy](https://github.com/trentpiercy).
- [Taskist](https://github.com/huextrat/Taskist) - Taskist 是一个 ToDo List 应用，用于任务管理，[Hugo EXTRAT](https://github.com/huextrat).
- [Tourism](https://github.com/bluemix/tourism-demo) - 集成 redux、动画以及 i18n 的 Tourism 应用，[blueMix](https://github.com/bluemix/tourism-demo).
- [Trinity Orientation @ Univ Toronto](https://github.com/matthewtory/trinity-orientation-2018) - 剑桥大学三一学院迎新周应用，[Matthew Tory](https://github.com/matthewtory).
- [Transform Widget](https://github.com/DrPaulT/flutter-engine-test) - 3D 游戏引擎用的图片精灵 widgets，[Paul Thomas](https://github.com/DrPaulT).
- [Deer](https://github.com/aleksanderwozniak/deer) - 使用 BLoC 模式编写的极简 Todo 应用，[Aleksander Woźniak](https://github.com/aleksanderwozniak).
- [TailorMade](https://github.com/jogboms/tailor_made) - 使用 ReBLoC 和 Firebase 云存储和功能组合管理时装设计师的日常工作，[Jeremiah Ogbomo](https://twitter.com/jogboms).
- [Instory](https://github.com/InvertedX/instory) - 有精美 UI 的 Instagram 故事相册下载器，[Sarath](https://twitter.com/_sarath_kumar).
- [Spacex-Go](https://github.com/jesusrp98/spacex-go) - 简单而强大的开源 SpaceX 发射跟踪器，[jesusrp98](https://twitter.com/jesusrp98).
- [Superhero Interaction](https://github.com/pinkeshdarji/SuperHeroInteraction) - 超酷的超级英雄互动动画，[Pinkesh Darji](https://github.com/pinkeshdarji).
- [Reply](https://github.com/flschweiger/reply) - 复刻 Reply 客户端，[Frederik Schweiger](https://github.com/flschweiger).
- [Enigma](https://github.com/AmitJoki/Enigma) - 点对点加密的私密聊天工具，[AmitJoki](https://github.com/AmitJoki).
- [Chillify](https://github.com/KarimElghamry/chillify) - 使用 Provider 和 Bloc 模式开发的超棒的音乐播放器，[Karim Elghamry](https://github.com/KarimElghamry).
- [Pokedex](https://github.com/scitbiz/flutter_pokedex) - 有着 精美 UI 以及流畅动画的 Pokedex 应用，[Hung Pham](https://github.com/scitbiz).
- [Timy Messenger](https://github.com/janoodleFTW/timy-messenger) - 一款专注于组织活动的群组消息应用，[Miguel Beltran](https://github.com/miquelbeltran) 和 [Franz Heinfling](https://github.com/fheinfling).
- [GitJournal](https://github.com/GitJournal/GitJournal) - 在 Git 代码库中记日记，[Vishesh Handa](https://github.com/vHanda).
- [AuthPass](https://github.com/authpass/authpass) - 兼容 Keepass 的密码管理器，包含移动端和桌面端，[hpoul](https://github.com/hpoul).
- [Fwitter](https://github.com/TheAlphamerc/flutter_twitter_clone) - 使用 Firebase 服务完全克隆 Twitter，[Sonu Sharma](https://github.com/TheAlphamerc).
- [Harpy](https://github.com/robertodoering/harpy) - 功能丰富的 Twitter 客户端，[Roberto Doering](https://github.com/robertodoering).

## 工具集

- [Launcher Icons](https://github.com/franzsilva/flutter_launcher_icons) - 轻松生成你的启动页图标，[Mark O'Sullivan](https://github.com/MarkOSullivan94) 和 [Franz Silva](https://github.com/franzsilva).
- [FlutterIcon](http://fluttericon.com/) - Flutter 图标集，[Mike Hoolehan](https://github.com/ilikerobots).
- [FVM](https://github.com/leoafarias/fvm) - Flutter 版本管理: 一个简单的管理 Flutter SDK 版本的命令行工具
- [Environment Configuration](https://github.com/TatsuUkraine/dart_environment_config) - 用于给应用生成 `.env` 配置文件的命令行工具，[TatsuUkraine](https://github.com/TatsuUkraine).
- [Flutter Flavorizr](https://github.com/AngeloAvv/flutter_flavorizr) - 3分钟就可以为 Android 和 iOS 生成 flavors 的命令行工具，[Angelo Cassano](https://github.com/AngeloAvv).
- [Fontify](https://github.com/westracer/fontify) - 可以将 SVG 图标转化为 OTF 字体文件并生成 Flutter 支持的类的命令行工具，[Igor Kharakhordin](https://github.com/westracer).
- [FlutterGen](https://github.com/FlutterGen/flutter_gen) - 引用静态资源（图片，字体，颜色等）代码生成器
- [Very Good Cli](https://github.com/VeryGoodOpenSource/very_good_cli) -  Very Good 的命令行工具，[Very Good Ventures](https://github.com/VeryGoodOpenSource).
- [Flutter Sidekick](https://github.com/leoafarias/sidekick)  - 一个简单的应用，可以使 Flutter 开发更愉快，[Leo Farias](https://github.com/leoafarias).
- [Dart Code Metrics](https://github.com/dart-code-checker/dart-code-metrics) - 增强的检查程序，可以报告代码度量，检查反模式，并为 Dart 分析器提供额外的规则，[Dart Code Checker team](https://github.com/dart-code-checker).

### VSCode

- [Awesome Snippets](https://marketplace.visualstudio.com/items?itemName=Nash.awesome-flutter-snippets) - 常用的类和方法集合，[Nash](https://twitter.com/Nash0x7E2).
- [Flutter Files](https://marketplace.visualstudio.com/items?itemName=gornivv.vscode-flutter-files) - 快速生成 BLoC 模板文件的上下文菜单
，[Gorniv](https://github.com/gorniv).
- [Flutter Intl](https://marketplace.visualstudio.com/items?itemName=localizely.flutter-intl) - 关联 .arb 文件的 i18n 插件，[Localizely](https://twitter.com/localizely).


### IntelliJ / Android Studio

- [Enhancement_Suite](https://github.com/marius-h/flutter_enhancement_suite) - 查找 pub.dev 库, 更新版本, Bloc, 代码片段等等，[Marius Höfler](https://github.com/marius-h).
- [Flutter Intl](https://plugins.jetbrains.com/plugin/13666-flutter-intl) - 关联 .arb 文件的 i18n 插件，[Localizely](https://twitter.com/localizely).

### 桌面端

- [Desktop Embedding](https://github.com/google/flutter-desktop-embedding) - 谷歌的嵌入 Flutter API 的桌面实现
- [Golang Desktop Embedder](https://github.com/go-flutter-desktop/go-flutter) - 用于桌面端的 Golang 的嵌入器，[Pierre Champion](https://github.com/pchampio).
- [Native Shell](https://github.com/nativeshell/nativeshell) - 实验性的 Flutter 嵌入器，[Matej Knopp](https://twitter.com/matejknopp).
- [Rust Desktop Embedder](https://github.com/gliheng/flutter-rs) - 用于桌面端的 Rust 的嵌入器，[juju](https://github.com/gliheng).
- [bitsdojo_window](https://github.com/bitsdojo/bitsdojo_window) <!--bitsdojo/bitsdojo_window--> - 自定义桌面应用窗口，[BitsDojo](https://github.com/bitsdojo).
- [Raspberry Pi Embedder](https://github.com/ardera/flutter-pi) - 轻量级的树莓派嵌入器，[Hannes Winkler](https://github.com/ardera).
- [Fluent UI](https://github.com/bdlukaa/fluent_ui) - 基于 Microsoft 的 Fluent Design 系统 UI 设计的 wdgets，[Bruno D'Luka](https://twitter.com/bdlukaadev).
- [MacOS UI](https://github.com/GroovinChip/macos_ui) - 基于 MacOS UI 设计的 widgets，[Groovin Chip](https://twitter.com/GroovinChip).
- [Ubuntu Yaru](https://github.com/ubuntu/yaru.dart) - Ubuntu 桌面的独特外观和风格的 UI 库，[Ubuntu](https://github.com/ubuntu).
- [Awesome Flutter Desktop](https://github.com/leanflutter/awesome-flutter-desktop) - 与 Flutter 桌面相关的精彩内容的策划清单，[LeanFlutter](https://github.com/leanflutter).

## 书

### 学习 Flutter - 初学者
- [Beginning App Development](https://www.amazon.com/Beginning-App-Development-Flutter-Cross-Platform/dp/1484251806) - by [Rap Payne](https://github.com/rapPayne).
- [Beginning Flutter](https://www.amazon.com/Beginning-Flutter-Hands-Guide-Development/dp/1119550823) - by [Marco Napoli](https://github.com/JediPixels).
- [Flutter for Beginners](https://www.amazon.com/Flutter-Beginners-introductory-cross-platform-applications/dp/1788996089) - by [Alessandro Biessek](https://github.com/biessek).
- [Flutter in Action](https://www.amazon.com/Flutter-Action-Eric-Windmill/dp/1617296147) - by [Eric Windmill](https://github.com/ericwindmill).
- [Learn Google Flutter Fast](https://www.amazon.com/Learn-Google-Flutter-Fast-Example/dp/1092297375) - by [Mark Clow](https://github.com/markclow).

### 实战
- [Practical Flutter](https://www.amazon.com/Practical-Flutter-Improve-Development-Open-Source/dp/1484249712) - by [Frank Zammetti](https://github.com/fzammetti).


## 社区

### 演示材料

- [Logo](https://drive.google.com/drive/folders/1GDGdQ0ghrxTNTx6aZLT41eV5sPZvV7bU) - 漂亮的 Flutter 标志

### 交流社区

- [Gitter](https://gitter.im/flutter/flutter) - 交流频道
- [r/FlutterDev](https://www.reddit.com/r/FlutterDev/) - Reddit 社区，[u/JaapVermeulen](https://www.reddit.com/user/JaapVermeulen).
- [Discord](https://discord.gg/N7Yshp4) - Discord 讨论区，[Pritykin](https://twitter.com/AndrewPritykin).
- [Flutter Community](https://github.com/fluttercommunity) - 官方社区
- [OpenFlutter](https://github.com/OpenFlutter) - 让 Flutter 更简单.
- [Hashnode](https://hashnode.com/n/flutter) - 读写文章、参与讨论或者提问

