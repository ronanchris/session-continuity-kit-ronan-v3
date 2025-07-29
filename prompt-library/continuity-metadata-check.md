# 📄 Prompt: Continuity Metadata Check

## ✨ Purpose
This prompt helps Cursor check whether strategic files in a project contain the necessary session continuity metadata: `session-id`, `linked-notes`, `summary`, and `context-priority`.

## 🧠 Prompt

Please scan this project for Markdown files that show signs of strategic reasoning, reusable frameworks, or cross-session references.

For each qualifying file, insert this YAML frontmatter at the top:

```yaml
---
session-id: <human-readable-ID>
linked-notes:
  - <related files>
context-priority: high
summary: >
  <1–3 sentence summary of this file's continuity role>
---
```

Only apply this to files that evolve, link to others, or guide strategy. Skip static files, checklists, or rules.

## 📦 Tags
- continuity
- metadata
- session-awareness
- yaml