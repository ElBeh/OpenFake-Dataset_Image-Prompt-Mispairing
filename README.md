# OpenFake Dataset - Image-Prompt Mispairing Report
Two Notebooks to demonstrate the mispairing of some models in the dataset.

## Critical Issue
Systematic image-prompt mispairing affecting multiple models in the [OpenFake dataset](https://huggingface.co/datasets/ComplexDataLab/OpenFake).

## Findings
- **12 verified mislabeled samples** across 4 models
- ** almost 100% mismatch rate** when filtering by affected models
- **Affected models:** flux.1-dev, sd-3.5, sdxl-realvis-v5, sd-1.5-dreamshaper
- **Other models appear correct**

## Verification

### Specific Samples
See [`notebooks/01_specific_samples_verification.ipynb`](notebooks/OpenFake_Image_Prompt_Mispairing.ipynb)
- Documents 12 specific examples with screenshots
- Shows complete mismatch between images and prompts

### Systematic Check
See [`notebooks/02_systematic_model_check.ipynb`](notebooks/02_systematic_model_check.ipynb)
- Verifies first 10 samples per affected model
- Confirms 100% error rate for these models

## Related Discussion
[Link zur HuggingFace Discussion - wird ergänzt]

## Dataset Indexing Note
HuggingFace viewer uses 1-based indexing, programmatic access is 0-based.
