# TRAAACE 🌴   

A fast, lightweight desktop app for tagging, organizing, and analyzing wildlife camera photos.
Designed for conservationists, researchers, and nature enthusiasts.

---

### 📊 Standardized Export Format

Every export (Excel, CSV, TXT, JSON) adheres to the identical, clear 9-column structure across both Quick and Batch modes:

| Column | Description | Example |
| :--- | :--- | :--- |
| **Folder** | The source batch or session folder name | `SiteA_2026-10-20` |
| **File** | Media filename | `DSCF0042.JPG` |
| **Media Type** | `Photo` or `Video`, from the file extension | `Photo` |
| **Site Name** | Deployment or camera station site identifier | `Ridge_North_01` |
| **Date** | Date of capture (YYYY-MM-DD) | `2026-10-20` |
| **Time** | Time of capture (HH:MM:SS) | `08:42:15` |
| **Species** | Identified animal or classification tag | `Kiwi` |
| **Animal Count** | Number of individuals observed in frame | `2` |
| **Comment** | Notes, behavior, or observation remarks | `Foraging near burrow` |

- **Excel (`.xlsx`)**: Formatted spreadsheet with custom headers, styled cells, and optimized column widths.
- **CSV (`.csv`)**: Clean comma-separated values formatted with a UTF-8 Byte Order Mark (BOM) for direct compatibility with Microsoft Excel and R.
- **Manifest (`.txt`)**: Human-readable text report containing summary statistics, species breakdown frequencies, and tabular observations.
- **JSON (`.json`)**: Structured JSON records suitable for data pipelines and scientific repositories.

---

## 🙏 Credits

Kakapo logo: [Kakapo by Cimrin](https://thenounproject.com/browse/icons/term/kakapo/) from Noun Project, licensed under [CC BY 3.0](https://creativecommons.org/licenses/by/3.0/). The credit is also shown in the app on the welcome screen and in the Guide.

---

## 📄 License

[![License: GPL v3](https://img.shields.io/badge/License-GPLv3-blue.svg)](https://www.gnu.org/licenses/gpl-3.0)
