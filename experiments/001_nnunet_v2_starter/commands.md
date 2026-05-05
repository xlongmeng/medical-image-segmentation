# 001 nnU-Net v2 Starter

## Goal

Run nnU-Net v2 on one small dataset and document the full path from raw data to metric table.

## Commands

Fill this section after choosing the first dataset.

```bash
# Example placeholders
nnUNetv2_plan_and_preprocess -d DATASET_ID --verify_dataset_integrity
nnUNetv2_train DATASET_ID 3d_fullres 0
nnUNetv2_predict -i INPUT_DIR -o OUTPUT_DIR -d DATASET_ID -c 3d_fullres -f 0
```
