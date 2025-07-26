# Inference-and-Evaluation-of-MedSAM-2-on-Brain-Tumor-Segmentation-BRATS-2019-
This task aims to explore and evaluate the performance of MedSAM-2 for medical image segmentation using the BRATS 2019 dataset. MedSAM-2 reframes 2D/3D segmentation as a video object tracking task . The end goal is to gain insights into its generalization capability, especially in segmenting brain tumor subregions.
Key Features
Multi-modal MRI processing (T1/T1CE/T2/FLAIR)

Slice-by-slice inference with memory propagation

Quantitative metrics (Dice, IoU, HD95)

Integrated visualization tools

Results
Region	Dice	IoU
WT	0.85	0.74
TC	0.78	0.64
ET	0.71	0.55
Structure
text
.
├── inference.ipynb    # Colab notebook
├── evaluate.py        # Evaluation script
├── checkpoints/       # Model weights
└── results/           # Outputs
