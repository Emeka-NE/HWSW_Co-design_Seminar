# High-Level Synthesis with Ant Colony Optimization Scheduling

**Student:** Nnaemeka Nnachi-Egwu  
**Program:** Electronic Engineering  
**Institution:** Hochschule Hamm-Lippstadt, Lippstadt, Germany  
**Email:** nnaemeka.nnachi-egwu@stud.hshl.de  
**Seminar:** HW/SW Co-Design (Prof. Dr. Achim Rettberg)  
**Main Reference:** S. Kopuri and N. Mansouri, "Enhancing Scheduling Solutions Through Ant Colony Optimization," IEEE ISCAS 2004, pp. V-257--V-260.

---

## Repository Structure

```
aco-hls-seminar/
│
├── README.md                                  ← this file
│
├── milestones/
│   ├── README.md
│   ├── M1/
│   │   ├── README.md
│   │   └── M1_NnaemekaNnachiEgwu.md           ← Technical Understanding (rough notes)
│   ├── M2/
│   │   ├── README.md
│   │   └── M2_NnaemekaNnachiEgwu.md           ← Contextualization & Tradeoffs (rough notes)
│   ├── M3/
│   │   ├── README.md
│   │   └── M3_NnaemekaNnachiEgwu.md           ← Critical Evaluation (rough notes)
│   └── M4/
│       ├── README.md
│       ├── M4_NnaemekaNnachiEgwu.tex          ← Final IEEE Paper (LaTeX source)
│       ├── M4_NnaemekaNnachiEgwu.bib          ← BibTeX references (7 entries)
│       ├── M4_NnaemekaNnachiEgwu.pdf          ← Compiled PDF (5 pages)
│       └── M4_NnaemekaNnachiEgwu_LaTeX.zip   ← Self-contained LaTeX package
│                                                  (includes IEEEtran.cls)
│
├── ai_protocol/
│   ├── README.md
│   ├── M1/
│   │   ├── README.md
│   │   ├── ai_usage_protocol_nnaemeka-nnachi-egwu_m1-technical-understanding.ipynb
│   │   ├── ai_usage_protocol_nnaemeka-nnachi-egwu_m1-technical-understanding.json
│   │   └── ai_usage_protocol_nnaemeka-nnachi-egwu_m1-technical-understanding.bib
│   ├── M2/   (same 3-file structure)
│   ├── M3/   (same 3-file structure)
│   └── M4/   (same 3-file structure)
│
├── implementation/
│   ├── README.md
│   ├── scheduler.hpp        ← C++17 CDFG types, FDS + A_FDS declarations
│   ├── scheduler.cpp        ← Equations 1–5, clique partitioning, Left-Edge
│   ├── main.cpp             ← Driver: all 4 benchmarks + sign-fix comparison
│   ├── Makefile             ← make / make clean
│   └── vhdl/
│       ├── README.md
│       └── datapath.vhd     ← Synthesisable VHDL entity (Elliptical Filter datapath)
│
└── docs/
    ├── README.md
    ├── cheat_sheet.txt      ← Presentation prep: key numbers, equations, Q&A
    └── gamma_prompt.txt     ← Self-contained 10-slide gamma.app prompt
```

---

## Milestone Summary

| Milestone | File | Format | Content |
|---|---|---|---|
| M1 | `M1_NnaemekaNnachiEgwu.md` | Markdown (rough notes) | Technical understanding, all 5 equations, sign finding flagged |
| M2 | `M2_NnaemekaNnachiEgwu.md` | Markdown (rough notes) | Scheduling landscape, tradeoff tables, ACO variant comparison |
| M3 | `M3_NnaemekaNnachiEgwu.md` | Markdown (rough notes) | Sign-convention proof, suitability analysis, extensions |
| M4 | `M4_NnaemekaNnachiEgwu.tex/.pdf` | IEEEtran LaTeX (5 pp) | Full paper integrating M1–M3 |

M1–M3 are **intentionally rough** -- bullets, tables, pseudocode. The seminar checklist explicitly forbids publication-style prose for these milestones.
