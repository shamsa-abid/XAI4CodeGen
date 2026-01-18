# Artifact–Paper Mapping

This document maps the **sections, tables, and analyses** in the paper  
*“Stakeholder-Centered Explainability for Code Generation Models”*  
to the corresponding artifacts provided in this repository.

The goal is to support **traceability, transparency, and reproducibility**.

---

## 📘 Mapping Overview

| Paper Section / Element | Artifact | Description |
|------------------------|----------|-------------|
| Research Methodology | `README.md` | High-level overview of artifacts and methodology |
| Systematic Literature Review (SLR) | `search/search_strings.md` | Complete search strings used in the SLR |
| SLR Data Extraction | `data-extraction/data_extraction_workbook.xlsx` | Data extraction template and extracted data |
| Primary Studies (P1–P10) | `data-extraction/data_extraction_workbook.xlsx` | Metadata and extracted evidence from selected papers |
| Requirements Elicitation Method | `prompts/llm_elicitation_prompts.md` | Prompts used for LLM-assisted elicitation |
| Model User Requirements | `survey/survey_instrument.pdf` | Survey questions validating user requirements |
| Model Engineer Requirements | `survey/survey_instrument.pdf` | Survey questions validating engineer requirements |
| Customized Explainability Question Bank | `question-banks/XAIQB_original_vs_customized.pdf` | Customized questions derived in this study |
| Extended XAI4CodeGen Question Bank | `question-banks/XAIQB_original_vs_customized.pdf` | Original and extended question sets |
| Gap Analysis Tables | `data-extraction/data_extraction_workbook.xlsx` | Mapping of requirements/questions to existing literature |
| Results (Coverage Percentages) | `data-extraction/data_extraction_workbook.xlsx` | Counts and percentages used in results |
| Threats to Validity | `README.md` | Notes on LLM usage and reproducibility limitations |

---

## 🧭 How to Use This Mapping

- **Reviewers** can trace claims and tables in the paper to concrete artifacts.
- **Researchers** can reuse the templates, prompts, and question banks.
- **Practitioners** can explore unmet explainability concerns identified in the gap analysis.

---

## 📌 Notes

- All artifacts are provided as-is to reflect the exact materials used in the study.
- Minor formatting or ordering differences may exist between artifacts and their presentation in the paper.
