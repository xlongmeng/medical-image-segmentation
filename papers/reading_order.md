# Reading Order

## Stage 0: Prerequisites

1. U-Net
2. Dice loss and Dice score
3. Hausdorff distance and HD95
4. Sliding-window inference
5. Cross-validation in medical segmentation

## Stage 1: Core Segmentation Systems

1. nnU-Net
2. nnU-Net v2
3. MedNeXt
4. Swin UNETR

Expected outcome:

- Understand the standard supervised segmentation pipeline.
- Be able to prepare a dataset in nnU-Net format.
- Be able to compare 2D, 3D full-resolution, and cascade-style training.

## Stage 2: Medical Foundation Models

1. SAM
2. MedSAM
3. VISTA3D
4. SAT
5. BiomedParse

Expected outcome:

- Understand promptable segmentation.
- Distinguish point, box, mask, and text prompts.
- Evaluate zero-shot and fine-tuned behavior separately.

## Stage 3: Pathology and Microscopy

1. CellViT
2. micro-SAM / μSAM
3. Pathology-specific SAM variants
4. Pathology text-prompt segmentation

Expected outcome:

- Segment nuclei, cells, tissue compartments, and tumor microenvironment regions.
- Convert segmentation maps into structured features for downstream analysis.
