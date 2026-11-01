# skills

每个子目录是一个独立 skill。

```
skills/
└── <skill-name>/
    ├── SKILL.md          必需，含 YAML frontmatter
    └── ...               可选：脚本、模板、参考资料
```

`SKILL.md` 格式：

```markdown
---
name: <skill-name>
description: 一句话说明做什么、什么时候该用
---

具体操作步骤……
```

新增 skill 的流程：建目录 → 写 `SKILL.md` → `git add` → commit → push。
