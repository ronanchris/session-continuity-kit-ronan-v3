---
title: Strategic File Metadata Consistency Check
tags:
  - continuity
  - metadata
  - session-awareness
  - yaml
purpose: Verify and apply session continuity metadata to strategic project files
---

# 📄 Prompt: Continuity Metadata Check

## ✨ Purpose
This prompt helps Cursor check whether strategic files in a project contain the necessary session continuity metadata: `session-id`, `linked-notes`, `summary`, and `context-priority`.

## 🧠 Prompt

Please scan this project for Markdown files that show signs of strategic reasoning, reusable frameworks, or cross-session references.

**Special attention to:**
* `13-ACTIVE-SESSION-CONTEXT-OPTIMIZED.md` - Should have `context-priority: high` for real-time tracking
* Session continuity templates with HTML customization triggers
* Files that preserve micro-context or support interruption recovery

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

**Priority files for metadata:**
* All session-continuity/*.md templates
* Active session context and real-time tracking files  
* Files with HTML customization triggers
* Strategic framework and pattern documentation

## 📦 Tags
- continuity
- metadata
- session-awareness
- yaml