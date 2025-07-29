# 🔁 Prompt: Modular Reuse with `^block-id` Anchors

## ✨ Purpose
This prompt helps Cursor detect and tag reusable logic sections using `^block-id`, enabling modular references via Obsidian-style embeds (`![[...#^block-id]]`).

## 🧠 Prompt

Please scan this project for strategic Markdown files that contain logic, frameworks, or patterns that may be reused within the same folder.

For each such file:

* Identify headers, bullet lists, or structured logic blocks that are referenced or reused
* Mark the beginning of each reusable section with a `^block-id`

  * Use short, semantic IDs like `^ai-checklist`, `^qa-pattern`, `^success-criteria`
* Propose or add example usage with:
  `![[filename#^block-id]]`

Do not mark trivial text or boilerplate. Focus only on reusable reasoning or strategic anchors.

## 📦 Tags
- modular
- reuse
- block-id
- embedding
- continuity