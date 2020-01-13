# front-end-awesome

[![front-end-awesome](https://camo.githubusercontent.com/13c4e50d88df7178ae1882a203ed57b641674f94/68747470733a2f2f63646e2e7261776769742e636f6d2f73696e647265736f726875732f617765736f6d652f643733303566333864323966656437386661383536353265336136336531353464643865383832392f6d656469612f62616467652e737667)](https://github.com/iq9891/awesome-frontend)

## 目录

- [打包工具](#打包工具)
- [webpack loader 和插件](#webpack-loader-和插件)
- [包管理](#包管理)
- [框架](#框架)
  - [Canvas 相关](#Canvas-相关)
  - [APP 相关](#APP-相关)
  - [CSS 相关](#CSS-相关)
  - [小程序 相关](#小程序-相关)
  - [其他](#其他)
- [React 相关库](#React-相关库)
- [Vue 相关库](#Vue-相关库)
  - [UI 库](#UI-库)
  - [其他](#其他)
- [阿里系](#阿里系)
- [工具类](#工具类)
- [数据流](#数据流)
- [语言](#语言)
- [文档](#文档)
- [工程](#工程)
- [编辑器](#编辑器)
- [命令行](#命令行)
- [请求处理](#请求处理)
- [富文本相关](#富文本相关)
- [持续集成](#持续集成)
- [在线工具](#在线工具)
  - [在线编程](#在线编程)
  - [转换](#转换)
  - [图标管理](#图标管理)
  - [其他在线工具](#其他在线工具)
- [代码高亮](#代码高亮)
- [音频/视频](#音频/视频)
- [数据可视化库](#数据可视化库)
- [动画库](#动画库)
- [数据模拟](#数据模拟)
- [调试工具](#调试工具)
- [源码分析](#源码分析)
- [其他](#其他)

----

## 打包工具

* [**webpack**][1-1] - 打包项目
* [**rollup**][1-2] - 打包 npm 库
* [**parcel**][1-3] - webpack 竞品，但发展前景不乐观，再观察一段时间
* [**@pikapkg/pack**][1-4] - 又一组件打包工具
* [**systemjs**][1-5] - 针对一些特殊场景会比较有用，比如云 ide，支付宝小程序 IDE 等
* [**microbundle**][1-6] - 基于 rollup，简化配置
* [**bili**][1-7] - 基于 rollup，同上
* [**webpack-dev-server**][1-8] - webpack 开发服务器
* [**webpack-dev-middleware**][1-9] - webpack 中间件
* [**vue-cli**][1-10] - vue 命令行工具
* [**create-react-app**][1-11] - react 官方脚手架
* [**webpack-merge**][1-12] - 合并 webpack 配置
* [**webpack-chain**][1-13] - 通过 chain 风格 api 的方式修改 webpack 配置
* [**prepack**][1-14] - 通过预先执行的方式优化打包结果
* [**swc**][1-15] - 基于 rust 的语法转换器，babel 的竞争者
* [**nathan/pax**][1-16] - 基于 rust，据说是这个星球最快的 JavaScript 打包工具
* [**pikapkg/web**][1-17] - 浏览器里跑 npm 依赖，面向现代浏览器
* [**lebab/lebab**][1-18] - 把 es5 代码转成 es6，反向 babel
* [**palmerhq/tsdx**][1-19] - Zero-config CLI for TypeScript package development

[⬆️ 返回首页](#目录)

## webpack loader 和插件

* [**hard-source-webpack-plugin**][2-1] - 性能提升 70%，但有坑
* [**svgr**][2-2] - svg 转 react 组件
* [**postcss**][2-3] - CSS 界的 babel
* [**autoprefixer**][2-4] - 为 CSS 选择权自动加 prefix
* [**cssnano**][2-5] - CSS 压缩，也有类 preset 的概念
* [**mini-css-extract-plugin**][2-6] - 提取 CSS 为单独文件
* [**webpackbar**][2-7] - webpack 进度条
* [**webpack-bundle-analyzer**][2-8] - 构建产物占比分析
* [**uglifyjs-webpack-plugin**][2-9] - JS 压缩，产物为 ES5 语法
* [**terser-webpack-plugin**][2-10] - JS 压缩，产物为 ES6 语法
* [**webpack-manifest-plugin**][2-11] - 生成 manifest.json
* [**copy-webpack-plugin**][2-12] - 复制额外的文件到输出目录
* [**case-sensitive-paths-webpack-plugin**][2-13] - 大小写敏感检测，能规避一些问题，但构建时性能消耗较大
* [**css-hot-loader**][2-14] - CSS 热更新，搭配 mini-css-extract-plugin 使用
* [**duplicate-package-checker-webpack-plugin**][2-15] - 重复依赖检测
* [**fork-ts-checker-webpack-plugin**][2-16] - ts 语法检测
* [**speed-measure-webpack-plugin**][2-17] - 统计 webpack 各阶段耗时

[⬆️ 返回首页](#目录)

## 包管理

* [**yarn**][3-1] - 我用这个
* [**npm**][3-2]
* [**bower**][3-3]

## 框架

### Canvas 相关

* [**cocos2d-html5**][4-1-1]
* [**Egret Engine**][4-1-2]
* [**LimeJS**][4-1-3]
* [**EaselJS**][4-1-4]
* [**three.js**][4-1-5]
* [**AlloyStick**][4-1-6]
* [**The-Best-JS-Game-Framework**][4-1-7]
* [**CanvasEngine**][4-1-8]
* [**Quintus**][4-1-9]
* [**Stage.js**][4-1-10]
* [**phaser**][4-1-11] - 一个快速、免费、开源的 HTML5 游戏框架
* [**lufylegend.js**][4-1-12]
* [**pixi.js**][4-1-13]

[⬆️ 返回首页](#目录)

### APP 相关

* [**weex**][4-2-1]
* [**react-native**][4-2-2]
* [**原生APP体验的高性能框架 mui**][4-2-3]
* [**Fries**][4-2-4]
* [**Flutter**][4-2-5] - 使构建精美的移动应用程序变得轻松快捷

### CSS 相关
* [**Bootstrap**][4-3-1]
* [**UIkit**][4-3-2]
* [**Framework7**][4-3-3]
* [**ionic framework**][4-3-4]
* [**jQuery Mobile**][4-3-5]
* [**Layui**][4-3-6]
* [**topcoat**][4-3-7]

### 小程序 相关

* [**mpvue**][4-4-1] - 基于 Vue.js 的小程序开发框架，从底层支持 Vue.js 语法和构建工具体系
* [**wepy**][4-4-2] - 小程序组件化开发框架
* [**westore**][4-4-3] - 微信小程序解决方案 - 1KB javascript 覆盖状态管理、跨页通讯、插件开发和云数据库开发
* [**ColorUI**][4-4-4] - 鲜亮的高饱和色彩，专注视觉的小程序组件库
* [**Gitter**][4-4-5] - 采用 Taro 框架 + Taro UI 进行开发的 demo ， 可能是目前颜值最高的 GitHub 微信小程序客户端
* [**Taro**][4-4-6] - 多端统一开发框架，支持用 React 的开发方式编写一次代码

[⬆️ 返回首页](#目录)

### 其他

* [**react**][4-5-1]
* [**vue**][4-5-2]
* [**next.js**][4-5-3]
* [**nuxt.js**][4-5-4]
* [**gastby**][4-5-5]
* [**umi**][4-5-6] - 蚂蚁金服的前端框架
* [**rekit**][4-5-7] - IDE and toolkit for building scalable web applications with React, Redux and React-router
* [**choo**][4-5-8] - dva 最初的 API 是参考这个实现的，已经不怎么发展了，再关注一段时间
* [**after.js**][4-5-10]
* [**mint**][4-5-11] - 提供了语言层方案的框架
* [**quasar**][4-5-12] - 基于 vue，一套代码多处适用
* [**Angular**][4-5-13]
* [**Foundation**][4-5-14]
* [**Polymer**][4-5-15] - Google发布的Web组件构建框架
* [**cyclejs**][4-5-16]

## React 相关库

* [**preact**][5-1] - 轻量级 React 实现
* [**inferno**][5-2] - 轻量级 React 实现
* [**react-router**][5-3] - React 路由方案
* [**reach-router**][5-4] - React 路由方案，较新，优势是可访问性
* [**router5**][5-5] - 通用的路由方案
* [**react-loadable**][5-6] - 按需加载 react 组件
* [**material-ui**][5-7] - UI 库
* [**react-intl**][5-8] - React 的国际化方案
* [**react-dnd**][5-9] - 拖拽实现
* [**react-helmet**][5-10] - 修改 html 的 header 内容
* [**react-jsonschema-form**][5-11] - A React component for building Web forms from JSON Schema
* [**react-dates**][5-12] - 适用于网络的易于国际化，移动友好的日期选择器库
* [**theme-ui**][5-13] - 根据基于约束的设计原则构建一致的主题化React应用

[⬆️ 返回首页](#目录)

## Vue 相关库

### UI 库

* [**quasar**][6-1-1]
* [**vue-material**][6-1-2]
* [**vuetify**][6-1-3]
* [**muse-ui**][6-1-4]
* [**buefy**][6-1-5]
* [**element-ui**][6-1-6]
* [**vulma**][6-1-7]
* [**vue-bulma-components**][6-1-8]
* [**iview-ui**][6-1-9]
* [**AT-UI**][6-1-10]
* [**v-semantic**][6-1-11]
* [**bootstrap-vue**][6-1-12]
* [**fish-ui**][6-1-13]
* [**Zircle UI**][6-1-14]
* [**vue-mdc-adapter**][6-1-15]
* [**Material Components Vue**][6-1-16]
* [**PrimeVue**][6-1-17]
* [**vuesax**][6-1-18]
* [**vuecidity**][6-1-19]
* [**water**][6-1-20]
* [**vant**][6-1-21]

### 其他

* [**vue-router**][6-2-1]
* [**vue-cropper**][6-2-2] - 一个简单的图片剪辑插件，支持海报图片剪辑
* [**vue-pretty-logger**][6-2-3] - 本编辑器的 Vue 版
* [**vue-icon**][6-2-4] - 简单的 icon 组件
* [**vue-baidu-map**][6-2-5] - 百度地图的 vue 版
* [**Vue.Draggable**][6-2-6] - 基于Sortable.js的Vue拖放组件
* [**vue-codemirror**][6-2-7] - codemirror 的 vue 封装
* [**vue-apollo**][6-2-8] - 连接 Vue 和 GraphQL/Apollo 的一座桥梁
* [**eagle.js**][6-2-9] - 一个使用 Vue 构建的功能强大、灵活且独特的幻灯片系统
* [**vue-color**][6-2-10] - 颜色选择器
* [**seat-select**][6-2-11] - 选座 C 端
* [**seat-select-controller**][6-2-12] - 选座 B 端后台
* [**vue-cli3-config**][6-2-13] - Vue-cli3 配置 vue.config.js 持续更新
* [**sing-app-vue-dashboard**][6-2-14] - Sing App Vue 仪表板
* [**vue-storefront**][6-2-15] - 这是一个 PWA 应用，可以与任何后端（或几乎任何后端）连接
* [**vue-virtual-scroller**][6-2-16] - 快速滚动条
* [**v-calendar**][6-2-17] - 用于构建日历的无依赖插件
* [**vue-design-system**][6-2-18] - 一组 UI 工具
* [**light-blue-vue-admin**][6-2-19] - 用于管理信息中心的 Vue.js 模板
* [**vue-grid-layout**][6-2-20] - Vue.js 的网格布局
* [**vue-content-loader**][6-2-21] - 创建占位符加载
* [**vue-js-modal**][6-2-22] - 高度可定制的 Modal
* [**vue2-animate**][6-2-23] - 集成 Animate.css 的动画库
* [**vuetensils**][6-2-24] - 一些常用组件
* [**easyjs**][6-2-25] - 拥有 Egg Vue SSR 服务端渲染

[⬆️ 返回首页](#目录)

## 阿里系

* [**ant-design**][7-1] - 蚂蚁金服的 React UI 库
* [**antvis**][7-2] - 数据可视化集合
* [**ant-motion**][7-3] - 动画说明和Ant设计组件
* [**@umijs/hooks**][7-4] - React Hooks 库
* [**qiankun**][7-5] - 为微型前端提供快速，简单和完整的解决方案

## 工具类

* [**history**][8-1]
* [**path-to-regexp**][8-2] - path 转正则，路由相关处理的底层库
* [**lodash**][8-3] - 工具集合
* [**fastclick**][8-4]
* [**date-fns**][8-5] - 时间处理
* [**immutable-js**][8-6] - 数据集控制
* [**sprint**][8-7]
* [**dayjs**][8-8] - 在javascript中解析，验证，操作和显示日期，类似 moment
* [**fecha**][8-9] - 小巧的时间格式化库
* [**tui.calendar**][8-10] - 日历库
* [**em-cookie**][8-11] - cookie 的处理
* [**EM-NORMALIZE**][8-12] - 样式重置
* [**modernizr**][8-13] - Modernizr是一个JavaScript库，可以在用户的​​浏览器中检测HTML5和CSS3功能
* [**gpu.js**][8-14] - GPU 加速
* [**js-cookie**][8-15] - cookie 的封装
* [**moment**][8-16] - 在javascript中解析，验证，操作和显示日期
* [**lazy.js**][8-17] - 像 underscore.js 的工具库
* [**licia**][8-18]
* [**underscore.js**][8-19]
* [**rgbaster.js**][8-20] - 图片的主色次色提取
* [**nanoid**][8-21] - 一款非常小巧的唯一 ID 生成工具
* [**hotkeys**][8-22] - 键盘按键的封装，如 ctrl+r
* [**JsBarcode**][8-23] - js 生成条形码(条码)
* [**comlink**][8-24] - 让 WebWorker 更好用
* [**await-timeout**][8-25] - Timeout 依托 Promise 的封装
* [**dsa.js**][8-26] - 数据结构及方法
* [**copy-to-clipboard**][8-27] - 复制的插件
* [**tesseract.js**][8-28] - 图片的文字识别工具
* [**svg.js**][8-29] - SVG 动画
* [**html2canvas**][8-30] - HTML 排版，用 canvas 截图
* [**shepherd**][8-31] - 引导您的用户浏览您的应用
* [**intro.js**][8-32] - 为您的网站和项目提供新功能介绍和逐步用户指南的更好方式可用于新手指引，功能介绍，更新指引等
* [**crypto-js**][8-33] - 加密标准的JavaScript库
* [**ulid**][8-34] - 生成UUID类库
* [**RSA**][8-35] - 用 RSA 加密实现 Web 数据加密传输
* [**detector**][8-36] - 客户端环境识别
* [**ua-parser-js**][8-37] - 客户端环境识别， userAgent
* [**platform.js**][8-38] - 平台检测库
* [**qrious**][8-39] - 用于使用 Canvas 生成二维码
* [**qart.js**][8-40] - 生成艺术二维码
* [**QRCode.js**][8-41] - QRCode.js 是用于制作 QRCode 的 JavaScript 库
* [**mousetrap**][8-42] - 用于处理键盘快捷键的简单的 JavaScript 库
* [**async**][8-43] - Async 在 NodeJS 和浏览器的实现
* [**color**][8-44] - JavaScript 颜色转换和操作库

[⬆️ 返回首页](#目录)

## 数据流

* [**redux**][9-1]
* [**immer**][9-2]
* [**mobx**][9-3]
* [**unstated**][9-4]
* [**rxjs**][9-5]
* [**dva**][9-6] - 基于 redux。
* [**rematch**][9-7] - 基于 redux
* [**vuex**][9-8]
* [**ngrx**][9-9]

## 语言

* [**TypeScript**][10-1]
* [**Flow**][10-2]
* [**Graphql**][10-3]

## 文档

* [**vuepress**][11-1]
* [**docz**][11-2]
* [**storybook**][11-3]
* [**mdx**][11-4] - jsx + markdown

[⬆️ 返回首页](#目录)

## 工程

* [**lerna**][12-1] - monorepo 管理
* [**lerna-changelog**][12-2] - 为 lerna 项目自动生成 changelog
* [**eslint**][12-3] - JS 风格约束
* [**eslint-config-airbnb**][12-4]
* [**xo**][12-5] - 封装自 eslint
* [**prettier**][12-6] - 更主观的风格自动修改
* [**yeoman-generator**][12-7] - 脚手架工具
* [**serve**][12-8] - 本地静态服务器
* [**servor**][12-9] - 另一个静态服务器
* [**budo**][12-10] - 又一个静态服务器
* [**np**][12-11] - npm publish 辅助，自动 push、打 tag、升版本等
* [**lint-staged**][12-12] - eslint 提速，只 lint 提交的代码
* [**coveralls**][12-13] - 覆盖率
* [**husky**][12-14] - 添加 git hooks
* [**cross-env**][12-15] - 跨平台的环境变量声明
* [**projj**][12-16] - 本地 git 项目管理，支持 github 和 gitlab
* [**nvm**][12-17] - 管理 node 版本
* [**concurrently**][12-18] - 在 npm scripts 里并行执行命令
* [**@zeit/ncc**][12-19] - 打包为 npm 包为一个文件
* [**npm-check**][12-20] - 检测依赖升级情况，和 `yarn upgrade-interactive` 配合着用，主要用来检测冗余依赖
* [**cpx**][12-21] - 复制，支持 glob，并且可以 watch
* [**onchange**][12-22] - 监听文件变动然后做一些事
* [**just**][12-23] - 微软出的任务管理器
* [**tern**][12-24] - 代码分析器，为不少编辑器服务
* [**analyze-css**][12-25] - CSS选择器的复杂性和性能分析器
* [**jscodeshift**][12-26] - 源码的转换，神似通过 AST ，可用于开发 VSCode 插件，或者 Lint
* [**gitattributes**][12-27] - 有用的 `.gitattributes` 模板的集合

[⬆️ 返回首页](#目录)

## 编辑器

* [**VSCode**][13-1] - 我用这个
* [**IntelliJ IDEA**][13-2]
* [**codesandbox**][13-3]
* [**stackblitz**][13-4]

## 命令行

* [**yargs**][14-1] - 命令行入口套件
* [**yargs-parser**][14-2] - 命令行参数解析
* [**chalk**][14-3] - 输出不同颜色
* [**cheerio**][14-4] - 用类 jQuery 语法处理 HTML
* [**chokidar**][14-5] - 文件监听
* [**clipboardy**][14-6] - 复制文本到粘贴板
* [**debug**][14-7] - 打印调试信息
* [**deprecate**][14-8] - 给过期警告
* [**glob**][14-9] - 文件查找
* [**tiny-glob**][14-10] - 文件查找
* [**signale**][14-11] - 漂亮的日志打印
* [**semver**][14-12] - semver 版本处理
* [**update-notifier**][14-13] - 更新提醒
* [**rimraf**][14-14] - 删除文件
* [**depd**][14-15] - 给出 deprecated 警告
* [**execa**][14-16] - 比 child\_process 好用，返回 Promise
* [**ora**][14-17] - 控制命令行光标，显示 loading 等
* [**inquirer**][14-18] - 交互式命令接口，比如 prompt
* [**enquirer**][14-19] - 同上，更 cool 一些
* [**ajv**][14-20] - 参数校验
* [**ink**][14-21] - 用 React 处理命令行输出
* [**figures**][14-22] - ✔︎ 等特殊字符，做了 windows 兼容处理

[⬆️ 返回首页](#目录)

## 请求处理

* [**whatwg-fetch**][15-1]
* [**got**][15-2]
* [**axios**][15-3]
* [**request**][15-4]
* [**reqwest**][15-5]
* [**ajax**][15-6] - Standalone AJAX library
* [**then-request**][15-7]
* [**browser-request**][15-8]
* [**superagent**][15-9]
* [**minAjax.js**][15-10]
* [**qwest**][15-11] - 第三方的 Ajax 库
* [**whatwg-fetch**][15-12]
* [**jsonp**][15-13] - 跨域处理
* [**isomorphic-fetch**][15-14]
* [**em-jsonp**][15-15] - 跨域处理

## 富文本相关

* [**Simditor**][18-1] - 简单快速的富文本编辑器
* [**BachEditor**][18-2] - 一个有情怀的编辑器
* [**TinyMCE**][18-3]
* [**bootstrap-markdown**][18-4]
* [**marked**][18-5] - markdown解析器
* [**Markdown Plus**][18-6]
* [**Editor.md**][18-7] - 开源在线Markdown编辑器
* [**stackedit**][18-8]
* [**Redactor Text Editor**][18-9]
* [**micromarkdown.js**][18-10] - 轻量级的md解析器
* [**wangEditor**][18-11] - 支持移动端的轻量级web富文本框
* [**CKEditor**][18-12] - 可视化 HTML 编辑器
* [**Quill**][18-13] - 富文本编辑器
* [**iEditor**][18-14] - 富文本编辑器
* [**medium-editor**][18-15] - Vue.js 官方推荐支持 Vue 的编辑器
* [**slate**][18-16] - 一个完全可定制的框架，用于构建富文本编辑器
* [**tiptap**][18-17] - Vue 的编辑器

[⬆️ 返回首页](#目录)

## 持续集成

* [**CircleCI**][17-1]
* [**GitlabCi**][17-2]
* [**appveyor**][17-3] - 适用于Windows和Linux的持续集成解决方案
* [**Jenkins**][17-4] - 一个支持 PHP 的连续集成平台
* [**JoliCi**][17-5] - 一个用 PHP 编写并由 DOCKER 供电的集成客户端
* [**PHPCI**][17-6] - 一个开源的 PHP 连续集成平台
* [**SemaphoreCI**][17-7] - 开源和私人项目的集成平台
* [**Shippable**][17-8] - 一个基于 DOCKER 的开源和私有项目的连续集成平台
* [**Travis CI**][17-9] - 持续整合平台
* [**Wercker**][17-10] - 持续整合平台
* [**snyk.io**][17-11] - 前端依赖检测
* [**codecov.io**][17-12] - 测试覆盖率报告

## 在线工具

### 在线编程

* [**jsfiddle**][19-1-1] - 在线编程，生成在线预览
* [**plnkr**][19-1-2] - 在线编程，生成在线预览
* [**codepen**][19-1-3] - 在线编程，生成在线预览
* [**jsbin**][19-1-4] - 在线编程，生成在线预览
* [**astexplorer**][19-1-5] - 在线编程，可选类型，如 ast

[⬆️ 返回首页](#目录)

### 转换
* [**在线时间戳(Unix timestamp)转换工具**][19-2-1]
* [**图片转换Base64**][19-2-2]
* [**文件转换工具**][19-2-3]
* [**babeljs**][19-2-4] - 语法实时编译 

### 图标管理

* [**icomoon**][19-3-1]
* [**iconfont**][19-3-2]

### 其他在线工具

* [**正则**][19-4-1]
* [**文件对比**][19-4-2]
* [**办公软件(文档、表格、幻灯片、表单)**][19-4-3]
* [**svg**][19-4-4]
* [**markdown**][19-4-5]
* [**图片压缩**][19-4-6]
* [**流程图，思维导图、UML、网络拓扑图**][19-4-7]
* [**jsdiff**][19-4-8] - 在线对比工具
* [**transfonter**][19-4-9] - 字体文件转换成 base64 格式
* [**send**][19-4-10] - 来自 Firefox 制造商的简单私密文件共享
* [**faviator**][19-4-11] - 一个生成图标的库
* [**emoji**][19-4-12] - emoji 总览

[⬆️ 返回首页](#目录)

## 代码高亮

* [**google-code-prettify**][20-1] - 一个可嵌入的脚本，可以使HTML代码更漂亮。
* [**highlight.js**][20-2]
* [**Rainbow**][20-3]
* [**ACE**][20-4]
* [**CodeMirror**][20-5] - 浏览器内代码编辑器
* [**Crayon Syntax Highlighter**][20-6]
* [**prism**][20-7] - 轻巧，健壮，优雅的语法高亮

## 音频/视频

* [**jPlayer**][21-1] -  HTML5 Audio & Video for jQuery
* [**video.js**][21-2] - HTML5 & Flash video player
* [**Accessible HTML5 Video Player**][21-3] - PayPal 开源的 HTML5 视频播放器
* [**Clappr**][21-4] - 开源的Web视频播放器
* [**Plyr**][21-5] - A simple HTML5 media player
* [**FitVids.js**][21-6] - A lightweight, easy-to-use jQuery plugin for fluid width video embeds
* [**BigVideo.js**][21-7] - The jQuery Plugin for Big Background Video
* [**BigScreen**][21-8] - A simple library for using the JavaScript Full Screen API
* [**Vide**][21-9] - 视频背景
* [**winamp2-js**][21-10]
* [**Buzz**][21-11] - A Javascript HTML5 Audio library
* [**MediaElement.js**][21-12] - 播放器 jquery 插件
* [**html-canvas-video-player**][21-13] - 支持 iOS 和 Android 的播放器
* [**iphone-inline-video**][21-14] - 让视频在iPhone上内联播放（防止自动全屏显示）

[⬆️ 返回首页](#目录)

## 数据可视化库

* [**echarts**][22-1] - 它是用纯 JavaScript 编写的，基于 zrender 画布。它支持以画布、SVG(4.0+) 和 VML 的形式绘制图表。除了 PC 和移动浏览器外，ECharts 还可以与 node 上的 node-canvas 一起使用，以便进行高效的服务器端渲染（SSR）
* [**Highcharts JS**][22-2] - 是一个广受欢迎的基于 SVG 的 JavaScript 图表库，针对旧的浏览器可降级到 VML 和画布。世界上最大的 100 家公司中，有 72 家公司（Facebook、Twitter 等）使用了这个库，这使得它成为世界上最流行的 JS 图表 API
* [**G2**][22-3]
* [**F2**][22-4] - 移动端可视化图表
* [**D3**][22-5] - 可能是最流行和使用最广泛的 JavaScript 数据可视化库。D3 用于基于数据的文档操作，并使用 HTML、SVG 和 CSS 让数据活起来。它基于 Web 标准，结合现代浏览器，不需要与专有框架耦合，将可视化组件和数据驱动的方法结合到 DOM 操作上。它允许你将任意数据绑定到文档对象模型（DOM），然后在文档上应用数据转换
* [**Chart.js**][22-6] - 一个非常受欢迎的开源 HTML5 图表库，它使用画布元素构建响应式 Web 应用。ChartJS 提供了混合图表类型，新的图表轴类型和漂亮的动画。它的设计简单而优雅，有 8 种基本的图表类型，你可以将该库与 moment.js 结合在一起使用，用于渲染时间轴
* [**three.js**][22-7] - ThreeJS 用 WebGL 创建 3D 动画。该项目的灵活性和抽象性意味着它也可用于 2 维或 3 维的数据可视化
* [**Metric-Graphics**][22-8] - 用于可视化和布局时间序列数据。它相对较小（80kb），提供了小而优雅的线条图、散点图、直方图、柱状图和数据表，以及地格图（rug plot）和基本线性回归等特性
* [**Recharts**][22-9] - 是一个使用 React 和 D3 构建的图表库，可以作为声明性的 React 组件使用。该库提供原生 SVG 支持，轻量级依赖树（D3 子模块）高度可定制。官网文档中可以找到很多例子
* [**Raphael**][22-10] - 是一个 JavaScript 矢量库，可在 Web 中绘制矢量图形。该库使用 SVG W3C 和 VML 作为创建图形的基础，因此每个图形对象也是 DOM 对象，你可以附加 JavaScript 事件处理程序。Raphael 目前支持 Firefox 3.0+、Safari 3.0+、Chrome 5.0+、Opera 9.5+ 和 Internet Explorer 6.0+
* [**C3**][22-11] - 是一个基于 D3 的可重用 Web 应用图表库。该库为每个元素提供了相应的类，这样你就可以通过这些类来自定义样式，并通过 D3 直接扩展结构。它还提供了多种 API 和回调来访问图表状态。借助它们，你可以更新图表，即使是已经渲染好的图标
* [**React-vis**][22-12] - 是 Uber 开发的一系列数据可视化组件，包括线 / 面 / 柱状图、热图、散热图、等高线图、六角热图等等。使用该库不需要事先掌握 D3 或任何其他 data-vis 库的知识，并提供了低级模块化的构建块组件，如 x/y 轴
* [**React virtualized**][22-13] - 是一组 React 组件，有效地呈现大型列表和表格数据。ES6、CommonJS 和 UMD 版本可以在每个分发版中使用，该项目支持 Webpack 4 工作流。请注意，为了避免版本冲突，必须将 react，react-dom 指定为 peer 依赖
* [**Victory**][22-14] - 在 Web 和 React Native 应用程序中使用相同的 API，以便于跨平台绘制图表。一种优雅而灵活的方式来利用 React 组件来支持实用的数据可视化
* [**CartoDB**][22-15] - 是一个位置智能和数据可视化工具，用于发现位置数据中的见解。你可以通过 Web 表单上传地理空间数据（Shapefiles、GeoJSON 等），并在数据集或地图上将其可视化，使用 SQL 进行搜索，并使用 CartoCSS 来应用地图样式
* [**Raw**][22-16] - 是电子表格和数据可视化之间的连接，基于 d3.js 库创建基于向量的自定义可视化。它可以处理表格数据（电子表格和 CSV）和从其他应用程序复制和粘贴的文本。因为是 SVG 格式，所以可以使用矢量图形编辑器编辑，或直接嵌入到网页中
* [**Metabase**][22-17] - 是一种相当快速和简单的方法，可以在不了解 SQL 的情况下创建数据仪表盘（分析师和数据专业人士可使用 SQL 模式）。你可以创建片段和度量指标，发送数据到 Slack（通过 MetaBot 在 Slack 中查看数据）等等。它可能是一个很好的工具，可用它在团队内部可视化数据，尽管可能需要做一些维护工作
* [**tauCharts**][22-18] - 一个基于 D3 的图表库。该库提供了一个声明接口，用于将数据字段快速映射到可视化属性，它的架构允许你使用插件构建切面和扩展图表行为
* [**chartist-js**][22-19] - 简单的响应式图表
* [**semiotic**][22-20] - 结合了 React 和 D3 的数据可视化框架
* [**nvd3**][22-21] - 一个用 D3.js 编写的可重用的图表库
* [**viser**][22-22] - 一个适合数据工程师的工具箱
* [**tui.chart**][22-23] - 漂亮的数据可视化图表
* [**datamaps**][22-24] - 使用 D3.js 在单个 JavaScript 件中自定义 SVG 地图可视化
* [**sheetsee.js**][22-25] - 用于对谷歌表格的数据进行可视化
* [**BizCharts**][22-26] - 基于 G2 和 React 的数据可视化库
* [**sigma.js**][22-27] - 一个专门用于图形绘制的 JavaScript 库
* [**incubator-echarts**][22-28] - 一个强大的、交互式的图表和可视化的浏览器库
* [**vis**][22-29] - 一个动态的基于浏览器的可视化库

[⬆️ 返回首页](#目录)

## 动画库

* [**velocity**][23-1]
* [**GreenSock-JS**][23-2]
* [**tween.js**][23-3]
* [**anime**][23-4]
* [**animate.css**][23-5] - A cross-browser library of CSS animations
* [**Transit**][23-6] - CSS transitions and transformations for jQuery
* [**WOW**][23-7] - 在滚动过程中展示CSS效果(默认触发animate.css)
* [**AniJS**][23-8] - A Library to Raise your Web Design without Coding
* [**Move.js**][23-9] - 简化CSS3的JS库
* [**ScrollMe**][23-10] – 在网页中加入各种滚动效果
* [**Effeckt.css**][23-11] - A Performant Transitions and Animations Library
* [**NEC**][23-12]
* [**csshake**][23-13] - CSS classes to move your DOM
* [**magic**][23-14] - CSS3 Animations with special effects
* [**SpinKit**][23-15]
* [**lenticular.js**][23-16] - 响应倾斜或鼠标事件创建图片
* [**interactive_3d**][23-17] - jQuery Interactive 3D - Create a 3D interactive object using images
* [**AnimateScroll**][23-18] - A Simple jQuery Plugin for Animating Scroll
* [**Blast.js**][23-19]
* [**Bounce.js**][23-20] - A JS library for making beautiful CSS3 keyframe animations
* [**Sticker.js**][23-21] - create a Sticker Effect
* [**scrollReveal.js**][23-22] - The element enters the visible area and automatically triggers the set animation
* [**stroll.js**][23-23] - CSS3 list scroll effects
* [**jQuery Easing**][23-24] -  运动方式扩展
* [**animations**][23-25] - CSS3 ANIMATION CHEAT SHEET
* [**iconate.js**][23-26] - 将 icons 增加运动效果的 JS 库
* [**Odometer**][23-27] - 数字之间的垂直切换
* [**Hover.css**][23-28] - 很多鼠标Hover态的效果
* [**imagehover.css**][23-29] - 为图片添加悬停效果
* [**iHover**][23-30] - 图片悬停效果
* [**ImageCaptionHoverAnimation**][23-31]
* [**Bootstrap Hover Image Gallery**][23-32]
* [**AlloyFinger**][23-33] - 腾讯 AlloyTeam 出品的超级小的 Web 手势库
* [**SpinKit**][23-34] - CSS Loading 动画的集合

[⬆️ 返回首页](#目录)

## 数据模拟

* [**mockjs**][24-1]
* [**easy-mock**][24-2]
* [**json-generator**][24-3]
* [**json-server**][24-4]

## 调试工具

* [**eruda**][25-1]
* [**vConsole**][25-2]
* [**vue-pretty-logger**][25-3] - 一个还在持续更新的本地 log 输出插件
* [**signale**][25-4] - Hackable console logger

## 源码分析

* [**vue-analysis**][26-1] - vue 2.x 源码分析
* [**vue-design**][26-2] - vue 2.x 源码分析


## 其他

* [**yazl**][16-1] - zip 压缩
* [**yauzl**][16-2] - zip 解压缩
* [**tar-fs**][16-3] - tar 的压缩和解压缩
* [**esquery**][16-4] - 语法树查询
* [**remark**][16-5] - Markdown 语法解析器
* [**markdown-it**][16-6] - Markdown 转 HTML
* [**electron**][16-7]
* [**DeskGap**][16-8] - 类 electron ，由于不包含浏览器的部分，所以产物更小
* [**fx**][16-9] - 交互式 JSON 查看
* [**fontawesome**][16-10] - 字体资源
* [**xray**][16-11] - 安全评估工具

[⬆️ 返回首页](#目录)

[1-1]:	https://github.com/webpack/webpack
[1-2]:	https://github.com/rollup/rollup
[1-3]:	https://github.com/parcel-bundler/parcel
[1-4]:	https://github.com/pikapkg/pack
[1-5]:	https://github.com/systemjs/systemjs
[1-6]:	https://github.com/developit/microbundle
[1-7]:	https://github.com/egoist/bili
[1-8]:	https://github.com/webpack/webpack-dev-server
[1-9]:	https://github.com/webpack/webpack-dev-middleware
[1-10]:	https://github.com/vuejs/vue-cli
[1-11]:	https://github.com/facebook/create-react-app
[1-12]:	https://github.com/survivejs/webpack-merge
[1-13]:	https://github.com/neutrinojs/webpack-chain
[1-14]:	https://github.com/facebook/prepack
[1-15]:	https://github.com/swc-project/swc
[1-16]:	https://github.com/nathan/pax
[1-17]:	https://github.com/pikapkg/web
[1-18]:	https://github.com/lebab/lebab
[1-19]:	https://github.com/palmerhq/tsdx

[2-1]:	https://github.com/mzgoddard/hard-source-webpack-plugin
[2-2]:	https://github.com/smooth-code/svgr
[2-3]:	https://github.com/postcss/postcss
[2-4]:	https://github.com/postcss/autoprefixer
[2-5]:	https://github.com/cssnano/cssnano
[2-6]:	https://github.com/webpack-contrib/mini-css-extract-plugin
[2-7]:	https://github.com/nuxt/webpackbar
[2-8]:	https://github.com/webpack-contrib/webpack-bundle-analyzer
[2-9]:	https://github.com/webpack-contrib/uglifyjs-webpack-plugin
[2-10]:	https://github.com/webpack-contrib/terser-webpack-plugin
[2-11]:	https://github.com/danethurber/webpack-manifest-plugin
[2-12]:	https://github.com/webpack-contrib/copy-webpack-plugin
[2-13]:	https://github.com/Urthen/case-sensitive-paths-webpack-plugin
[2-14]:	https://github.com/shepherdwind/css-hot-loader
[2-15]:	https://github.com/darrenscerri/duplicate-package-checker-webpack-plugin
[2-16]:	https://github.com/Realytics/fork-ts-checker-webpack-plugin
[2-17]:	https://github.com/stephencookdev/speed-measure-webpack-plugin

[3-1]:	https://github.com/yarnpkg/yarn
[3-2]:	https://github.com/npm/cli
[3-3]:	https://bower.io

[4-1-1]:	https://github.com/cocos2d/cocos2d-html5
[4-1-2]:	http://www.egret-labs.org/
[4-1-3]:	https://github.com/digitalfruit/limejs
[4-1-4]:	https://github.com/CreateJS/EaselJS
[4-1-5]:	https://github.com/mrdoob/three.js
[4-1-6]:	https://github.com/AlloyTeam/AlloyStick
[4-1-7]:	https://github.com/finscn/The-Best-JS-Game-Framework
[4-1-8]:	https://github.com/RSamaium/CanvasEngine
[4-1-9]:	https://github.com/cykod/Quintus
[4-1-10]:	https://github.com/piqnt/stage.js/
[4-1-11]:	https://github.com/photonstorm/phaser
[4-1-12]:	https://github.com/lufylegend/lufylegend.js
[4-1-13]:	https://github.com/pixijs/pixi.js

[4-2-1]:	https://github.com/apache/incubator-weex
[4-2-2]:	https://github.com/facebook/react-native
[4-2-3]:	https://github.com/dcloudio/mui
[4-2-4]:	https://github.com/jaunesarmiento/fries
[4-2-5]:	https://github.com/flutter/flutter

[4-3-1]:	https://github.com/twbs/bootstrap
[4-3-2]:	https://github.com/uikit/uikit
[4-3-3]:	http://www.idangero.us/framework7
[4-3-4]:	http://ionicframework.com/
[4-3-5]:	http://jquerymobile.com/
[4-3-6]:	https://github.com/sentsin/layui/
[4-3-7]:	https://github.com/topcoat/topcoat

[4-4-1]:	https://github.com/Meituan-Dianping/mpvue
[4-4-2]:	https://github.com/Tencent/wepy
[4-4-3]:	https://github.com/Tencent/westore
[4-4-4]:	https://github.com/weilanwl/ColorUI
[4-4-5]:	https://github.com/huangjianke/Gitter
[4-4-6]:	https://github.com/NervJS/taro

[4-5-1]:	https://github.com/facebook/react
[4-5-2]:	https://github.com/vuejs/vue
[4-5-3]:	https://github.com/zeit/next.js
[4-5-4]:	https://github.com/nuxt/nuxt.js
[4-5-5]:	https://github.com/gatsbyjs/gatsby
[4-5-6]:	https://github.com/umijs/umi
[4-5-7]:	https://github.com/rekit/rekit
[4-5-8]:	https://github.com/choojs/choo
[4-5-10]:	https://github.com/jaredpalmer/after.js
[4-5-11]:	https://github.com/mint-lang/mint
[4-5-12]:	https://github.com/quasarframework/quasar
[4-5-13]:	https://github.com/angular/angular
[4-5-14]:	https://github.com/zurb/foundation
[4-5-15]:	https://www.polymer-project.org
[4-5-16]:	https://github.com/cyclejs/cyclejs/

[5-1]:	https://github.com/developit/preact
[5-2]:	https://github.com/infernojs/inferno
[5-3]:	https://github.com/ReactTraining/react-router
[5-4]:	https://github.com/reach/router
[5-5]:	https://github.com/router5/router5
[5-6]:	https://github.com/jamiebuilds/react-loadable
[5-7]:	https://github.com/mui-org/material-ui
[5-8]:	https://github.com/yahoo/react-intl
[5-9]:	https://github.com/react-dnd/react-dnd
[5-10]:	https://github.com/nfl/react-helmet
[5-11]:	https://github.com/mozilla-services/react-jsonschema-form
[5-12]:	https://github.com/airbnb/react-dates
[5-13]:	https://github.com/system-ui/theme-ui

[6-1-1]:	https://github.com/quasarframework/quasar
[6-1-2]:	https://github.com/vuematerial/vue-material
[6-1-3]:	https://github.com/vuetifyjs/vuetify
[6-1-4]:	https://github.com/museui/muse-ui
[6-1-5]:	https://github.com/rafaelpimpa/buefy
[6-1-6]:	https://github.com/ElemeFE/element
[6-1-7]:	https://vulma.org
[6-1-8]:	https://github.com/vouill/vue-bulma-components
[6-1-9]:	https://www.iviewui.com
[6-1-10]:	https://at.aotu.io
[6-1-11]:	https://www.npmjs.com/package/v-semantic
[6-1-12]:	https://bootstrap-vue.github.io
[6-1-13]:	https://myliang.github.io/fish-ui
[6-1-14]:	https://zircleui.github.io/zircleUI/
[6-1-15]:	https://github.com/stasson/vue-mdc-adapter
[6-1-16]:	https://github.com/matsp/material-components-vue
[6-1-17]:	https://github.com/primefaces/primevue
[6-1-18]:	https://github.com/lusaxweb/vuesax
[6-1-19]:	https://bitbucket.org/acidmartin/vuecidity
[6-1-20]:	https://github.com/fe6/water
[6-1-21]:	https://github.com/youzan/vant

[6-2-1]:	https://github.com/vuejs/vue-router
[6-2-2]:	https://github.com/xyxiao001/vue-cropper
[6-2-3]:	https://github.com/TaroXin/vue-pretty-logger
[6-2-4]:	https://github.com/fe6/vue-icon
[6-2-5]:	https://github.com/Dafrok/vue-baidu-map
[6-2-6]:	https://github.com/SortableJS/Vue.Draggable
[6-2-7]:	https://github.com/surmon-china/vue-codemirror
[6-2-8]:	https://github.com/Akryum/vue-apollo
[6-2-9]:	https://github.com/zulko/eagle.js
[6-2-10]:	https://github.com/xiaokaike/vue-color
[6-2-11]:	https://github.com/zenghao0219/seat-select
[6-2-12]:	https://github.com/zenghao0219/seat-select-controller
[6-2-13]:	https://github.com/staven630/vue-cli3-config
[6-2-14]:	https://github.com/flatlogic/sing-app-vue-dashboard
[6-2-15]:	https://github.com/DivanteLtd/vue-storefront
[6-2-16]:	https://github.com/Akryum/vue-virtual-scroller
[6-2-17]:	https://github.com/nathanreyes/v-calendar
[6-2-18]:	https://github.com/viljamis/vue-design-system
[6-2-19]:	https://github.com/flatlogic/light-blue-vue-admin
[6-2-20]:	https://github.com/jbaysolutions/vue-grid-layout
[6-2-21]:	https://github.com/egoist/vue-content-loader
[6-2-22]:	https://github.com/euvl/vue-js-modal
[6-2-23]:	https://github.com/asika32764/vue2-animate
[6-2-24]:	https://github.com/stegosource/vuetensils
[6-2-25]:	https://github.com/easy-team/easyjs

[7-1]:	https://github.com/ant-design/ant-design
[7-2]:	https://github.com/antvis
[7-3]:	https://github.com/ant-design/ant-motion
[7-4]:	https://github.com/umijs/hooks
[7-5]:	https://github.com/umijs/qiankun

[8-1]:	https://github.com/ReactTraining/history
[8-2]:	https://github.com/pillarjs/path-to-regexp
[8-3]:	https://github.com/lodash/lodash
[8-4]:	https://github.com/ftlabs/fastclick
[8-5]:	https://github.com/date-fns/date-fns
[8-6]:	https://github.com/facebook/immutable-js
[8-7]:	https://github.com/bendc/sprint
[8-8]:	https://github.com/xx45/dayjs
[8-9]:	https://github.com/taylorhakes/fecha
[8-10]:	https://github.com/nhnent/tui.calendar
[8-11]:	https://github.com/em-fe/em-cookie
[8-12]:	https://github.com/em-fe/EM-NORMALIZE
[8-13]:	https://github.com/modernizr/modernizr
[8-14]:	https://github.com/gpujs/gpu.js
[8-15]:	https://github.com/js-cookie/js-cookie
[8-16]:	https://github.com/moment/moment
[8-17]:	https://github.com/dtao/lazy.js
[8-18]:	https://github.com/liriliri/licia
[8-19]:	https://github.com/jashkenas/underscore
[8-20]:	https://github.com/briangonzalez/rgbaster.js
[8-21]:	https://github.com/ai/nanoid
[8-22]:	https://github.com/jaywcjlove/hotkeys
[8-23]:	https://github.com/lindell/JsBarcode
[8-24]:	https://github.com/GoogleChromeLabs/comlink
[8-25]:	https://github.com/vitalets/await-timeout
[8-26]:	https://github.com/amejiarosario/dsa.js
[8-27]:	https://github.com/sudodoki/copy-to-clipboard
[8-28]:	https://github.com/naptha/tesseract.js
[8-29]:	https://github.com/svgdotjs/svg.js
[8-30]:	https://github.com/niklasvh/html2canvas
[8-31]:	https://github.com/shipshapecode/shepherd
[8-32]:	https://github.com/usablica/intro.js
[8-33]:	https://github.com/brix/crypto-js
[8-34]:	https://github.com/alizain/ulid
[8-35]:	http://www.ohdave.com/rsa/
[8-36]:	https://github.com/hotoo/detector
[8-37]:	https://github.com/faisalman/ua-parser-js
[8-38]:	https://github.com/bestiejs/platform.js
[8-39]:	https://github.com/neocotic/qrious
[8-40]:	https://github.com/kciter/qart.js
[8-41]:	https://github.com/davidshimjs/qrcodejs
[8-42]:	https://github.com/ccampbell/mousetrap
[8-43]:	https://github.com/caolan/async
[8-44]:	https://github.com/Qix-/color

[9-1]:	https://github.com/reduxjs/redux
[9-2]:	https://github.com/mweststrate/immer
[9-3]:	https://github.com/mobxjs/mobx
[9-4]:	https://github.com/jamiebuilds/unstated
[9-5]:	https://github.com/ReactiveX/rxjs
[9-6]:	https://github.com/dvajs/dva
[9-7]:	https://github.com/rematch/rematch
[9-8]:	https://github.com/vuejs/vuex
[9-9]:	https://github.com/ngrx/platform

[10-1]:	https://github.com/Microsoft/TypeScript
[10-2]:	https://github.com/facebook/flow
[10-3]:	https://github.com/graphql/graphql-js

[11-1]:	https://github.com/vuejs/vuepress
[11-2]:	https://github.com/pedronauck/docz
[11-3]:	https://github.com/storybooks/storybook
[11-4]:	https://github.com/mdx-js/mdx

[12-1]:	https://github.com/lerna/lerna
[12-2]:	https://github.com/lerna/lerna-changelog
[12-3]:	https://github.com/eslint/eslint
[12-4]:	https://github.com/airbnb/javascript
[12-5]:	https://github.com/xojs/xo
[12-6]:	https://github.com/prettier/prettier
[12-7]:	https://github.com/yeoman/generator
[12-8]:	https://github.com/zeit/serve
[12-9]:	https://github.com/lukejacksonn/servor
[12-10]:	https://github.com/mattdesl/budo
[12-11]:	https://github.com/sindresorhus/np
[12-12]:	https://github.com/okonet/lint-staged
[12-13]:	https://github.com/marketplace/coveralls
[12-14]:	https://github.com/typicode/husky
[12-15]:	https://github.com/kentcdodds/cross-env
[12-16]:	https://github.com/popomore/projj
[12-17]:	https://github.com/creationix/nvm
[12-18]:	https://github.com/kimmobrunfeldt/concurrently
[12-19]:	https://github.com/zeit/ncc
[12-20]:	https://github.com/dylang/npm-check
[12-21]:	https://github.com/mysticatea/cpx
[12-22]:	https://github.com/Qard/onchange
[12-23]:	https://github.com/Microsoft/just
[12-24]:	https://github.com/ternjs/tern
[12-25]:	https://github.com/macbre/analyze-css
[12-26]:	https://github.com/facebook/jscodeshift
[12-27]:	https://github.com/alexkaratarakis/gitattributes

[13-1]:	https://code.visualstudio.com/
[13-2]:	https://www.jetbrains.com/idea/
[13-3]:	https://codesandbox.io/
[13-4]:	https://stackblitz.com/

[14-1]:	https://github.com/yargs/yargs
[14-2]:	https://github.com/yargs/yargs-parser
[14-3]:	https://github.com/chalk/chalk
[14-4]:	https://github.com/cheeriojs/cheerio
[14-5]:	https://github.com/paulmillr/chokidar
[14-6]:	https://github.com/sindresorhus/clipboardy
[14-7]:	https://github.com/visionmedia/debug
[14-8]:	https://github.com/brianc/node-deprecate
[14-9]:	https://github.com/isaacs/node-glob
[14-10]:	https://github.com/terkelg/tiny-glob
[14-11]:	https://github.com/klaussinani/signale
[14-12]:	https://github.com/npm/node-semver
[14-13]:	https://github.com/yeoman/update-notifier
[14-14]:	https://github.com/isaacs/rimraf
[14-15]:	https://github.com/dougwilson/nodejs-depd
[14-16]:	https://github.com/sindresorhus/execa
[14-17]:	https://github.com/sindresorhus/ora
[14-18]:	https://github.com/SBoudrias/Inquirer.js
[14-19]:	https://github.com/enquirer/enquirer
[14-20]:	https://github.com/epoberezkin/ajv
[14-21]:	https://github.com/vadimdemedes/ink
[14-22]:	https://github.com/sindresorhus/figures

[15-1]:	https://github.com/github/fetch
[15-2]:	https://github.com/sindresorhus/got
[15-3]:	https://github.com/axios/axios
[15-4]:	https://github.com/request/request
[15-5]:	https://github.com/ded/reqwest
[15-6]:	https://github.com/ForbesLindesay/ajax
[15-7]:	https://github.com/then/then-request
[15-8]:	https://github.com/iriscouch/browser-request
[15-9]:	https://github.com/visionmedia/superagent
[15-10]:	https://github.com/argunner/minAjax.js
[15-11]:	https://github.com/pyrsmk/qwest
[15-12]:	https://github.com/fis-components/whatwg-fetch
[15-13]:	https://github.com/webmodules/jsonp
[15-14]:	https://github.com/matthew-andrews/isomorphic-fetch
[15-15]:	https://github.com/em-fe/em-jsonp

[16-1]:	https://www.npmjs.com/package/yazl
[16-2]:	https://github.com/thejoshwolfe/yauzl
[16-3]:	https://github.com/mafintosh/tar-fs
[16-4]:	https://github.com/estools/esquery
[16-5]:	https://github.com/remarkjs/remark
[16-6]:	https://github.com/markdown-it/markdown-it
[16-7]:	https://github.com/electron/electron
[16-8]:	https://github.com/patr0nus/DeskGap
[16-9]:	https://github.com/antonmedv/fx
[16-10]:	https://fontawesome.com
[16-11]:	https://github.com/chaitin/xray

[17-1]:	https://circleci.com
[17-2]:	https://about.gitlab.com/gitlab-ci/
[17-3]:	https://www.appveyor.com/
[17-4]:	https://jenkins.io/index.html
[17-5]:	https://github.com/jolicode/JoliCi
[17-6]:	https://www.phptesting.org/
[17-7]:	https://semaphoreci.com/
[17-8]:	https://www.shippable.com/
[17-9]:	https://travis-ci.org/
[17-10]:	http://www.wercker.com/
[17-11]:	https://snyk.io
[17-12]:	https://codecov.io

[18-1]:	https://github.com/mycolorway/simditor
[18-2]:	https://github.com/Integ/BachEditor
[18-3]:	https://github.com/tinymce/tinymce
[18-4]:	https://github.com/toopay/bootstrap-markdown
[18-5]:	https://github.com/chjj/marked
[18-6]:	https://github.com/tylingsoft/markdown-plus
[18-7]:	https://github.com/pandao/editor.md
[18-8]:	https://github.com/benweet/stackedit
[18-9]:	http://imperavi.com/redactor/
[18-10]:	https://github.com/simonwaldherr/micromarkdown.js/
[18-11]:	https://github.com/wangfupeng1988/wangEditor
[18-12]:	https://github.com/ckeditor/ckeditor-dev
[18-13]:	https://github.com/quilljs/quill
[18-14]:	https://github.com/iq9891/ieditor
[18-15]:	https://github.com/yabwe/medium-editor
[18-16]:	https://github.com/ianstormtaylor/slate
[18-17]:	https://github.com/heyscrumpy/tiptap

[19-1-1]:	https://jsfiddle.net/
[19-1-2]:	http://plnkr.co
[19-1-3]:	https://codepen.io/
[19-1-4]:	http://jsbin.com
[19-1-5]:	https://astexplorer.net/

[19-2-1]:	http://www.atool.org/timestamp.php
[19-2-2]:	http://imgbase64.duoshitong.com/
[19-2-3]:	https://cloudconvert.com/
[19-2-4]:	https://babeljs.io/repl/#?babili=false&evaluate=true&lineWrap=false&presets=es2015%2Creact%2Cstage-2&targets=&browsers=&builtIns=false&code=

[19-3-1]:	https://icomoon.io
[19-3-2]:	http://www.iconfont.cn

[19-4-1]:	https://regexper.com/
[19-4-2]:	http://prettydiff.com/
[19-4-3]:	https://www.google.com/docs/about
[19-4-4]:	http://editor.method.ac
[19-4-5]:	https://dillinger.io
[19-4-6]:	https://tinypng.com
[19-4-7]:	https://www.processon.com/
[19-4-8]:	http://incaseofstairs.com/jsdiff
[19-4-9]:	https://transfonter.org/
[19-4-10]:	https://github.com/mozilla/send
[19-4-11]:	https://github.com/faviator/faviator
[19-4-12]:	https://github.com/muan/emoji

[20-1]:	https://github.com/google/code-prettify
[20-2]:	https://highlightjs.org/
[20-3]:	http://craig.is/making/rainbows
[20-4]:	https://github.com/ajaxorg/ace
[20-5]:	https://github.com/codemirror/codemirror
[20-6]:	https://github.com/aramk/crayon-syntax-highlighter
[20-7]:	https://github.com/PrismJS/prism

[21-1]:	https://github.com/happyworm/jPlayer
[21-2]:	https://github.com/videojs/video.js
[21-3]:	https://github.com/paypal/accessible-html5-video-player
[21-4]:	https://github.com/clappr/clappr
[21-5]:	https://github.com/selz/plyr
[21-6]:	https://github.com/davatron5000/FitVids.js
[21-7]:	https://github.com/dfcb/BigVideo.js
[21-8]:	https://github.com/bdougherty/BigScreen
[21-9]:	https://github.com/VodkaBears/Vide
[21-10]:	https://github.com/captbaritone/winamp2-js
[21-11]:	https://github.com/jaysalvat/buzz
[21-12]:	https://github.com/mediaelement/mediaelement
[21-13]:	https://github.com/Stanko/html-canvas-video-player
[21-14]:	https://github.com/bfred-it/iphone-inline-video

[22-1]:	https://github.com/apache/incubator-echarts
[22-2]:	https://github.com/highcharts/highcharts
[22-3]:	https://github.com/antvis/g2
[22-4]:	https://github.com/antvis/f2
[22-5]:	https://github.com/d3/d3
[22-6]:	https://github.com/chartjs/Chart.js
[22-7]:	https://github.com/mrdoob/three.js/
[22-8]:	https://github.com/metricsgraphics/metrics-graphics
[22-9]:	https://github.com/recharts/recharts
[22-10]:	https://github.com/DmitryBaranovskiy/raphael
[22-11]:	https://github.com/c3js/c3
[22-12]:	https://github.com/uber/react-vis
[22-13]:	https://github.com/bvaughn/react-virtualized
[22-14]:	https://github.com/FormidableLabs/victory
[22-15]:	https://github.com/CartoDB/cartodb
[22-16]:	https://github.com/densitydesign/raw
[22-17]:	https://github.com/metabase/metabase
[22-18]:	https://github.com/TargetProcess/tauCharts
[22-19]:	https://github.com/gionkunz/chartist-js
[22-20]:	https://github.com/emeeks/semiotic
[22-21]:	https://github.com/novus/nvd3
[22-22]:	https://github.com/viserjs/viser
[22-23]:	https://github.com/nhnent/tui.chart
[22-24]:	https://github.com/markmarkoh/datamaps
[22-25]:	https://github.com/jlord/sheetsee.js
[22-26]:	https://github.com/alibaba/BizCharts
[22-27]:	https://github.com/jacomyal/sigma.js
[22-28]:	https://github.com/apache/incubator-echarts
[22-29]:	https://github.com/almende/vis

[23-1]:	https://github.com/julianshapiro/velocity
[23-2]:	https://github.com/greensock/GreenSock-JS/
[23-3]:	https://github.com/tweenjs/tween.js
[23-4]:	https://github.com/juliangarnier/anime
[23-5]:	https://github.com/daneden/animate.css
[23-6]:	https://github.com/rstacruz/jquery.transit
[23-7]:	https://github.com/matthieua/WOW
[23-8]:	https://github.com/anijs/anijs/
[23-9]:	https://github.com/visionmedia/move.js
[23-10]:	https://github.com/nckprsn/scrollme
[23-11]:	https://github.com/h5bp/Effeckt.css
[23-12]:	http://nec.netease.com/library/category/#animation
[23-13]:	https://github.com/elrumordelaluz/csshake
[23-14]:	https://github.com/miniMAC/magic
[23-15]:	https://github.com/tobiasahlin/SpinKit
[23-16]:	https://github.com/thomasxiii/lenticular.js
[23-17]:	https://github.com/peachananr/interactive_3d
[23-18]:	https://github.com/ramswaroop/animatescroll.js
[23-19]:	https://github.com/julianshapiro/blast
[23-20]:	https://github.com/tictail/bounce.js
[23-21]:	https://github.com/cmiscm/stickerjs
[23-22]:	https://github.com/julianlloyd/scrollReveal.js
[23-23]:	https://github.com/hakimel/stroll.js
[23-24]:	https://github.com/gdsmith/jquery.easing
[23-25]:	http://www.justinaguilar.com/animations/index.html
[23-26]:	https://github.com/bitshadow/iconate
[23-27]:	https://github.com/HubSpot/odometer
[23-28]:	https://github.com/IanLunn/Hover
[23-29]:	https://github.com/ciar4n/imagehover.css
[23-30]:	https://github.com/gudh/ihover
[23-31]:	https://github.com/hasinhayder/ImageCaptionHoverAnimation
[23-32]:	http://miketricking.github.io/dist/
[23-33]:	https://github.com/AlloyTeam/AlloyFinger
[23-33]:	https://github.com/tobiasahlin/SpinKit

[24-1]:	http://mockjs.com
[24-2]:	https://www.easy-mock.com/
[24-3]:	https://www.json-generator.com/
[24-4]:	https://github.com/typicode/json-server

[25-1]:	https://github.com/liriliri/eruda
[25-2]:	https://github.com/Tencent/vConsole
[25-3]:	https://github.com/TaroXin/vue-pretty-logger
[25-4]:	https://github.com/klauscfhq/signale

[26-1]:	https://github.com/ustbhuangyi/vue-analysis
[26-2]:	https://github.com/HcySunYang/vue-design
