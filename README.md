# APICloud 多端应用模板合集

> 本仓库中包含的项目都是基于APICloud多端技术开发的应用。 建议直接点击对应仓库检出单个项目作为学习研究。
> 如需在本仓库一并检出子模块，使用  ` clone `  命令时请添加  ` --recursive `  参数。

## 1. 《快速上手》[hello-app](https://github.com/apicloudcom/hello-app) ![](https://img.shields.io/github/stars/apicloudcom/hello-app?style=social)

` 源码地址 ` https://github.com/apicloudcom/hello-app

` 项目说明 `
该项目是为了向大家介绍多端技术 AVM.js 上手演示项目文档。 仓库重点关注 README.md 中的上手步骤文本。 可以通过该文档，从 0 到 1 搭建项目工具环境、创建项目、预览体验等基本操作。
另外还附带了提交打包等后续操作说明。推荐新手阅读使用。

## 2. 《组件合集 + 每日优鲜》[avm-simple](https://github.com/apicloudcom/avm-simple) ![](https://img.shields.io/github/stars/apicloudcom/avm-simple?style=social)

` 源码地址 ` https://github.com/apicloudcom/avm-simple

` 项目说明 `
该项目是一个组件 demo 、经典模板和生鲜电商完整案例的小合集。

在项目的 [组件集合示例](https://github.com/apicloudcom/avm-simple/tree/master/%E7%BB%84%E4%BB%B6%E7%A4%BA%E4%BE%8B%E5%90%88%E9%9B%86)
中展示了基础组件的调用效果，可以体验和预览组件的样式和交互。

在项目的 [多端案例-生鲜电商](https://github.com/apicloudcom/avm-simple/tree/master/%E5%A4%9A%E7%AB%AF%E6%A1%88%E4%BE%8B-%E7%94%9F%E9%B2%9C%E7%94%B5%E5%95%86)
中展示了一个完整的多端应用源码。 以便于从项目级别的场景下了解应用的整体关系和部分业务逻辑处理示例。

项目其他文件夹还包括了一些常用的页面模板，例如：仿朋友圈导航栏、仿淘宝首页和聊天界面等。

## 3. 《企业展示》[company-display](https://github.com/apicloudcom/company-display) ![](https://img.shields.io/github/stars/apicloudcom/company-display?style=social)

` 源码地址 ` https://github.com/apicloudcom/company-display

` 项目简介 `
此项目是一个企业展示类型的应用，主要功能包括企业信息展示、案例展示、加盟申请等。

` 技术要点 `
项目中前端采用 avm 多端开发技术进行开发，要点包括 TabLayout 布局、swiper 轮播图、rich-text 富文本、scroll-view 滚动视图、下拉刷新等。

` 截图展示 `

![preview](https://github.com/apicloudcom/company-display/raw/main/docs/preview.jpg)

## 4. 《堂食点餐》[ordering-food](https://github.com/apicloudcom/ordering-food) ![](https://img.shields.io/github/stars/apicloudcom/ordering-food?style=social)

` 源码地址 ` https://github.com/apicloudcom/ordering-food

` 项目说明 `
此项目是一个餐饮商户单商家堂食下单应用。 主要功能包括浏览商家主页信息、查看推荐菜品、下单商品、取餐等号等功能。 可以适用于小吃快餐餐饮商户的堂食点单管理，也可以进行稍微二开成为外卖、店铺或者是虚拟服务等电商小应用。

` 技术要点 `
项目中前端技术要点包括跨页面通信、全局购物车数据管理、自定义复用组件编写和辅助助手函数等等。 使用 APICloud 多端技术实现了一套代码，多端运行。 支持编译成 Android & iOS App 以及微信小程序。 项目后端使用的是
APICloud [数据云3.0](https://docs.apicloud.com/Cloud-API/sentosa?uzchannel=30) 来构建的：
通过编写云函数自动管理维护接口和数据，详细可以参考数据云的文档。也可以自定义后端接口，通过自写服务器完成开发。

` 截图展示 `

![preview](https://github.com/apicloudcom/ordering-food/raw/main/docs/preview.jpg)

## 5. 《服饰商城》[online-dress](https://github.com/apicloudcom/online-dress) ![](https://img.shields.io/github/stars/apicloudcom/online-dress?style=social)

` 源码地址 ` https://github.com/apicloudcom/online-dress

` 项目说明 `
此项目为在线服饰商城类应用，主要功能包括商品展示、商品搜索、购物车、订单管理等。适用于单商家电商类应用开发，快速构建自己的商城应用。

` 技术要点 `
项目中前端采用 avm 多端开发技术进行开发，要点包括 TabLayout 布局、swiper 轮播图、rich-text 富文本、scroll-view 滚动视图、下拉刷新、组件封装等。使用 APICloud
多端技术进行开发，实现一套代码多端运行，支持编译成 Android & iOS App 以及微信小程序。项目后端则是使用的 APICloud 数据云 3.0 自定义云函数来构建的。

` 截图展示 `

![preview](https://github.com/apicloudcom/online-dress/raw/main/docs/preview.jpg)

## 6. 《教育培训》[education-training](https://github.com/apicloudcom/education-training) ![](https://img.shields.io/github/stars/apicloudcom/education-training?style=social)

` 源码地址 ` https://github.com/apicloudcom/education-training

` 项目说明 `
此项目是一个教育培训的机构服务应用，包括了线上线下课的课程展示、师资力量的名师名片展示、在线预约、在线下单购买课程、用户订单预约管理等功能。

` 技术要点 `
本项目在开发过程中，在“能拆就拆”的思想下，对项目进行细粒度的组件化拆解。 可以从中了解到组件拆分逻辑和一些操作技巧，对自定义组件进行巩固。

1. 组件的高级使用方法：诸如使用条件渲染、引入自定义函数对模板节点进行处理和继承，以及特殊节点 children 等使用 。
2. 组件的设计流程：例如实现 a-tabs ，对于复杂的组件可以先定义使用外观，然后反向填充细节逻辑。
3. 组件的设计原则：多出重复的页面结构就需要考虑提炼和归纳。设计出来的组件需要易用、简洁。

` 截图展示 `

![preview](https://github.com/apicloudcom/education-training/raw/main/docs/preview.jpg)

## 7. 《生鲜电商》[fresh-ec](https://github.com/apicloudcom/fresh-ec) ![](https://img.shields.io/github/stars/apicloudcom/fresh-ec?style=social)

` 源码地址 ` https://github.com/apicloudcom/fresh-ec

` 项目说明 `
此项目为生鲜电商类应用，主要功能包括商品列表、商品详情展示、购物车、登录注册、个人中心等。也是2.x版本的培训课程项目升级到3.x的一个典型案例。

` 技术要点 `
项目中前端采用 avm 多端开发技术进行开发，要点包括 scroll-view 滚动视图、下拉刷新、输入处理、swiper 轮播图、网络请求封装等。 使用 APICloud 多端技术进行开发，实现一套代码多端运行，支持编译成 Android
& iOS App 以及微信小程序。

` 截图展示 `

![preview](https://github.com/apicloudcom/fresh-ec/raw/main/docs/preview.jpg)