.
├── .github/workflows/      # GitHub Actions 工作流
│   ├── daily-sync.yml      # 每日增量同步（北京时间 8:00）
│   └── manual-full-sync.yml # 每周全量同步（北京时间 2:00）
├── scripts/                # 核心脚本
│   ├── api.py             # 微信读书 API 封装
│   ├── config.py          # 配置管理
│   ├── md_to_notion.py    # Markdown 转 Notion blocks
│   ├── notion_client.py   # Notion API 封装
│   ├── notion_push.py     # Notion 推送逻辑
│   ├── renderer.py        # Markdown 渲染
│   ├── sync.py            # 同步主逻辑
│   └── utils.py           # 工具函数
├── data/                   # 书籍数据（自动创建）
├── index.json             # 书籍索引（自动创建）
├── .env                   # 环境变量（需手动创建）
└── requirements.txt       # Python 依赖
