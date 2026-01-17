\# Stakeholder-Centered Explainability for Code Generation Models



This repository contains the \*\*supplementary materials and research artifacts\*\* for the paper:



> \\\*\\\*Explaining Code Generation AI Models: Are We Meeting Stakeholder Needs?\\\*\\\*  

> \\\*(under review)\\\*



\## Abstract



The growing adoption of AI models (including Large Language Models) for code generation in everyday software development has intensified concerns around their transparency and the need for robust explainability methods to foster trust in these systems. Despite a growing body of explainability techniques, little is known about how well these methods serve the distinct goals of two key stakeholder groups: model users (e.g., developers) and model engineers. In this work, we present the first systematic mapping between existing explainability approaches for code generation and the practical questions and concerns of these takeholders.We gather stakeholder requirements using an LLM-assisted elicitation method. By aligning our gathered requirements and questions with current eXplainable AI (XAI) techniques, we uncover critical gaps in existing explainability support. Our findings lay the groundwork for a more user-centered design of explainability tools in code generation.

\### Supplementary Materials and Research Artifacts





The artifacts in this repository support the \*\*systematic literature review (SLR)\*\*, \*\*LLM-assisted requirements elicitation\*\*, \*\*stakeholder validation survey\*\*, and \*\*gap analysis\*\* presented in the paper.  

They are provided to enhance \*\*transparency, reproducibility, and reuse\*\*.



---



\## 📂 Repository Structure and Contents



\### 🔍 Systematic Literature Review (SLR)



\- \*\*`search/search\_strings.md`\*\*  

&nbsp; Contains the complete search queries used for the systematic literature review, including the use of wildcard operators (e.g., `explain\*`, `interpret\*`) to ensure comprehensive coverage.



\- \*\*`data-extraction/data\_extraction\_workbook.xlsx`\*\*  

&nbsp; An Excel workbook containing:

&nbsp; - The data extraction template used in the review

&nbsp; - Extracted data for the ten selected primary studies

&nbsp; - Mapping between papers and the explainability concerns they address



---



\### 🤖 LLM-Assisted Requirements Elicitation



\- \*\*`prompts/llm\_elicitation\_prompts.md`\*\*  

&nbsp; Includes the prompts used with the ChatGPT web interface (GPT-4–class model) to elicit explainability requirements and questions for:

&nbsp; - Code generation model users

&nbsp; - Code generation model engineers



These prompts were used to generate initial requirement sets that were later refined and validated.



---



\### ❓ Explainability Question Banks



\- \*\*`question-banks/XAIQB\_original\_vs\_customized.pdf`\*\*  

&nbsp; A side-by-side comparison of:

&nbsp; - An existing explainability question bank for code generation models

&nbsp; - The customized and extended question banks developed in this study



This document highlights how stakeholder-driven questions extend beyond existing formulations.



---



\### 📊 Stakeholder Validation Survey



\- \*\*`survey/survey\_instrument.pdf`\*\*  

&nbsp; The survey instrument used to validate the relevance of:

&nbsp; - Model user requirements

&nbsp; - Model engineer requirements

&nbsp; - Explainability questions



Survey responses informed the prioritization and gap analysis reported in the paper.



---



\### 🔁 Artifact–Paper Traceability



\- \*\*`artifact-mapping.md`\*\*  

&nbsp; Provides a mapping between the paper sections, tables, and results and the corresponding artifacts in this repository.



---



\## ⚠️ Reproducibility and Tooling Notes



\- Requirements elicitation was conducted using the \*\*ChatGPT web interface (OpenAI)\*\*.

\- At the time of use, ChatGPT was powered by a \*\*GPT-4–class model\*\*.

\- The exact model version and minor revisions are not disclosed by OpenAI.

\- Due to the non-deterministic nature of LLMs, regenerated outputs may vary slightly.



These factors are discussed as part of the \*\*threats to validity\*\* in the paper.



---



\## 📜 License



This repository is released under the \*\*Creative Commons Attribution 4.0 International (CC BY 4.0)\*\* license.  

You are free to reuse the materials with appropriate attribution.



---



\## 📣 How to Cite



If you use these artifacts, please cite the associated paper.  

A `CITATION.cff` file is provided to support easy citation via GitHub.



---



\## 🤝 Contact



For questions or clarifications regarding the artifacts, please contact the authors via the email provided in the paper.



