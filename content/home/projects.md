+++
# A Projects section created with the Portfolio widget.
widget = "portfolio"  # See https://sourcethemes.com/academic/docs/page-builder/
headless = true  # This file represents a page section.
active = true  # Activate this widget? true/false
weight = 65  # Order that this section will appear.

title = "项目经历"
subtitle = ""

[content]
  # Page type to display. E.g. project.
  page_type = "project"
  
  # Filter toolbar (optional).
  # Add or remove as many filters (`[[content.filter_button]]` instances) as you like.
  # To show all items, set `tag` to "*".
  # To filter by a specific tag, set `tag` to an existing tag name.
  # To remove toolbar, delete/comment all instances of `[[content.filter_button]]` below.
  
  # Default filter index (e.g. 0 corresponds to the first `[[filter_button]]` instance below).
  filter_default = 0
  

[design]
  # Choose how many columns the section has. Valid values: 1 or 2.
  columns = "1"

  # Toggle between the various page layout types.
  #   1 = List
  #   2 = Compact
  #   3 = Card
  #   5 = Showcase
  view = 1

  # For Showcase view, flip alternate rows?
  flip_alt_rows = false

[design.background]
  # Apply a background color, gradient, or image.
  #   Uncomment (by removing `#`) an option to apply it.
  #   Choose a light or dark text color by setting `text_color_light`.
  #   Any HTML color name or Hex value is valid.
  
  # Background color.
  # color = "navy"
  
  # Background gradient.
  # gradient_start = "DeepSkyBlue"
  # gradient_end = "SkyBlue"
  
  # Background image.
  # image = "background.jpg"  # Name of image in `static/img/`.
  # image_darken = 0.6  # Darken the image? Range 0-1 where 0 is transparent and 1 is opaque.

  # Text color (true=light or false=dark).
  # text_color_light = true  
  
[advanced]
 # Custom CSS. 
 css_style = ""
 
 # CSS class.
 css_class = ""
+++



### 壹品仓
<span class="dim">iOS</span>

壹品仓是⼀款做品牌特卖的应⽤软件，软件为⽤户提供了服装箱包类品牌的特价销售、限时抢购等服务，⽬前累计⽤户超过130w，平均⽇活近2w。通过线上线下结合的⽅式，来⽅便⽤户使⽤。

该App主要使用了OC语言开发，但是在项目中做了很多混合开发的工作，比如使用flutter开发一些轻量级页面，还有使用Vue开发移动端H5页面集成到项目中。⼯作期间负责了旧有项⽬部分模块的升级和优化，解决较多线上bug，提升整个App使⽤的流畅度和稳定性，优化iOS混合开发架构。独⾃完成整个壹品仓iOS App扫码购⼤版本的升级和开发。为App赋能，开发实现了直播功能，可以让店员和⽤户在同⼀个App上实现开直播和观看直播的功能。并实现弹幕特效和数据记录禁⾔等功能。


### MOS智慧零售
<span class="dim">iOS & Android</span>

MOS智慧零售是妈咪全知道服务所有特许经营连锁的信息化、数字化管理中心。其中主要包含了线下门店，运营管理和加盟导师等多种角色的登陆使用，以及各个角色下不同权限及功能的管理中心。主要功能模块包含了订货，经营数据，库存管理，订单管理，商品管理，远程巡店,还涉及到了分销功能，团长大团长的社区团购模式。

主要技术使用了uni-app跨平台开发框架，采用js+scss+vue的技术栈，以及u-view，u-charts等UI组件和图表组件等。整个App的前台开发，上架管理都是由我一个人独自负责的。其中最困难和最麻烦的事情就是要考虑各种手机屏幕的适配问题，以及iOS和Android平台的兼容性。目前该App主要为公司旗下的特许经营门店，门店管理运营和招商部门的使用。


### MOS终端
<span class="dim">Uni-app</span>

MOS终端是一款主要针对商用Android平板应用，使用的平台为SUNMI M2 MAX无线数据终端。主要为门店提供智能订货、会员运营、知识学习、数据分析等服务的一款产品，同时又包含了配合收银系统的订单管理，和MOS盘点系统的出入库订单，盘点仓库等功能。

该项目全部采用uni-app跨平台开发框架开发，整个项目的前台架构和分包策略，以及基础工具的搭建和订货模块，经营数据模块和会员管理模块前台部分都由我独自完成。


### ⼩草评
<span class="dim">微信小程序</span>

专为博主打造的好物试⽤⼩程序，功能包含活动报名，以及照片墙，试用评测报告的编辑和上传等。全部采用微信自有小程序的工具和环境开发，该⼩程序由本⼈独⾃负责开发。经过⼀年多的多个版本更新优化，总⽤户量有30w+。


### 星选好店
<span class="dim">微信小程序</span>

主要提供优质即时配送服务，为商家助⼒外卖⾃运营，全部采用微信自有小程序的工具和环境开发。除了传统的红包裂变玩法外，⾸创外卖AA付款拼单模式，我负责⻔店展示和选择菜品，拼单和⽀付，配送信息以及订单管理等开发，以及后期多个版本迭代的开发任务。2020年1⽉9⽇在⼴州举办的微信公开课PRO中，微信官⽅在餐饮分会和⼩程序助⼿分会都展示和推介了该⼩程序。

### 优小店商家版
<span class="dim">iOS混合开发</span>

优小店是一个微信小程序端的外卖平台，所以为了方便商家的订单管理以及数据管理等，开发了优小店商家版这款App，涉及到了通过消息通知来进行手机语音播报，对订单对金额和菜品准备给予提醒。同时需链接蓝牙打印机，通过消息通知获取订单详情，进行订单打印。这些核心的功能都是在iOS原生的基础上，进行开发的， 后期的一些商品管理，订单查询等等展示功能的页面，都是通过嵌入uni-app开发的移动h5实现的。


### 小满电商
<span class="dim">iOS</span>

“北京小满云创文化产业有限公司”旗下，由我司承接开发的同名垂直电商平台，入驻品牌以服装、3C、家居、影视衍生品、动漫衍生品和艺术衍生品等六大品类为主；结合买手模式，优选全范围内具美学质感的创意产品，以满足消费者个性化购物需求。这是我工作开的参与的第一个项目，在整个开发中我更多的承担助手的角色，当时负责电商的基础模块，主要开发收货地址的管理功能，和订单的列表以及订单的详情操作等。正式的开始接触iOS开发工作，带给了我很多不一样的东西，同时也感谢当时项目里帮助过我的同事。


