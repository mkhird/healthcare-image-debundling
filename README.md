# healthcare-image-debundling

Python-driven image privacy pipeline for healthcare and sensitive facilities. Supports automated face blurring, POI-guided manual redaction, and dataset rebundling to protect patient-identifiable information while preserving accurate site models.

## Pipeline Overview

This repository documents a multi-stage workflow designed to support privacy-preserving image processing in regulated environments.

The pipeline includes:
- Optional pre-processing with automated face blurring
- Dataset ingestion and model generation
- POI-based identification of sensitive content
- Targeted panorama extraction for manual blurring
- Rebundling and redeployment of sanitized datasets

For a step-by-step explanation of the processing workflow, see:
👉 **[Workflow Overview](docs/workflow_overview.md)**

## Repository Structure

## Pipeline Screenshots

### POI-Based Blurring Workflow
![POI Tagging](docs/screenshots/poi_tagging_example.![POI tagging example ](https://github.com/user-attachments/assets/d6616424-0232-433e-9070-d42d43eee3b1)
png)

### Panorama Redaction
![Before and After Blurring](docs/screenshots/panorama_before_after.png)
![Panos before](https://github.com/user-attachments/assets/75a0f6f3-e2c2-4ebf-bf6e-227bcdb0d806)
![Panos blurred after](https://github.com/user-attachments/assets/033ecc0b-7e35-4a56-b2d1-70c6398a063e)
