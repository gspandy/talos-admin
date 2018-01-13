# Ant Design Pro

[![](https://img.shields.io/travis/ant-design/ant-design-pro.svg?style=flat-square)](https://travis-ci.org/ant-design/ant-design-pro) [![Build status](https://ci.appveyor.com/api/projects/status/67fxu2by3ibvqtat/branch/master?svg=true)](https://ci.appveyor.com/project/afc163/ant-design-pro/branch/master)  [![Gitter](https://badges.gitter.im/ant-design/ant-design-pro.svg)](https://gitter.im/ant-design/ant-design-pro?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge)

开箱即用的中台前端/设计解决方案。

![](https://gw.alipayobjects.com/zos/rmsportal/xEdBqwSzvoSapmnSnYjU.png)

## 特性

- :gem: **优雅美观**：基于 Ant Design 体系精心设计
- :triangular_ruler: **常见设计模式**：提炼自中后台应用的典型页面和场景
- :rocket: **最新技术栈**：使用 React/dva/antd 等前端前沿技术开发
- :iphone: **响应式**：针对不同屏幕大小设计
- :art: **主题**：可配置的主题满足多样化的品牌诉求
- :globe_with_meridians: **国际化**：内建业界通用的国际化方案
- :gear: **最佳实践**：良好的工程实践助您持续产出高质量代码
- :1234: **Mock 数据**：实用的本地数据调试方案
- :white_check_mark: **UI 测试**：自动化测试保障前端产品质量

## 模板

```
- Dashboard
  - 分析页
  - 监控页
  - 工作台
- 表单页
  - 基础表单页
  - 分步表单页
  - 高级表单页
- 列表页
  - 查询表格
  - 标准列表
  - 卡片列表
  - 搜索列表（项目/应用/文章）
- 详情页
  - 基础详情页
  - 高级详情页
- 结果
  - 成功页
  - 失败页
- 异常
  - 403 无权限
  - 404 找不到
  - 500 服务器出错
- 帐户
  - 登录
  - 注册
  - 注册成功
```
## 目录结构

我们已经为你生成了一个完整的开发框架，提供了涵盖中后台开发的各类功能和坑位，下面是整个项目的目录结构。

```bash
├── mock                     # 本地模拟数据
├── public
│   └── favicon.ico          # Favicon
├── src
│   ├── assets               # 本地静态资源
│   ├── common               # 应用公用配置，如导航信息
│   ├── components           # 业务通用组件
│   ├── e2e                  # 集成测试用例
│   ├── layouts              # 通用布局
│   ├── models               # dva model
│   ├── routes               # 业务页面入口和常用模板
│   ├── services             # 后台接口服务
│   ├── utils                # 工具库
│   ├── g2.js                # 可视化图形配置
│   ├── theme.js             # 主题配置
│   ├── index.ejs            # HTML 入口模板
│   ├── index.js             # 应用入口
│   ├── index.less           # 全局样式
│   └── router.js            # 路由入口
├── tests                    # 测试工具
├── README.md
└── package.json
```

## 使用

```bash
$ git clone https://github.com/ant-design/ant-design-pro.git --depth=1
$ cd ant-design-pro
$ npm install
$ npm start         # 访问 http://localhost:8000
```

也可以使用集成化的 [ant-design-pro-cli](https://github.com/ant-design/ant-design-pro-cli) 工具。

```bash
$ npm install ant-design-pro-cli -g
$ mkdir pro-demo && cd pro-demo
$ pro new
```
### 参考文档
https://www.cnblogs.com/eeds-wangwei/p/8116633.html
https://segmentfault.com/q/1010000012231921

