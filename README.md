# 微信小程序云开发 - 数据备份

本仓库用于存储微信小程序云开发数据库和云存储的本地备份文件。

## 备份结构

```
backup_YYYY-MM-DDTHH-mm-ss/
── database.json          # 数据库导出
├── report.json            # 备份报告
└── works/                 # 作品图片
    └── 影集名称/
        └── 子类名称/
            └── 作品ID/
                ├── cover.jpg
                ├── image_1.jpg
                └── meta.json
```

## 备份脚本

备份和恢复脚本位于 [backupAndRestore](https://github.com/yukongg0625/backupAndRestore) 仓库。
