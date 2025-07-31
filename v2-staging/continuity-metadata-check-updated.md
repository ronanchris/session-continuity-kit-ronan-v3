---
title: Strategic File Metadata Consistency Check - Surgical System
tags:
  - continuity
  - metadata
  - session-awareness
  - yaml
  - surgical-architecture
purpose: Verify and apply session continuity metadata to strategic project files in the surgical 6-template system
---

# 📄 Prompt: Continuity Metadata Check - Surgical System

## ✨ Purpose
This prompt helps Cursor check whether strategic files in a project contain the necessary session continuity metadata for the surgical 6-template Session Continuity Core system: `session-id`, `linked-notes`, `summary`, and `context-priority`.

## 🧠 Prompt

Please scan this project for Markdown files that show signs of strategic reasoning, reusable frameworks, or cross-session references compatible with the surgical Session Continuity Core architecture.

**Focus on the 6-template surgical system**:
- `AI-COLLABORATION-CORE.md` - Should have `context-priority: high` for meta-collaboration intelligence
- `SESSION-MANAGEMENT.md` - Should have `context-priority: high` for session lens methodology  
- `PROJECT-REQUIREMENTS.md` - Should have HTML customization triggers
- `PROBLEM-SOLVING-METHODS.md` - Should have systematic methodology preservation
- `LEARNING-CAPTURE.md` - Should have breakthrough documentation capabilities
- `SYSTEM-DEPLOYMENT.md` - Should have complete deployment and validation guidance

For each qualifying file in the surgical system, ensure this YAML frontmatter exists:

```yaml
---
session-id: <human-readable-ID>
linked-notes:
  - <related files from 6-template system>
context-priority: high
summary: >
  <1–3 sentence summary of this file's role in the surgical continuity system>
---
```

**Priority validation for surgical architecture**:
- All 6 core templates should have proper metadata
- Linked-notes should reference only existing templates in the surgical system
- Context-priority should reflect importance in the 6-template hierarchy
- Summary should describe role in surgical precision architecture

**Do NOT reference eliminated templates**:
- ❌ 13-ACTIVE-SESSION-CONTEXT-OPTIMIZED.md (eliminated)
- ❌ Separate session planning/state/entrance files (consolidated)
- ❌ Separate collaboration/DNA files (consolidated)
- ❌ Templates eliminated in surgical consolidation

Only apply metadata to files that evolve, link to others, or guide strategy within the surgical 6-template system. Skip static files, checklists, or rules that don't participate in the strategic session continuity framework.

## 📦 Tags
- continuity
- metadata
- session-awareness
- yaml
- surgical-architecture