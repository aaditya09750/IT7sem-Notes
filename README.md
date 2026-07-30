# IT SEM 7 NOTES - QUESTION BANK & ANSWER ARCHIVE

![PDF](https://img.shields.io/badge/Format-PDF-EC1C24?style=for-the-badge\&logo=adobeacrobatreader\&logoColor=white)
![University](https://img.shields.io/badge/Mumbai_University-R--19_C_Scheme-1F3A68?style=for-the-badge\&logo=googlescholar\&logoColor=white)
![Branch](https://img.shields.io/badge/Branch-Information_Technology-2E5C8A?style=for-the-badge\&logo=bookstack\&logoColor=white)
![Semester](https://img.shields.io/badge/Semester-VII-8B3A3A?style=for-the-badge\&logo=readthedocs\&logoColor=white)
![Subjects](https://img.shields.io/badge/Subjects-5-FF6B35?style=for-the-badge\&logo=files\&logoColor=white)
![License](https://img.shields.io/badge/License-MIT-green?style=for-the-badge\&logo=opensourceinitiative\&logoColor=white)

A subject-wise archive of TE IT Semester VII revision material - MUSA question banks, university question papers, repeated-question shortlists, theory-question frequency reports, the compulsory Q1 5-marks repetition analysis, and full answer keys. Each subject lives in its own self-contained folder so a single subject can be downloaded, printed, or shared without dragging the rest of the repo along.

**Maintainer:** Aaditya Gunjal - TE IT, Mumbai University

## Indexed Subjects

*   **AI & DS II** - see [AI & DS II/](AI%20&%20DS%20II/)
*   **Cyber Security & Laws** - see [Cyber Security & Laws/](Cyber%20Security%20&%20Laws/)
*   **Internet Of Everything** - see [Internet Of Everything/](Internet%20Of%20Everything/)
*   **Software Testing & QA** - see [Software Testing & QA/](Software%20Testing%20&%20QA/)

## Core Features

### Subject-Wise Isolation

Every subject is a self-contained folder. Question banks, papers, and answer keys for one subject never spill over into another, so you can clone a single folder and have everything you need for that exam.

### PYQ PDFs

Each subject folder contains a `PYQ.pdf` file, which includes Previous Year Questions for revision.

## Repository Structure

```text
IT7sem Notes/
|-- README.md
|-- AI & DS II/
|   `-- AI&DS PYQ.pdf
|-- Cyber Security & Laws/
|   `-- CS&L PYQ.pdf
|-- Internet Of Everything/
|   `-- IOE PYQ.pdf
`-- Software Testing & QA/
    `-- Software Testing & QA PYQ.pdf
```

## File Naming Convention

| Suffix       | Purpose                                             |
| :----------- | :-------------------------------------------------- |
| `<Subject> PYQ.pdf` | Previous Year Questions for the subject. |

Stick to this convention when adding new files - it keeps subject folders predictable and makes future tooling (search, indexing, the planned study portal) trivial to wire up.

## Quick Start

### Browse a Subject

```bash
# AI & DS II
start "AI & DS II/"                        # Windows
open "AI & DS II/"                         # macOS

# Or open a specific PDF directly
start "AI & DS II/AI&DS PYQ.pdf"
```

### Download a Single Subject Folder

GitHub does not support folder-only downloads natively. Use one of:

```bash
# Sparse clone (Git 2.25+) - pulls just one subject folder
git clone --filter=blob:none --no-checkout https://github.com/aaditya09750/IT7sem-Notes.git
cd IT7sem-Notes
git sparse-checkout init --clone
git sparse-checkout set "AI & DS II"
git checkout main
```

```bash
# Or grab the whole repo (smallest pain, ~10 MB)
git clone https://github.com/aaditya09750/IT7sem-Notes.git
```

## Adding a New Subject

1.  **Create a folder** at the repo root using the subject's full name, e.g. `New Subject/`.
2.  **Drop in the PDFs** following the naming convention above:

    *   `New Subject/New Subject PYQ.pdf` - Previous Year Questions
3.  **Update this README** - add the subject to the **Indexed Subjects** list and the **Repository Structure** tree.
4.  **Stage with `git mv`** if you are moving existing files - it preserves history and keeps the diff readable.

## Adding a New File to an Existing Subject

```bash
# Example: adding a fresh PYQ to AI & DS II
git add "AI & DS II/AI&DS PYQ.pdf"
git commit -m "chore(AI & DS II): updated PYQ"
```

Keep commit messages in the existing style - `feat:`, `chore:`, or `feat(<subject>):` scoped prefixes match the rest of the log.

## Roadmap

This folder is the source of truth for an upcoming **`it7-study-portal`** - a Next.js 15 + Drizzle (SQLite) + Auth.js v5 web app that will index every PDF, expose subject-wise search, and surface PYQ drills directly in the browser. PDFs will keep living here; the portal will read them via a `PDF_CONTENT_DIR` pointer rather than duplicating files.

## License

![License](https://img.shields.io/badge/License-MIT-green?style=for-the-badge\&logo=opensourceinitiative\&logoColor=white)

```text
MIT License

Copyright (c) 2026 Aaditya Gunjal

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.
```

> Source PDFs (MUSA question banks, university papers) remain the intellectual property of their original authors and Mumbai University. The MIT license covers the organisation, naming, and structure of this archive only.

---

## IT Sem 7 Notes

A clean, subject-wise archive of MUSA QBs, university papers, and answer keys for TE IT students at Mumbai University. One folder per subject, one convention across the repo.

**Star this repository if it helped you prep for an exam!**
