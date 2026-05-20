# Temple of Debod 3D Reconstruction

This repository contains the final assets and documentation for a 3D reconstruction project of the Temple of Debod.

The project combines photogrammetry and neural rendering workflows, including COLMAP sparse reconstruction, Gaussian Splatting visualization, Nerfstudio outputs, and a final mesh extraction generated with SuGaR.

## Repository structure

```text
templo_debod_3D/
├── 01_gaussian_splat/
│   └── splat.ply
├── 02_nerfstudio_model/
├── 03_dataset/
├── 04_colmap/
└── 05_mesh_SuGaR/
    ├── sugarfine_3Dgs7000_density.obj
    ├── sugarfine_3Dgs7000_density.mtl
    └── sugarfine_3Dgs7000.png

```
# 3D Reconstruction Pipeline Results

## Main Results
* **Sparse reconstruction** generated with COLMAP.
* **Gaussian Splatting representation** exported as `.ply`.
* **Nerfstudio model files** used for visualization and rendering.
* **Mesh** generated with SuGaR from the Gaussian Splatting output.
* **Final mesh files** include `.obj`, `.mtl`, and texture `.png`.

## Tools Used
* **COLMAP**
* **Nerfstudio**
* **3D Gaussian Splatting**
* **SuGaR**
* **CloudCompare / MeshLab** (for visualization)

## Visual results

The folder `06_results_screenshots/` contains screenshots of the main outputs of the reconstruction pipeline, including:

- COLMAP sparse reconstruction
- Gaussian Splatting visualization
- Nerfstudio render
- SuGaR mesh extraction
- Final mesh visualization

## Notes
* Some large 3D assets are tracked using **Git LFS**.

## Author
* **Yulicenia Diaz Cabrera**

## Final preview

![Final reconstruction preview](gaussian_splat_view.jpg)