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

