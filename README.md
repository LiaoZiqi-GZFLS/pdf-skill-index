# pdf-skill-index

A **pointer** to the official Anthropic `pdf` Agent Skill — not a copy of it.

Nothing from the skill lives in this repository: no `SKILL.md`, no scripts, no
prompt text, no assets. This page exists precisely because the skill is
proprietary and cannot be redistributed, so linking is the only correct way to
point people at it.

## Upstream

| | |
| --- | --- |
| Skill | `pdf` |
| Repository | [anthropics/skills](https://github.com/anthropics/skills) |
| Skill directory | [`skills/pdf`](https://github.com/anthropics/skills/tree/main/skills/pdf) |
| License | [`skills/pdf/LICENSE.txt`](https://github.com/anthropics/skills/blob/main/skills/pdf/LICENSE.txt) |
| Siblings | `docx`, `pptx`, `xlsx` (same repo, same terms) |

## What it covers

Read the upstream directory for the authoritative description. In broad terms it
handles reading/extracting PDF content, structural edits (merge, split, rotate),
document generation, form filling, encryption and watermarks, embedded image
extraction, and OCR for scanned documents.

## Why this repo only links

`skills/pdf/LICENSE.txt` is © Anthropic, PBC — all rights reserved. Its
"ADDITIONAL RESTRICTIONS" section prohibits, among other things:

- reproducing or copying the materials
- distributing, sublicensing, or transferring them to a third party
- creating derivative works
- retaining copies of the materials outside Anthropic's services

Note what this means for "credit the original author" style reposts: **attribution
does not help.** The restriction targets the act of redistribution itself, not
redistribution without credit. A README declaring the origin changes nothing.

So this repository contains links and commentary only.

## How to actually get it

Use an official distribution channel instead of copying files around:

- **Qoder** ships this skill — along with `docx`, `pptx`, and `xlsx` — as bundled
  skills. They are seeded automatically on first run and land in your local
  `~/.qoder-cn/skills/<name>/` directory.
- **Claude** includes the document skills natively.

If you need to redistribute it yourself — bundling it into your own product, for
instance — get written permission from Anthropic first.

## 中文说明

本仓库**只是链接索引**，不含该 skill 的任何内容：没有 `SKILL.md`、没有脚本、没有提示词原文、
没有素材。

上游 `anthropics/skills` 的 `skills/pdf/LICENSE.txt` 版权归 Anthropic, PBC，保留所有权利；
其 "ADDITIONAL RESTRICTIONS" 一段明确禁止复制、再分发、转授权、创作衍生作品，以及
"在 Anthropic 服务之外保留副本"。其中最关键的一点是：**署名不能解锁任何一项** ——
被禁止的是再分发行为本身，而不是"未署名的再分发"。所以写一份"转载声明"并不改变结论。

因此本仓库只放链接和说明。要拿到这个 skill，请走官方渠道：Qoder 首次运行时会自动把
`pdf` 及 `docx`/`pptx`/`xlsx` 播种到本地 `~/.qoder-cn/skills/`；Claude 也原生内置。
若确实需要把它分发进自己的产品，请先取得 Anthropic 的书面许可。

## Related

- [LiaoZiqi-GZFLS/pdf-reader](https://github.com/LiaoZiqi-GZFLS/pdf-reader) — an
  independent PDF reading skill built on PyMuPDF. Separate codebase, no overlap
  with the upstream skill, and not subject to the terms above.
