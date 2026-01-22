# 🧬 Bibliometric Landscape of Cytoneme Research

![Status](https://img.shields.io/badge/Status-Active-success)
![Method](https://img.shields.io/badge/Method-Bibliometrics-orange)

## 📌 Overview
This project presents a comprehensive bibliometric analysis of the research landscape surrounding **cytonemes** (signaling filopodia). By leveraging metadata from major scientific databases, this repository maps the historical evolution, thematic clusters, and collaborative networks that define this niche field of developmental biology.

---

## ⚙️ Methodological Framework

### 1. Data Acquisition
**Database:** [Scopus / Web of Science / PubMed] Core Collection  
**Search Date:** [Insert Date]

The search strategy targeted the **Title, Abstract, and Keywords** fields to capture the full spectrum of terminology used since the discovery of cytonemes.

**Search Query:**
> ("cytoneme*" OR "signaling filopodia" OR "signaling protrusions")
> AND
> ("signaling" OR "morphogen" OR "transport" OR "development")

### 2. Selection Criteria
To ensure data quality and relevance, the following filters were applied during the screening process:

| Criterion | Inclusion | Exclusion |
| :--- | :--- | :--- |
| **Timespan** | 1999 — Present | Pre-1999 records |
| **Document Type** | Articles, Reviews | Editorials, Errata, Abstracts |
| **Language** | English | Non-English text |

### 3. Computational Environment
The analysis relies on a combination of Python scripting for data processing and specialized bibliometric software for network visualization.

* **Python (v3.10) & Pandas:** Used for data cleaning, deduplication, and pre-processing.
* **VOSviewer (v1.6.20):** Utilized for co-occurrence and co-authorship network visualization (using fractional counting).
* **Bibliometrix (R-Package):** Employed for statistical performance indicators (Growth rate, H-index).

---

## 📚 Thesaurus & Data Normalization

*> This section details the semantic mapping used to standardize keywords and resolve synonyms.*

[... Section to be completed by the author ...]

---
