# Rib Segmentation and Sequential Labeling

Research project on automatic rib segmentation and anatomical labeling from chest CT using multi-axial slicing and 3D reconstruction.

## Related publications

- *Automatic Rib segmentation and sequential labeling via Multi-axial slicing and 3D reconstruction* — Applied Intelligence, September 2024.
- *Rib segmentation and sequence labeling via biaxial slicing and 3D reconstruction* — IMCOM, January 2024.

## Notebook workflow

1. Prepare CT inputs with [Segmentation_Preprocessing.ipynb](Segmentation_Preprocessing.ipynb).
2. Train the segmentation model with [Segmentation_train.ipynb](Segmentation_train.ipynb).
3. Run validation and testing with [Segmentation_validate and test.ipynb](Segmentation_validate%20and%20test.ipynb), then inspect [Segmentation_evaluation.ipynb](Segmentation_evaluation.ipynb).
4. Use [Rib_Numbering_Final.ipynb](Rib_Numbering_Final.ipynb) for sequential rib labeling.

Open the notebooks in Jupyter and review the input paths and dependencies before running them. The repository contains the notebooks. CT data, model weights, and a pinned environment are not included.
