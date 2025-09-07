# Easy-Live
project-root/
├── package.json          # 工作区配置
├── pnpm-workspace.yaml   # 工作区定义
├── apps/
│   └── web/              # 主应用
├── packages/
│   ├──读卡器适配器/ card-reader-adapter     # 读卡器通信逻辑
│   ├──excel处理器/  excel-processor      # Excel处理工具
│   ├──共享组件/     shared-components     # 通用UI组件
│   └──类型定义/    type-definitions      # 共享TypeScript类型
└── 配置文件/   configs          # ESLint、TypeScript等配置