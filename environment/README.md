# Environment Notes

Do not force one giant environment for all papers. Many reproduction repositories have conflicting dependencies.

Recommended approach:

1. Keep a small base environment for this lab repo.
2. Use separate environments for nnU-Net, MONAI/Swin UNETR, MedSAM, CellViT, and micro-SAM when needed.
3. Record exact setup commands in each experiment folder.

## Base Environment

Minimal packages for local utilities:

```bash
pip install numpy scipy pandas matplotlib scikit-image SimpleITK nibabel
```

Install method-specific dependencies only when starting that reproduction.
