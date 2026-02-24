# CLAUDE.md

This file provides guidance for Claude when working with this repository.

## Project Overview

This is a **study guide repository** for the **Huawei HCCDA-Tech Essentials** certification exam. It contains Thai-language study notes, image assets extracted from course PDFs, and practice questions organized by chapter.

There is no application code, build system, or test suite. All content is static Markdown and PNG images.

## Repository Structure

```
.
├── CLAUDE.md                                  # This file
├── README.md                                  # Thai-language intro and navigation guide
├── HCCDA_HCCDA_Summary_HEADING_FIXED_v2.md   # Main study notes (1,463 lines, Thai)
└── assets/
    ├── chapter1_pdf_pages/   # 41 PNG slides (Chapter 1)
    ├── chapter2_pdf_pages/   # 30 PNG slides (Chapter 2)
    ├── chapter3_pdf_pages/   # 34 PNG slides (Chapter 3)
    ├── chapter4_pdf_pages/   # 36 PNG slides (Chapter 4)
    ├── chapter5_pdf_pages/   # 37 PNG slides (Chapter 5)
    ├── chapter6_pdf_pages/   # 35 PNG slides (Chapter 6)
    ├── chapter7_pdf_pages/   # 40 PNG slides (Chapter 7)
    └── chapter8_pdf_pages/   # 25 PNG slides (Chapter 8)
```

## Content Structure (9 Chapters)

| Chapter | Topic | Key Services / Concepts |
|---------|-------|--------------------------|
| 1 | Diving into Huawei Cloud | Cloud models (IaaS/PaaS/SaaS), Regions, Availability Zones |
| 2 | Compute Services | ECS, Image management, Auto Scaling |
| 3 | Storage Services | EVS (block), SFS (file), OBS (object) |
| 4 | Networking Services | VPC, Subnet, EIP, NAT Gateway, ELB, Network ACL |
| 5 | Database Services | Huawei Cloud database offerings and selection |
| 6 | Security Services | IAM, DEW (encryption), CTS (audit logging) |
| 7 | Elastic Cloud for Distributed Deployment | Distributed architecture, scalability patterns |
| 8 | Cloud Native and Transformation | Containers, Cloud Native concepts |
| 9 | Exam Outline and Sample Questions | Exam format, practice questions (T/F, single/multi-choice) |

## Language

- Primary language: **Thai** (with English technical terms for Huawei Cloud services)
- When editing or adding content, maintain Thai language for explanations and English for service names/acronyms

## Working with This Repository

### Reading / Navigating
- Start with `README.md` for orientation
- Main content is in `HCCDA_HCCDA_Summary_HEADING_FIXED_v2.md`
- Images in `assets/chapter*_pdf_pages/` are referenced inline from the main file

### Editing Content
- Keep Markdown headings consistent — heading levels are used as navigation anchors in `README.md`
- If chapter headings change, update the jump links in `README.md` to match
- Use `<details>` / `<summary>` blocks for collapsible answer sections in practice questions
- Image references follow the pattern: `assets/chapterN_pdf_pages/pageXX.png`

### Adding New Content
- New practice questions should be appended under the relevant chapter's section
- New chapters should be added to both the main summary file and the `README.md` link table
- Keep PNG assets organized in the corresponding `chapter*_pdf_pages/` folder

### Git Conventions
- `.gitignore` excludes `*.pdf`, `*.zip`, and `.vscode/`
- Do not commit raw PDF files — convert to PNG and place in the appropriate `assets/` subfolder
- Commit messages should be clear and describe which chapter or section was updated

## No Build or Test Commands

This is a static documentation repository. There are no:
- Package managers or dependency files
- Build scripts or Makefiles
- Test suites or CI pipelines

To view the content, open the Markdown files in any Markdown-capable viewer (GitHub, VS Code, Obsidian, etc.).
