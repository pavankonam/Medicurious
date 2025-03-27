# Medicurious: An LLM for Medical Insights

## Overview
Medicurious is a Large Language Model (LLM) developed to simplify access to reliable medical information in an era of abundant yet overwhelming data. This project aims to empower doctors and healthcare professionals by providing a specialized AI tool tailored for medical insights, addressing the limitations of general-purpose models like GPT-40 in the medical domain.

## Motivation
As the quote states: *"AI will not replace doctors, but doctors who use AI will replace those who don't."* Medicurious is built to enhance medical decision-making, not replace it, by offering structured, accurate, and actionable information.

## Project Goal
The objective is to create an LLM that integrates diverse medical data sources, processes them into a unified format, and delivers reliable insights for healthcare applications.

## Data Sources
- **Medication Guides**: CSV files containing drug information (Drug Name, Active Ingredient, Form/Route, Date, URL).
- **Drug Safety Database**: Detailed data on approved prescription drugs.
- **Symptom-Diagnosis Dataset**: Combinations of symptoms and corresponding diagnoses.
- **Clinical Guidelines**: General guidelines for medicine and treatment plans.

## Data Preprocessing
### Step-by-Step Transformation
1. **Medication Guides CSV Processing**:
   - Load, clean, and extract relevant columns from CSV files.
2. **Initial Data Combination**:
   - Merge symptom-diagnosis and medication data into a unified JSONL format.
3. **Drug Safety Data Normalization**:
   - Clean and standardize entries from the drug safety database.

## Repository Contents
- **PDF Document**: Overview of Medicurious, including its purpose, data sources, and preprocessing steps.
- **Code**: Scripts for data preprocessing and transformation (to be uploaded).
- **Sample Data**: Examples of processed JSONL files (to be added).

## Features
- **Knowledge Representation**: Structured medical information for easy access and querying.
- **Live Demo**: Showcases Medicurious in action (details in the PDF).
- **Evaluation Criteria**: Metrics to measure performance and reliability (outlined in the PDF).

## Dependencies
- Python (for data processing and model development).
- Libraries: Pandas (data manipulation), JSON (format conversion), and others to be specified in `requirements.txt`.

## Future Work
- Enhance the LLM with additional medical datasets.
- Implement real-time query capabilities for clinical use.
- Refine evaluation criteria for broader validation.
