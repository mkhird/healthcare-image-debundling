# Workflow Overview

This repository documents a privacy-preserving image processing pipeline designed for healthcare and sensitive environments.

## High-Level Flow

1. **Initial Data Upload**
   Raw camera data is uploaded to a controlled environment and archived for traceability.

2. **Pre-Processing (Optional)**
   Raw imagery is converted to JPG and passed through automated face blurring before downstream ingestion.

3. **Model Processing**
   Sanitized imagery is uploaded for dataset alignment, bundling, and site model generation.

4. **POI Tagging**
   Sensitive elements are tagged using Points of Interest (POIs) to enable targeted redaction.

5. **Manual Blurring**
   Panorama images near tagged POIs are extracted, manually blurred, and replaced.

6. **Rebundling & Delivery**
   Updated imagery is rebundled and redeployed, ensuring only sanitized data remains.

This separation of automated and manual steps supports flexibility, auditability, and compliance-driven workflows.
