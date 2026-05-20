# Temple of Debod 3D Reconstruction

This repository contains the final assets for a 3D reconstruction project of the Temple of Debod.

The project combines photogrammetry and neural rendering workflows, including COLMAP sparse reconstruction, Gaussian Splatting visualization, and a final mesh extraction generated with SuGaR.

## Repository structure

```text
templo_debod_3D/
├── 03_gaussian_splat/
│   └── splat.ply
├── 01_dataset/
├── 02_colmap/
├── 04_mesh_SuGaR/
│   ├── sugarfine_3Dgs7000_density.obj
│   ├── sugarfine_3Dgs7000_density.mtl
│   └── sugarfine_3Dgs7000.png
├── 05_results/
└── README.md

```
# 3D Reconstruction Pipeline Results

## Main Results
* **Sparse reconstruction** generated with COLMAP.
* **Gaussian Splatting representation** exported as `.ply`.
* **Mesh** generated with SuGaR from the Gaussian Splatting output.
* **Final mesh files** include `.obj`, `.mtl`, and texture `.png`.

## Tools Used
* **COLMAP**
* **3D Gaussian Splatting**
* **SuGaR**
* **CloudCompare / MeshLab** (for visualization)

## Visual results

The folder `05_results/` contains rendered images and screenshots of the main outputs about the reconstruction pipeline, including:

- COLMAP sparse reconstruction
- Gaussian Splatting visualization
- Final mesh visualization

## Notes
* Some large 3D assets are tracked using **Git LFS**.
* The final mesh is intended as a reconstruction proof of concept, not as a production-ready 3D asset.

## Author
* **Yulicenia Diaz Cabrera**
