# 采购计划管理系统

## 项目说明
本项目是一个基于Vue的采购计划管理系统前端，实现了采购计划的增删改查、明细导入导出、附件上传等功能。系统严格按照需求文档进行开发，确保功能完整性和规范性。

## 技术栈
- 前端：Vue2、Element UI、Axios

## 环境要求
- Node.js 14+
- npm 6+

## 快速开始

### 1. 安装依赖
```bash
npm install
```

### 2. 启动开发服务器
```bash
npm run serve
```

## 访问地址
- 前端：http://localhost:8080

## 功能特性
- 采购计划管理（增删改查）
- 计划明细导入导出
- 附件上传下载
- 状态流转管理

## 注意事项
1. 文件上传大小限制为100MB
2. 单个计划最多上传5个附件

## 目录结构
```
procurement-plan-front/
├── .idea/           # IDE配置
├── docs/            # 文档
├── src/             # 源代码
│   ├── api/         # API请求
│   │   └── plan.js  # 采购计划相关接口
│   ├── views/       # 页面
│   │   ├── plan/    # 采购计划相关页面
│   │   │   ├── add.vue       # 新增计划
│   │   │   ├── edit.vue      # 编辑计划
│   │   │   ├── list.vue      # 计划列表
│   │   │   ├── detail.vue    # 计划详情
│   │   │   └── ImportDialog.vue # 导入对话框
│   │   ├── PlanForm.vue      # 计划表单
│   │   ├── PlanList.vue      # 计划列表
│   │   └── PlanDetail.vue    # 计划详情
│   ├── router/      # 路由
│   │   └── index.js # 路由配置
│   ├── store/       # Vuex状态管理
│   │   └── index.js # 状态管理配置
│   ├── utils/       # 工具
│   │   └── request.js # 请求工具
│   ├── styles/      # 样式
│   │   └── index.scss # 全局样式
│   ├── layout/      # 布局
│   │   ├── Header.vue # 头部
│   │   └── Sidebar.vue # 侧边栏
│   ├── App.vue      # 根组件
│   └── main.js      # 入口文件
├── public/          # 静态资源
├── node_modules/    # 依赖
├── package.json     # 项目配置
├── package-lock.json # 依赖锁定
├── vue.config.js    # Vue配置
└── README.md        # 项目说明
```

## 主要功能
- 采购计划增删改查、明细导入导出、附件上传、状态流转等。

## 其他
- 详细接口文档、后端代码、技术文档见 `docs/` 目录。
