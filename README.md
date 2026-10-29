# TRAAACE 🌴   

A fast, lightweight desktop app for tagging, organizing, and analyzing wildlife camera photos.
Designed for conservationists, researchers, and nature enthusiasts in Aotearoa.

It has adjustable species hotkeys and comments, and can export CSV, XLSX, JSON and TXT files.

There are two workspaces, Quick and Project. The Project workspace lets you manage your folders and gives insights into your data. When you export your data and images, you can choose to merge the data and organise the images into subfolders by species.

You can scale the interface to any size with CTRL/CMD + / - and there are light and dark modes.

There is an optional AI add-on for species suggestions that uses Alita, MegaDetector v5a, ONNX Runtime and FFmpeg. The repo for the AI add-on is [here](https://github.com/just8080/traaace_ai).

The app installers are 5–7 MB. The standard AI add-on is about 540 MB to download, and the NVIDIA (CUDA) add-on is about 3.5 GB, most of which comes straight from NVIDIA.

By default the AI (ONNX Runtime 1.31) runs on your processor on Windows and Linux. On Apple Silicon Macs it uses Apple's Core ML, which is much faster (Intel Macs can't use the AI add-on).

There is an [experimental download](https://traaace.ing/gpu.html) for Windows users with an NVIDIA graphics card. I haven't been able to test it on a computer with an NVIDIA card yet, so feedback would be great.

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

---

## 🙏 Credits

Kakapo logo: [Kakapo by Cimrin](https://thenounproject.com/browse/icons/term/kakapo/) from Noun Project, licensed under [CC BY 3.0](https://creativecommons.org/licenses/by/3.0/).

---

## 📄 License

[![License: GPL v3](https://img.shields.io/badge/License-GPLv3-blue.svg)](https://www.gnu.org/licenses/gpl-3.0)
