# Replication Package

This repository contains the replication package for the study:

> **Emerging Challenges in Threat Modeling for GenAI-Augmented Systems: A View from the Trenches**

**ABSTRACT**: _Threat modeling remains a central task in secure software engineering, as it enables the identification of security issues from system architectures. As Generative Artificial Intelligence (GenAI) becomes increasingly pervasive across software systems, traditional threat modeling methods (e.g., STRIDE) are insufficient to assess emerging GenAI-specific risks. In this work, we present the first results from an exploratory assessment of GenAI-aware threat modeling methods in a Small and Medium Enterprise (SME) setting. For this, we conducted a rapid literature review to select relevant techniques and systematically applied three shortlisted methods to an industrial case study involving a GenAI-augmented system. The results highlight differences in the threats identified by each technique and reveal limited support for certain GenAI-specific risk categories, particularly those related to software supply chains and human-centered security issues. We further report practitioners' perceptions of the usability and integration of these methods in SME development workflows, including their perceived effort and adoption challenges._

## Repository Structure

```text
.
├── 1_Automated_Search/
│   └── Search queries and raw/exported search results from the RLR.
│
├── 2_First_Screening/
│   └── Materials and results from the first screening phase.
│
├── 3_Second_Screening/
│   └── Materials and results from the second screening phase.
│
├── 4_Thematic_Analysis/
│   └── Coding and thematic analysis artifacts used to characterize the selected studies.
│
├── 5_Method_Comparison/
│   └── Comparison of the selected threat modeling methods and OWASP Top-10 for LLMs mapping.
│
├── 6_Executive_Report/
│   └── Materials related to the executive report shared with the SME development team.
│
└── 7_Survey/
    └── Survey instrument and aggregated practitioner survey results.
