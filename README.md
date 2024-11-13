![Glitch Art](https://glitch-art.vercel.app/api/simple?word=Blackcell)


### Hi there, I am BastKakrolot👋

> A Front end developer from **WuHan, China**.

### 🏗️ Learning:

<code><img src="https://img.shields.io/badge/typescript-%23007ACC.svg?style=for-the-badge&logo=typescript&logoColor=white"/></code>
<code><img src="https://img.shields.io/badge/react-%2320232a.svg?style=for-the-badge&logo=react&logoColor=%2361DAFB"/></code>
<code><img src="https://img.shields.io/badge/node.js-6DA55F?style=for-the-badge&logo=node.js&logoColor=white"/></code>
<code><img src="https://img.shields.io/badge/vuejs-%2335495e.svg?style=for-the-badge&logo=vuedotjs&logoColor=%234FC08D"/></code>
<code><img src="https://img.shields.io/badge/nextjs-%2320232a.svg?style=for-the-badge&logo=nextdotjs&logoColor=%234FC08D"/></code>

### 📫 Reach me:

- **QQ** : 572383082
- **WeChat** : zzzs20
- **Phone** : 18202797144
- **E-mail** : blackcellcode@gmail.com

<details>
    <summary align="center"><b>我的简历</b></summary>

## 联系信息
- **手机**: （+86）18202797144
- **邮箱**: blackcellcode@gmail.com
- **GitHub**: github.com/BastKakrolot
- **掘金**: juejin.cn/user/4441682706969917
- **博客**：next.blackcell.top

## 个人简介

- 熟悉代码开发到上线全流程，对协同开发，分支管理，项目配置等都有较深刻的最佳实践 ，经历过多种分支模型
- 会多审视重构代码，在 Gitlab 上对组内成员进行 code review 积极组织前端分享会，以及代码审查会
- 有中后台大型项目、移动端开发经验，熟悉前端性能优化的实现，例如代码优化、打包优化、资源优化，能结合实际业务场景进行优化
- 熟悉 Webpack 等打包工具的基本配置， 能够对以上工具进行二次封装、基于以上工具搭建通用的开发环境
- 熟悉 prettier / eslint 基本配置，有良好且严格的编码习惯
- 能按照 UI 完成页面还原，任务完成度高

## 工作经验

### XX科技有限公司 - 前端工程师/研发中心/大前端组 （ 2022.02 - 2024.04）

- 负责组内公共组件开发建设工作（可编辑表格等，虚拟列表，可拖动列，）
- 负责组内项目维护，底层逻辑优化，比如开发中途添加主题功
- 负责组内成员任务分配 & CodeReview 工作
- 维护组内代码规范，持续输出项目文档
`react` `ahooks` `Umi` `Antd` `Css-Module` `JSX` ...

### XX有限公司 - web前端 （2019.07 - 2022.02）

- 开发了移动端和桌面端的高保真界面，采用了响应式设计。
- 实现了复杂的前端交互逻辑和组件复用。
 `swiper` `vue` `Bootstrap` `jquery` `animate` ...

### XX科技有限公司 - 前端开发工程师 （2017.07 - 2019.07）
- 开发了PC端的多个项目（包括但不限于一窗受理系统，土地二级交易市场，统一 OA等）。
- 对静态资源核心库进行维护和更新。
- 为旧项目重新搭建底层框架，优化和升级原有系统。
`elementui` `highcharts` `requirejs` `vue` `axios` ...

## 个人项目/作品集

### 基于Next的博客项目

这是我个人开发的博客项目，可以在联系信息中访问我的主页进行查看，该博客使用Next14 进行搭建，支持自动部署实现CI/CD，提交后会调用github的工作流，通过读取配置文件，进行打包。然后将打包后的镜像推送至dockerhub，然后远程调用服务器拉取最新的docker镜像部署，至此可以完成持续部署。博客使用的域名证书通过acme.sh进行自动化续签，该博客支持mdx，可以再编写文章时调用配置好的组件进行更优美的展示，在完成这个功能时发现mdx与部分最新版本的插件不兼容，因此排查了许久，最后通过降级完成此部分功能，此项目能够学习最前沿技术的同时也能让自己的基础更加巩固。数据的存储使用的MongoDB，通过app-router进行获取，其中有部分数据是通过server-Component直接加载，登录部分使用next-auth进行鉴权，可以接入多种登录。
 `mongodb` `next-auth` `vditor` `react-photo-view` `ahooks` `tailwindcss` `next-mdx-remote` `react-mde` `@nextui-org/react` `@mui/material` `@ricons/fa`...

## 供应链管理系统

在此项目中我负责新模块开发，公共组件维护等任务。在开发新模块时能够清晰认知业务需求，高效完成模块搭建。自觉担当公共组件维护工作，这个项目中，当表格数据量达到十万级时，页面会卡死，即使没卡死也会导致编辑过程异常卡顿，使用虚拟列表以及优化编辑逻辑，重构表格内部代码删除冗余方法和过程，使该组件内部细分各个模块，便于日后维护和扩展，并且添加拖拽排序功能，对于十万级数据的编辑也能做到流畅无卡顿，最后此组件在公司内部得到高评价，许多项目都应用了此组件。提倡使用hooks编程，将ui与逻辑分离，大大提高开发效率！维护供应链代码规范，持续更新供应链组件文档，持续输出项目文档。
`Umi3.5` `ahooks` `antd` `React` `mobx` `dva` `v-list` `fomily` ...

## 微信点单程序

项目使用微信小程序框架开发，登陆后获取id，用户详情，订单信息等进行socket连接前后台交互；首页分为6个模块：首页展示、餐品点单、订单提交页、订单列表、订单详情、个人中心。首页展示主要展示当前推荐商品以及用户基本信息和操作按钮，餐品点单页面进入后会选择用餐人数，在餐品列表上方也会展示当前推荐餐品，左侧分类和右侧餐品列表实现联动，用户点完餐品后会进入订单提交页面。 订单提交页面展示用户所选商品列表、就餐人数、餐厅地址点击可进入地图查看并可以进行导航、电话点击可直接拨打、用户选择预约时间，确认完毕后进入支付，支付成功则会进入订单详情页面。订单详情页面展示当前订单信息，流水号，交易号等信息。订单列表展示用户历史订单以及进行中订单基本信息，点击后可进入订单详情查看。中心页面展示用户头像，积分，优惠券等信息

# 致谢
感谢您花时间阅读我的简历，期待能有机会和您共事。

</details>

### 🏠 Blog:

- **[https://juejin.cn/user/4441682706969917](https://juejin.cn/user/4441682706969917)**
- **[https://next.blackcell.top/](https://next.blackcell.top/)**

### 📊 Stats:

| <img align="center" src="https://github-readme-stats.vercel.app/api?username=BastKakrolot&show_icons=true&theme=buefy&hide_border=true" alt="" /> | <img align="center" src="https://github-readme-stats.vercel.app/api/top-langs/?username=BastKakrolot&layout=compact&theme=buefy&hide_border=true" alt="" /> |
| ------------------------------------------------------------------------------------------------------------------------------------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------- |

### ✨ 模板来自 [li-jia-nan](https://github.com/li-jia-nan) 十分感谢!!
