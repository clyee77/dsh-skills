# dsh-skills

DeepSeek Harness（DSH）的 skill 和客户端插件集中存放仓库。

## 目录结构

```
.
├── skills/     每个子目录是一个独立 skill，内含 SKILL.md
└── plugins/    每个子目录是一个独立客户端插件
```

## skills

每个 skill 一个目录，目录名即 skill 名（小写、连字符分隔），至少包含：

```
skills/my-skill/
└── SKILL.md    顶部 YAML frontmatter：name / description
```

`SKILL.md` 的 `description` 决定它什么时候被触发，写清楚「做什么」和「什么时候用」。

## plugins

每个插件一个目录，结构与 DSH 客户端插件一致，包含各自的 `package.json`。

## 提交约定

- 一个 skill / 插件一个 commit，信息写清楚新增还是修改；
- 不要提交 `node_modules`、构建产物、日志和任何包含密钥的文件。
