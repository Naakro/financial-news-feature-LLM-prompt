# Prompt for Financial News Feature Analysis using LLM (GPT-4)

## Context
This prompt was designed as part of a research study focused on analyzing the *financial news feature* in personal finance applications. The goal is to identify common dimensions used in designing and implementing financial news functionalities that support user decision-making and financial literacy.

The prompts were submitted to a Large Language Model (LLM), specifically GPT-4, as part of a Feature-Oriented Competitor Analysis (FOCA) method.

---

## Prompt 1 – Dimension Discovery

"You are an AI assistant that helps analyze features in personal finance applications.  
Please identify and explain the key dimensions typically found in financial news features within personal finance apps."

---

## Prompt 2 – Relevance and Completeness Evaluation

"Evaluate the relevance and sufficiency of the following dimensions for financial news features:  
- Content Presentation Format  
- News Source  
- Frequency and Update Mechanism  
- Topic Personalization  
- Integration with Other App Features  

Suggest any additional dimensions if applicable."

---

## Prompt 3 – Identifying Competitor Applications with Financial News Features

Please recommend 5 global and 5 Indonesian personal finance applications available on the Google Play Store or Apple App Store that:

- Include financial news, market updates, or economic insights as part of their features (either explicitly or implicitly),
- Can be categorized under budgeting, investing, or digital banking apps,
- Are popular (e.g., downloaded at least 1 million times or have a significant user base),
- Provide relevant value for users looking to stay informed about economic or financial topics through their app.

Please format the result in a table with the following columns:

- App Name  
- Region (Global or Indonesia)  
- Financial News Feature (Yes/No)  
- Key News Functionality  
- Estimated Installs (if available)

## Prompt 4 – Feature Decomposition into Sub-Features

Feature
{feature}: {feature_description}

Given the mobile app feature above, please refine it to a list of subfeatures.
Ensure that the number of sub-features is {n}.
The output should be a list of JSON formatted objects like this:
[{ "sub-feature": sub-feature, "description": description }]

### Prompt



## Notes

These prompts were used to guide LLM-driven exploration and validation of design dimensions for financial news features. The resulting insights supported the feature analysis and development of the *Atur Duit* application.
For reproducibility and citation purposes, this file is published in a public GitHub repository.

---
**Author:** Naufal Akmal Rosaidia  
**Date:** 2025 

