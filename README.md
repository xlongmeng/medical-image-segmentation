# Medical Image Segmentation

A lightweight study and reproduction workspace for medical image segmentation papers, baselines, and foundation models.

This repository tracks papers, official code links, reproduction notes, dataset instructions, experiment configs, and research logs. It should not store raw medical datasets, checkpoints, pretrained weights, or large generated outputs.

## Goals

- Build core medical image segmentation skills: preprocessing, 2D/3D training, sliding-window inference, Dice, HD95, and cross-validation.
- Reproduce strong supervised baselines before moving to medical foundation models.
- Study promptable and text-guided segmentation methods such as MedSAM, VISTA3D, SAT, and BiomedParse.
- Connect pathology segmentation outputs with downstream tissue-state and gene-expression prediction research.

## Learning Stages

### Stage 1: Core Medical Segmentation

1. U-Net
2. nnU-Net v2
3. MedNeXt
4. Swin UNETR

Focus on data format, preprocessing, 3D patch training, evaluation metrics, and reliable baselines.

### Stage 2: Medical Foundation Models

1. SAM
2. MedSAM
3. VISTA3D
4. SAT
5. BiomedParse

Focus on point prompts, box prompts, text prompts, interactive segmentation, zero-shot transfer, and domain adaptation.

### Stage 3: Pathology and Microscopy

1. CellViT
2. micro-SAM / μSAM
3. pathology-specific SAM variants
4. pathology text-prompt segmentation

Focus on nuclei segmentation, tissue compartment segmentation, tumor/stroma/immune regions, and structured features for downstream biological prediction.

## Repository Layout

```text
papers/          Reading order, paper notes, and official code links.
datasets/        Dataset cards and local data instructions. Large data is ignored.
configs/         Dataset and experiment configuration templates.
experiments/     Per-method reproduction logs and result summaries.
reports/         Reproducibility logs and research summaries.
environment/     Environment setup notes.
scripts/         Small helper scripts later, if needed.
```

## Large File Policy

Do not commit:

- raw datasets
- processed medical images
- model checkpoints
- pretrained weights
- generated predictions
- large logs or exported media

Use local storage for heavy files and keep only metadata, instructions, and small examples in this repository.

## First Milestone

Reproduce nnU-Net v2 on one small public dataset, document the conversion process, and report Dice/HD95 with several visual failure cases.
