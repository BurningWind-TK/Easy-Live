project-root/
├── apps/                      # 应用目录（最终运行的程序）
│   ├── web/                   # 前端主应用（用户操作界面）
│   ├── desktop/               # 桌面端应用（本地硬件适配）
│   ├── server/                # 后端服务（核心逻辑处理）
│   └── admin/                 # 管理后台（权限/日志管理）
├── packages/                  # 共享依赖目录（可复用工具）
│   ├── card-reader-adapter/   # 读卡器适配器（硬件通信）
│   ├── card-data-parser/      # 读卡器数据解析（格式转换）
│   ├── excel-processor/       # Excel处理器（列增删改）
│   ├── excel-template/        # Excel模板管理（格式统一）
│   ├── shared-components/     # 共享UI组件（多应用复用）
│   ├── type-definitions/      # 类型定义（TS类型共享）
│   ├── log-service/           # 日志服务（问题排查）
│   └── permission-utils/      # 权限工具（操作控制）
├── docs/                      # 项目文档（技术/使用手册）
├── scripts/                   # 自动化脚本（部署/测试）
├── tests/                     # 测试用例（功能保障）
├── examples/                  # 示例资源（快速上手）
├── configs/                  # ESLint、TS等配置文件
├── package.json               # 工作区配置
└── pnpm-workspace.yaml        # 工作区定义