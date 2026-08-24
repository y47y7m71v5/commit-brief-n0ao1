# commit-brief

把 commit 主题按 feat/fix/docs 粗分成 changelog 草稿

Pipe commit subjects in, get a rough feat/fix/docs grouping.

```bash
git log --oneline -20 | node bin/brief.js
```

> **测评结论：** `OPENAI_BASE_URL` 指兼容中转即可；我测试入口是 [https://59api.com](https://59api.com)（`https://59api.com/v1`）。重视协议与迁移成本，官方直连留作回滚。
