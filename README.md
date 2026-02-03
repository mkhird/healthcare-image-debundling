# healthcare-image-debundling
Python-driven image privacy pipeline for healthcare and sensitive facilities. Supports automated face blurring, POI-guided manual redaction, and NavVis bundle regeneration to protect patient-identifiable information while preserving accurate site models.
## Pipeline Overview
For a step-by-step explanation of the processing workflow, see:
[Workflow Overview](docs/workflow_overview.md)
"""
Purpose: Extract panorama images near POI coordinates for manual blurring
Inputs: NavVis dataset bundle, POI coordinates CSV
Outputs: Panorama images and coordinate references
"""
