# Communicable Disease Surveillance in Toronto: Trends and Implications for Prevention

## Overview
Communicable disease surveillance programs can help public health agencies track changes in reported illness and plan prevention efforts around recurring seasonal patterns. This report examines Toronto’s Monthly Communicable Disease Surveillance Data from 2021 to 2025, comparing monthly case totals across six disease categories and annual influenza rates. The categories show different seasonal patterns; influenza closely follows the winter peaks in vaccine-preventable disease cases and reached an annual rate of 387.0 cases per 100,000 in 2025. These findings show how surveillance data can support monitoring across diseases and help time influenza vaccination outreach before the winter increase.  

## Structure

The repo is structured in the following way: 

**Scripts:** 
- Contains all code required to collect, clean and validate data. 
- Provides Jupyter notebook to replicate exploratory data analysis that was performed. 

**Data:**
- */raw_data:* Folder containing the raw dataset that was downloaded from Open Data Toronto 
- */processed:* Folder containing the cleaned dataset. One row represents one disease and year. 
- */synthetic_data:* Folder containing the synthetic data that was created to simluate the cleaned dataset used for analysis. 

**Paper:**
- Contains files related to the produced report including quarto document and references.

## Disclosure
Apects of the analysis code were written with support from OpenAI Codex. Similarily, Chat-GPT was used to assist in the editing and reviewing of the writing material. A history of the chats is provided in `other/llm/usage.txt`. All final code and written material was reviewed and tested by author.  