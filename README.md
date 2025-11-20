[![Encyclopedia of Arabic Rhetoric](static/logo.png "Encyclopedia of Arabic Rhetoric.")](https://al-balagha.com)
# [Arabic Rhetorical Device Taxonomy (v0.1.1)](https://github.com/Al-Balagha/Arabic-Rhetoric/tree/v0.1.1)
### A project of the [Encyclopedia of Arabic Rhetoric](https://al-balagha.com)

The systematic, hierarchical classification of **Arabic rhetorical devices** published by the [Encyclopedia of Arabic Rhetoric](https://al-balagha.com).

&nbsp;
## ℹ️ About
The [Arabic Rhetorical Device Taxonomy](https://al-balagha.com/wiki/Arabic_Rhetorical_Device_Taxonomy) was drafted in 2022 to support the identification of Arabic rhetorical devices in both classical and contemporary Arabic texts. Developed as part of the author's [Master's-level research](https://doi.org/10.48550/arXiv.2507.21106) into the [rhetorical density](http://rhetorical-density.com) of Arabic discourse, the project originated from the observation that existing taxonomies - whether in traditional manuals or modern online resources - were often incomplete, inconsistent in their terminology, and either too basic or completely inaccessible to many students and researchers, especially non-native speakers.

The taxonomy was therefore conceived with the aim of making the sciences of Arabic rhetoric (_al-balāgha_) and their scholarship more accessible, coherent, and navigable for both Arabs and non-Arabs alike. This accessibility is an essential first step to applying contemporary scholarship and computational methods to this rich classical science that lacks a consistent modern structure.

This repository serves as the **open, citable, versioned reference** of the Arabic rhetorical device ontology underpinning the Encyclopedia of Arabic Rhetoric. In continuous development since 2022, the taxonomy is based on classical Arabic rhetorical theory and is suitable for use in computational analysis, corpus annotation, digital humanities research, and education.

The taxonomy is freely released under the CC-BY 4.0 license to promote the development of contemporary Arabic rhetorical studies, and is currently being used by the [**BALAGHA Score**](https://balaghascore.com) and other projects.

&nbsp;
### 🎯 Purpose

The Arabic Rhetorical Device Taxonomy provides:

* A **comprehensive classification** of 95 Arabic rhetorical devices based on classical Arabic sources.
* Definitions grounded in classical scholarship, with references to primary sources.
* Examples illustrating rhetorical device usage.
* A stable versioned repository for use in academic writing and reproducible research.

&nbsp;
### 🔄 Versioning

The taxonomy uses **Semantic Versioning (SemVer)**:
* [20 November 2025 - v0.1.1](https://github.com/Al-Balagha/Arabic-Rhetoric/tree/v0.1.1)  
Machine-readable (JSON, JSON-LD, TTL, RDF/XML) versions of files added to the repository.

* [17 November 2025 - v0.1.0](https://github.com/Al-Balagha/Arabic-Rhetoric/tree/v0.1.0)  
First publicly documented version of the taxonomy released on [GitHub](https://github.com/Al-Balagha/Arabic-Rhetoric).

* 6 September 2022  - Initial draft  
The taxonomy was first developed as part of an [academic dissertation](https://doi.org/10.48550/arXiv.2507.21106) submitted to the University of Exeter.

&nbsp;
### 🗂️ Structure of the Taxonomy

The taxonomy contains a total of 95 rhetorical devices organised into four domains, mirroring classical Arabic rhetoric scholarship:

**DOMAIN A: Sentence Construction \& Syntactical Stylistics  (علم المعاني)** with 14 rhetorical devices

**DOMAIN B: Figurative Speech (علم البيان)** with 7 rhetorical devices

**DOMAIN C: Linguistic Embellishments (علم البديع)** with 68 rhetorical devices, which has been further sub-divided into ten subdomains:

* *Subdomain CA* - Wordplay \& Phonetic Styling with 3 rhetorical devices
* *Subdomain CB* - Contrasts \& Inversions with 5 rhetorical devices
* *Subdomain CC* - Repetition \& Reinforcement with 2 rhetorical devices
* *Subdomain CD* - Indirectness \& Ambiguity with 5 rhetorical devices
* *Subdomain CE* - Grouping \& Distinguishing with 8 rhetorical devices
* *Subdomain CF* - Paragraph Structure \& Flow with 11 rhetorical devices
* *Subdomain CG* - Argumentation \& Illustrative Persuasion with 10 rhetorical devices
* *Subdomain CH* - Persuasive Tricks with 15 rhetorical devices
* *Subdomain CI* - Sound Aesthetics with 3 rhetorical devices
* *Subdomain CJ* - Rhythmic Structuring \& Balance with 6 rhetorical devices

**DOMAIN D: Negative Rhetorical Effects** with 6 linguistic defects which weaken the rhetorical strength of a discourse.

&nbsp;

Each rhetorical device entry typically includes:

* Name (in English and Arabic)
* Category and subcategory
* Definition
* Function
* Examples
* Cross-references
* Notes on usage, variants, and interpretation
* References to classical sources

Please refer to the file **[taxonomy-index](taxonomy-index.md)** for a list of all the Arabic rhetorical devices included in the taxonomy.

&nbsp;
### 📦 Repository Contents
#### Human-readable content
The repository provides both [PDF](PDF) and self-contained standalone [HTML](HTML) snapshots from the [Encyclopedia of Arabic Rhetoric](https://al-balagha.com), ensuring:

* Archival stability
* Version-locked documentation
* Accurate visual references for researchers and reviewers

Each HTML and PDF file reflects the content of the encyclopedia on the date of the v0.1.0 release (20 November 2025).

The PDF file **[Encyclopedia_of_Arabic_Rhetoric_FULL](Encyclopedia_of_Arabic_Rhetoric_FULL.pdf)** combines all repository pages into a single document for ease of sharing, citation, and use on mobile devices.

#### Machine-readable content
[Machine-readable](machine-readable) versions of the taxonomy are also provided in [JSON](machine-readable/json), [JSON-LD](machine-readable/jsonld), [RDF/XML](machine-readable/rdfxml) and [Turtle (TTL)](machine-readable/ttl), formats for compatibility with linked-data workflows, digital humanities tools, and semantic applications.


&nbsp;
#### 📚 Folder structure
```
/
├── README.md
├── LICENSE.txt
├── taxonomy-index.md
├── CITATION.cff
├── CHANGELOG.md
├── Encyclopedia_of_Arabic_Rhetoric_FULL.pdf
├── PDF/
│   ├── A-Sentence_Construction_and_Syntactical_Stylistics_(ilm_ul_maani)/
│   ├── B-Figurative_Speech_(ilm_ul_bayaan)/
│   ├── C-Linguistic_Embellishments_(ilm_ul_badi)/
│   └── D-Negative_Rhetorical_Effects/
│
├── HTML/
│   ├── A-Sentence_Construction_and_Syntactical_Stylistics_(ilm_ul_maani)/
│   ├── B-Figurative_Speech_(ilm_ul_bayaan)/
│   ├── C-Linguistic_Embellishments_(ilm_ul_badi)/
│   └── D-Negative_Rhetorical_Effects/
│
└── machine-readable/
    ├── json/
    ├── jsonld/
    ├── rdfxml/
    └── ttl/
```

&nbsp;
### 📖 How to Cite
**APA:**
Marathe, M. (2025). Arabic Rhetorical Device Taxonomy (v0.1.1) of the Encyclopedia of Arabic Rhetoric (al-Balagha.com) [Data set]. GitHub. https://doi.org/10.5281/zenodo.17635958

**Chicago:**
Marathe, Mandar. 'Arabic Rhetorical Device Taxonomy (v0.1.1) of the Encyclopedia of Arabic Rhetoric (al-Balagha.com)'. Data set, GitHub, 2025. https://doi.org/10.5281/zenodo.17635958

**BibTeX:**
```bibtex
@dataset{albalagha2025,
  author = {{Mandar Marathe}},
  title = {Arabic Rhetorical Device Taxonomy (v0.1.1) of the Encyclopedia of Arabic Rhetoric (al-Balagha.com)},
  year = {2025},
  version = {0.1.1},
  url = {https://doi.org/10.5281/zenodo.17635958}
}
```

&nbsp;<br>
---
## 📬 About the Author
**[Dr Mandar Marathe](https://marathe.org)** | [SOAS Profile](https://www.soas.ac.uk/about/mandar-marathe)  
PhD Researcher in Arabic Rhetoric | SOAS University of London  
[![Project Home](https://img.shields.io/badge/ARDT%20Project-Home-green)](https://al-balagha.com/wiki/Arabic_Rhetorical_Device_Taxonomy)  

### Related Projects
- 📚 [Encyclopedia of Arabic Rhetoric](https://al-balagha.com) - Reference source for Arabic rhetorical devices  
- 💯 [BALAGHA Score](https://balaghascore.com) - Arabic rhetorical density analysis  
- 📖 [Balagha Corpus](https://balagha-corpus.com) - Annotated texts for Arabic rhetorical analysis  
- 📡 [BalaghaBase.org](https://balaghabase.org) - Semantic knowledge graph for Arabic rhetoric  
- 🔬 [Rhetorical Density](https://rhetorical-density.com) - Methodology and discussion of rhetorical density as a quantitative metric  

### Connect
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Profile-blue)](https://www.linkedin.com/in/mandar-marathe-uk/) [![ORCID](https://img.shields.io/badge/ORCID-Profile-green.svg)](https://orcid.org/0000-0002-6927-6836) [![Google Scholar](https://img.shields.io/badge/Google%20Scholar-Profile-blue)](https://scholar.google.com/citations?user=w-bT-iYAAAAJ)  
---
_Last updated: 20 November 2025._
