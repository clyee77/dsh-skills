# plugins

每个子目录是一个独立客户端插件，结构遵循 DSH 客户端插件约定。

```
plugins/
└── <plugin-name>/
    ├── package.json
    └── src/
```

插件通常需要构建后才能被 DSH 加载，构建产物（`dist/` 等）不入库，由 CI 或本地构建生成。
