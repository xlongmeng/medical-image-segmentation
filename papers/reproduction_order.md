# Reproduction Order

## Phase 1: Baseline Infrastructure

### 1. nnU-Net v2

Target:

- Prepare one small dataset in nnU-Net format.
- Train a 2D or 3D configuration.
- Report Dice and HD95.
- Save visual predictions and failure cases locally.

Deliverables:

- dataset conversion notes
- command log
- metric table
- 3-5 qualitative examples

### 2. Swin UNETR

Target:

- Run a MONAI-style training or inference example.
- Compare data pipeline differences against nnU-Net.

### 3. MedNeXt

Target:

- Run MedNeXt on the same dataset if feasible.
- Compare performance, memory, and training time.

## Phase 2: Promptable Medical Segmentation

### 4. MedSAM Inference

Target:

- Run inference with box prompts.
- Record prompt sensitivity.
- Compare against supervised baseline predictions.

### 5. MedSAM Fine-Tuning

Target:

- Fine-tune on a small target dataset.
- Compare frozen and fine-tuned behavior.

## Phase 3: Pathology and Microscopy

### 6. micro-SAM

Target:

- Run interactive or automatic microscopy segmentation.
- Evaluate annotation workflow speed and failure modes.

### 7. CellViT

Target:

- Run nuclei/cell segmentation.
- Extract cell-level features for downstream tissue-state analysis.

## Phase 4: Large Medical Foundation Models

### 8. VISTA3D, SAT, BiomedParse

Target:

- Start with inference demos and model behavior analysis.
- Avoid full training unless there is a clear research need and enough compute.
