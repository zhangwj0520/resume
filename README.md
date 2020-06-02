## 张为杰个人简历

- 在线简历地址： [https://github.com/windego/resume](https://github.com/windego/resume)
- 手机：18803129525
- E-mail：576579227@qq.com
- Github: [Windego](https://github.com/windego)

### 教育背景

- 2010-9 ~ 2014-6：河北工业大学 通信工程 本科

### 技术能力

1. 熟练掌握并运用 react 框架,并了解其核心源码,熟练使用 redux,react-router,antd 等相关组件,目前主要使
   用 hooks
1. 掌握 ES6 等最新的 ECMA 规范,并运用到实际项目开发中
1. 熟悉前端自动化和工程化，可使用 webpack 搭建 react,vue 等项目
1. 熟练使用微信小程序原生框架以及 taro 框架进行小程序端开发
1. 熟练使用 node 进行后端 API 开发, 熟悉 express,koa,egg 等框架,熟悉 koa 源码
1. 熟悉 mysql,mongoDB 数据库,配合 node 实现数据库增删改查
1. 熟练使用 react native 及相关组件进行 App 开发,了解 rn 相关的 ios,android 环境配置,打包,软件发布等
   .
1. 了解 flutter 跨平台框架，并使用其构建过一些 App、web 端应用.

### 工作经历

> 2019.11 - 至今 北京顺丰同城科技有限公司

1. 工作内容

   - 公司对外 kfc 项目前端负责人，包括物流平台和运营平台，任务分配，项目开发。
   - 顺丰同城一站 saas 项目前端负责人，包括小程序端和 PC 管理后台，任务分配，项目开发。

2. 项目介绍

   - 1.kfc 百胜运营平台 (1.0 项目)

     - 技术栈:
       - react + react-router + antd4.0 + redux +umi/hooks
     - 项目介绍

       - 公司负责独立搭建的第一个项目,主要采用函数式组件写法,
       - 采用 create-react-app 方式搭建项目,fork react-scripts 并修改,主要涉及路径 alias、默认
         cssmodule ,配置 antd 按需加载等,
       - 集成 antd4.0, 封装 json-schema-form,
       - 基于 umijs/hooks 的 useFormTable 重新封装 useTable,
       - 状态管理使用@reduxjs/toolkit, 并封装 useActions,useStore 等方法
       - 组件延迟加载使用 React.lazy 和 Suspense 进行,基于 lazy 和 repalceReducer 封装 loadable,实现
         redux store 的动态注入
       - 项目中大部分功能需要使用地图,采用高德地图,并封装 hooks 组件

   - 2.kfc 项目物流平台

     - 技术栈
       - vue + vuex + axios
     - 项目介绍
       - 维护性项目

   - 3.saas 项目-商家端
     - 技术栈
       - react 全家桶
     - 项目介绍
       - 已有项目,saas 项目的后台管理系统,主要包括小程序店铺装修组件的定制化配置,以及商家的商品和订
         单管理,数据统计等
       - 添加数据图表统计功能时,采用 echart,并封装组件.
       - 随着业务代码增加，开发时项目启动速度慢，对项目进行优化，具体方式：采用路由拆分，.env 配置相
         应启动模块，对路由进行拆分，达到启动速度优化。后期又编写 vscode 拆件，可视化修改启动模块，
         以及修改后端代理地址，cookie 配置。
   - 4.sass 小程序
     - 技术栈
       - 原生小程序+redux
     - 项目介绍
       - saas 小程序服务商,模块化功能,用户可以根据实际需求添加不同功能,主要分餐饮版和通用版
   - 5.丰食小程序
     - 技术栈
       - 原生小程序+redux
     - 项目介绍
       - 企业团餐平台,主要功能复用 saas 小程序组件
   - 6.物流聚合平台 1.0 项目
     - 技术栈
       - react 全家桶
     - 项目介绍
       - 丰食的后台管理系统,开发周期短,复用了商家端的项目.
   - 7.丰食 H5 项目
     - 技术栈
       - 采用 taro
     - 项目介绍
       - 作为顺丰内部 app 丰声的微服务,之前团队有调研过 taro,丰食小程序项目因时间紧急未采用,到 H5 项
         目时,又需要重新做一遍功能,考虑尝试 taro
       - 采用了当时的 taro next beat 版本
       - 其中遇到了一些坑:地图打点,采用高德 sdk;下拉刷新,上拉加载更多,采用自定义封装实现;

> 2018.06 - 2019.11 北京多来点信息技术有限公司

1. 工作内容及项目介绍

- 公司内部 crm 系统,新功能开发及维护,主要包括 pc 端项目和 app 端项目
- pc 端项目采用 react+redux
- app 端项目 采用 react native

> 2016.01 - 2018.06 北京格林威尔科技有限公司

- 工作内容: 软件测试(黑盒)

> 2014.07 - 2016.01 瑞思康达科技发展有限公司

- 工作内容: 软件测试(黑盒)

> 个人独立项目: [药都云采购]小程序,企业采购平台

- 项目介绍
  - 小程序采用 taro+redux
  - 后台管理,采用 react+redux+echart 等
  - 后端使用 eggjs
  - 部署到阿里云
  - 配合公众号,添加微信,接入 Wechaty 微信机器人,自动拉群,定时发送公告信息
