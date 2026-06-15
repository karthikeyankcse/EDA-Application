# EDA Python Applications

A suite of **GUI-based Python automation applications** for EDA engineering workflows. Built with Tkinter, OOP architecture, and cross-platform compatibility — designed to eliminate manual effort in PCB engineering processes.

---

## 📦 Applications

### BOM Compare
Compares two Bill of Materials files (Excel/CSV) and identifies:
- Added, removed, and modified components
- Quantity mismatches
- Part number / value / footprint discrepancies
- Outputs a structured mismatch report

**Stack:** Python, Tkinter, openpyxl, pandas

---

### Allegro BRD Compare
Compares two Cadence Allegro `.brd` files and reports differences in:
- Component placement (XY coordinates, rotation, mirror status)
- Net connectivity
- Layer stackup changes
- Outputs field-level mismatch logs

**Stack:** Python, Tkinter, Cadence Allegro batch SKILL

---

### Inter Tool Communication — CAM ↔ Allegro
Bridges data between CAM 350 and Cadence Allegro PCB Editor:
- Transfers layer mapping, drill data, and stackup information
- Eliminates manual re-entry between tools
- Configurable mapping rules via GUI

**Stack:** Python, Tkinter, subprocess, file I/O

---

### Report Generator
Automated engineering report generation from PCB design data:
- Reads design data from Allegro/OrCAD output files
- Generates formatted Excel/PDF reports
- Supports BOM, placement, net list, and DRC report types

**Stack:** Python, Tkinter, openpyxl, reportlab

---

## 🚀 Key Features

- **Tkinter GUI** — Clean, intuitive interfaces requiring no command-line usage
- **OOP Architecture** — Modular, maintainable codebase with clear separation of concerns
- **Cross-platform** — Compatible with Windows and Linux
- **Executable packaging** — Deployable as standalone `.exe` without Python installation
- **Large file handling** — Optimized for processing large BRD and BOM files efficiently

---

## 🛠️ Requirements

```
Python 3.8+
tkinter (built-in)
openpyxl
pandas
```

Install dependencies:
```bash
pip install openpyxl pandas
```

---

## 📂 Usage

```bash
python app_name.py
```

Each application launches a GUI window. Follow the on-screen prompts to:
1. Select input files
2. Configure comparison/processing options
3. Run and export results

---

## 👤 Author

**Karthikeyan K** — EDA Automation Engineer  
[github.com/karthikeyankcse](https://github.com/karthikeyankcse)
