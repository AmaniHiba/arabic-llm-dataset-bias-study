# Ethical Audit of Arabic NLP Datasets (2015-2025)

This repository contains a curated and filtered list of Arabic NLP datasets, created as part of a PhD research project on **Responsible AI in the Arab Region**. The goal is to analyze the landscape of Arabic datasets used for LLM training, focusing on documentation, licensing, and potential biases.

## 1. Data Source
The primary source for this collection is the **Masader** catalog (developed by ARBML/BigScience), which indexes over 800 Arabic NLP datasets [1].

## 2. Filtering Criteria
From the initial catalog, we applied strict filtering criteria to select datasets suitable for quantitative ethical auditing. The filtering process resulted in **117 datasets** based on the following conditions:

* **Timeframe:** Published between **2015 and 2025**.
* **Format:** Text-only datasets (Audio/Image excluded).
* **Availability:** Must have an accessible link and a valid license field.
* **Risk Assessment:** Initial screening for "Low Bias Risk" based on Masader metadata.

## 3. Repository Contents
* `Arabic_NLP_Datasets_Audit.csv`: The cleaned and structured dataset metadata. Columns include:
    * Dataset Name
    * Year
    * Source
    * Provider
    * Task Type (Translation, QA, etc.)
    * Dialect (MSA, Mixed, Regional)
    * License
    * 
    * Paper Link
    * Hosting Platform (GitHub, Hugging Face, etc.)
    * Collection Style
    * Domain

## 4. Preliminary Findings (Descriptive Analysis)
An initial analysis of the 117 filtered datasets reveals the following distribution:

* **Dialect Representation:**
    * ~60% Modern Standard Arabic (MSA).
    * ~25% Mixed Dialects.
    * ~15% Regional Dialects (e.g., Egyptian, Gulf, Levantine).
* **Licensing:**
    * Approximately **65%** utilize open licenses (e.g., CC-BY, MIT, Apache).
    * Around **20%** carry non-commercial restrictions.
* **Hosting:** The majority of datasets are hosted on GitHub (~41%) and Hugging Face (~24%).


**References:**
[1] Areeb et al., "Masader: Metadata annotations for more than 200 Arabic NLP datasets," BigScience/ARBML.
