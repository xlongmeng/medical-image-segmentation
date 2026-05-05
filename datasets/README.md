# Datasets

This folder stores dataset instructions and small metadata only.

Raw data and processed data are ignored by git. Put large files under local paths such as:

```text
datasets/raw/
datasets/processed/
```

Do not commit medical images, masks, checkpoints, or generated predictions.

## Candidate Starter Datasets

Choose one dataset first rather than downloading many at once.

| Dataset | Modality | Task | Why Useful |
|---|---|---|---|
| Medical Segmentation Decathlon subset | CT/MRI | organ/tumor segmentation | standard nnU-Net-style practice |
| ACDC | cardiac MRI | ventricle/myocardium segmentation | small and friendly for first runs |
| BraTS subset | brain MRI | tumor segmentation | common 3D benchmark |
| MoNuSeg | pathology | nuclei segmentation | relevant to pathology direction |
| PanNuke | pathology | nuclei segmentation/classification | useful for CellViT-like work |

## Dataset Card Template

Create one file per dataset in this folder, for example `datasets/acdc.md`.

```markdown
# Dataset Name

## Source

## License and Access

## Task

## Modalities

## Labels

## Local Path

## Conversion Notes

## Splits

## Known Issues
```
