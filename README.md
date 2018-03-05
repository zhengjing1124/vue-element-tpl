<p align="center">
  <img width="320" src="https://wpimg.wallstcn.com/ecc53a42-d79b-42e2-8852-5126b810a4c8.svg">
</p>

<p align="center">
	<a href="https://github.com/vuejs/vue">
		<img src="https://img.shields.io/badge/vue-2.5.10-brightgreen.svg" alt="vue">
	</a>
	<a href="https://github.com/ElemeFE/element">
		<img src="https://img.shields.io/badge/element--ui-2.0.8-brightgreen.svg" alt="element-ui">
	</a>
	<a href="https://github.com/zhengjing1124/vue-element-tpl/blob/master/LICENSE">
		<img src="https://img.shields.io/github/license/mashape/apistatus.svg" alt="license">
	</a>
	<a href="https://github.com/zhengjing1124/vue-element-tpl/releases">
		<img src="https://img.shields.io/github/release/zhengjing1124/vue-element-tpl.svg" alt="GitHub release">
	</a>
</p>

## 简介

 本项目是一个后台集成解决方案，基于 [Vue.js](https://github.com/vuejs/vue) 和 [element](https://github.com/ElemeFE/element)。它使用了最新的前端技术栈，内置了i18国际化解决方案，动态路由，权限验证等多功能特性。

**注意：该项目使用 element-ui@2.0.0+ 版本，所以最低兼容 vue@2.5.0**

## 准备

你的本地环境需要安装 [node](http://nodejs.org/) 和 [git](https://git-scm.com/)。我们的技术栈基于 [ES2015+](http://es6.ruanyifeng.com/)、[vue](https://cn.vuejs.org/index.html)、[vuex](https://vuex.vuejs.org/zh-cn/)、[vue-router](https://router.vuejs.org/zh-cn/) and [element-ui](https://github.com/ElemeFE/element)。

 **本项目并不是一个脚手架，更倾向于是一个集成解决方案**

 **该项目不支持低版本浏览器(如ie)，有需求请自行添加polyfill [详情](https://github.com/zhengjing1124/vue-element-tpl/wiki#babel-polyfill)**

 <p align="center">
  <img width="900" src="https://wpimg.wallstcn.com/a5894c1b-f6af-456e-82df-1151da0839bf.png">
</p>

## 功能
```
- 登录/注销
- 权限验证
- 多环境发布
- 动态侧边栏（支持多级路由）
- 动态面包屑
- 国际化多语言
- 多种动态换肤
- 快捷导航(标签页)
- 富文本编辑器
- Markdown编辑器
- JSON编辑器
- Screenfull全屏
- 列表拖拽
- Svg Sprite 图标
- Dashboard
- 本地mock数据
- Echarts 图表
- Clipboard(剪贴复制)
- 401/404错误页面
- 错误日志
- 导出excel
- 导出zip
- 前端可视化excel
- 树形table
- Table example
- 动态table example
- 拖拽table example
- 内联编辑table example
- Form example
- 二步登录
- SplitPane
- Dropzone
- Sticky
- CountTo
- Markdown2html
```

## 开发
```bash
# 克隆项目
git clone https://github.com/zhengjing1124/vue-element-tpl.git

# 安装依赖
npm install
   
# 建议不要用cnpm安装 会有各种诡异的bug 可以通过如下操作解决 npm 下载速度慢的问题
npm install --registry=https://registry.npm.taobao.org

# 启动服务
npm run dev
```
浏览器访问 http://localhost:9527

## 发布
```bash
# 构建测试环境
npm run build:sit

# 构建生成环境
npm run build:prod
```

## 其它
```bash
# --report to build with bundle size analytics
npm run build:prod --report

# --preview to start a server in local to preview
npm run build:prod --preview

# lint code
npm run lint

# auto fix
npm run lint -- --fix
```

更多信息请参考 [使用文档](https://zhengjing1124.github.io/vue-element-admin-site/#/deploy)

Copyright (c) 2018-present zhengjing
