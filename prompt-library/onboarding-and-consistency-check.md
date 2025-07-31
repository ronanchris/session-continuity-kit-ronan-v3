---
title: AI Session Onboarding and Continuity Audit
tags:
  - onboarding
  - continuity
  - audit
  - session-initialization
  - system-check
purpose: Initialize an AI session by comprehensively checking project metadata, block usage, and system alignment
---

# 🧠 Prompt: AI Onboarding + Continuity Consistency Check

## ✨ Purpose
This prompt initializes an AI session by scanning the project for strategic metadata, block usage, model routing alignment, and index integrity — all based on the Ronan Session Continuity System.

## 🧠 Prompt

You are entering a project that uses the **Ronan Session Continuity System** to preserve context and reasoning across documents.

Please review this project with the following goals in mind:

---

### ✅ CONTINUITY SYSTEM AUDIT

**1. Metadata Check**

* Confirm that all strategic Markdown files include:

  * `session-id`
  * `linked-notes`
  * `summary`
  * `context-priority`

**2. Modular Reuse**

* Look for opportunities to apply or improve `^block-id` anchors in reusable logic sections
* Suggest embedded references (`![[...#^block-id]]`) where appropriate within the same project

**3. Rule Alignment**

* Ensure `.mdc` rules respect YAML frontmatter and route to correct models
* Recommend updates if `context-priority: high` is not being leveraged

**4. Index Integrity**

* Open `00-CONTINUITY-INDEX.md` and verify that it includes:

  * All key strategic files with session metadata
  * Summaries that match the file's contents
  * Accurate filenames and linked-notes alignment
  * Reference to `13-ACTIVE-SESSION-CONTEXT-OPTIMIZED.md` in Real-Time Context section

**5. Active Session Context Validation**

* Confirm `13-ACTIVE-SESSION-CONTEXT-OPTIMIZED.md` exists and includes:
  * HTML customization trigger for guided setup
  * Session lens integration (4-6 items max)
  * Token optimization (<2KB target)
  * Interruption recovery sections
  * Tool state tracking capabilities

**6. Prompt Library Coherence**

* Scan `prompt-library/` and validate that all prompts:

  * Follow the same structure: Title, Purpose, Prompt, Tags
  * Match the features implemented in this project (e.g. metadata, reuse, rules)

---

### 🧠 CONTEXT PRIMING FOR THIS SESSION

After reviewing, do the following:

* Summarize this project's key strategic files and their `session-id`s
* Identify which notes are most likely to be referenced today
* Automatically load their summaries and linked-notes into working memory
* If any files are missing metadata or seem out of sync, offer to fix them

Treat this session as part of an ongoing context-aware system. Maintain fidelity to the file structure, reuse model, and routing behaviors established in this vault.

## 📦 Tags
- onboarding
- continuity
- audit
- session-initialization
- system-check