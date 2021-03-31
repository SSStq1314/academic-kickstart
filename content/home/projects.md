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



### MOS智慧零售
<span class="dim">iOS & Android</span>

MOS智慧零售是妈咪全知道服务所有特许经营连锁的信息化、数字化管理中心，是一个面向To B的应用程序。其中主要包含了线下门店，运营管理和加盟导师等多种角色的登陆使用，以及各个角色下不同权限及功能的管理中心。主要功能模块包含了订货，招商，经营数据，库存管理，订单管理，商品管理，远程巡店，资金管理，直播和促销活动的分享等，还涉及到了分销功能，团长大团长的社区团购模式。在APP内可以做到订货，查看经营数据，门店的会员概览，员工管理等业务，以及销售订单，配货单等功能；也可以进行招商拓客，知识学习。主要技术使用了uni-app跨平台开发框架，采用js+scss+vue的技术栈，以及u-view，u-charts等UI组件和图表组件等。整个App的前台开发，上架管理都是由我一个人独自负责的。其中最困难和最麻烦的事情就是要考虑各种手机屏幕的适配问题，以及iOS和Android平台的兼容性。目前该App，已经经过5个小版本的迭代，主要为公司旗下的特许经营门店，门店管理运营和招商部门的使用。

### MOS终端
<span class="dim">Android商用平板</span>

MOS终端是一款主要针对商用Android平板应用，使用的平台为SUNMI M2 MAX无线数据终端。MOS终端由店主或店长发起向妈咪全知道总部订货的行为，主要为门店提供智能订货、会员运营、知识学习、数据分析等服务的一款产品，同时又包含了配合收银系统的订单管理，和MOS盘点系统的出入库订单，盘点仓库等功能。除了以上特有功能外，还涉及到了商品促销活动管理，门店的销售经营数据分析，门店所有顾客和会员的管理，以及总部动态新闻资讯等功能。其中初期第一版本的订货模块，经营数据模块和会员管理模块前台部分由我完成开发工作，整个项目的前台架构和分包策略，以及基础工具的搭建有我独自完成。


### 星选好店
<span class="dim">微信小程序</span>

【星选好店】公司自有项目，主要是提供优质即时配送服务，为商家助力外卖自运营。星选好店的产品逻辑就是通过企业微信+小程序让流量回归到商家，帮助商家构建私域流量。再通过一系列运营工具帮助商家形成交易转化。让商家摆脱平台的束缚。星选好店也支持商家生成一个自己的专属小程序用于建立线上品牌。在整个项目的开发运营过程中，我负责基础的业务功能，如门店的切换和门店菜品的展示选择，下单和支付整个流程的实现，后期还负责部分优化功能，配合产品提出的功能做业务调整和优化。该项目从开发完后，一直运营至今，其中在2020年1月9日的下午，在广州举办的微信公开课PRO中，微信官方在餐饮分会和小程序助手分会都展示和推介了该小程序。


### 优小店商家版
<span class="dim">iOS & 移动前端</span>

优小店是一个微信小程序端的外卖平台，所以为了方便商家的订单管理以及数据管理等，开发了优小店商家版这款App，涉及到了通过消息通知来进行手机语音播报，对订单对金额和菜品准备给予提醒。同时需链接蓝牙打印机，通过消息通知获取订单详情，进行订单打印。这些核心的功能都是在iOS原生的基础上，进行开发的， 后期的一些商品管理，订单查询等等展示功能的页面，都是通过嵌入uni-app开发的移动h5实现的。


### 小满电商
<span class="dim">iOS</span>

“北京小满云创文化产业有限公司”旗下，由我司承接开发的同名垂直电商平台，入驻品牌以服装、3C、家居、影视衍生品、动漫衍生品和艺术衍生品等六大品类为主；结合买手模式，优选全范围内具美学质感的创意产品，以满足消费者个性化购物需求。这是我工作开的参与的第一个项目，在整个开发中我更多的承担助手的角色，当时负责电商的基础模块，主要开发收货地址的管理功能，和订单的列表以及订单的详情操作等。正式的开始接触iOS开发工作，带给了我很多不一样的东西，同时也感谢当时项目里帮助过我的同事。


