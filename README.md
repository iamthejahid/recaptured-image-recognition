Deep Learning-Based Recognition of Recaptured Images for Digital Media Authentication
Paper ID: 1595 — ICCIT 2025

This repository contains the complete source code and dataset access link for the research paper:

“Deep Learning-Based Recognition of Recaptured Images for Digital Media Authentication”
Accepted at the 28th International Conference on Computer and Information Technology (ICCIT 2025).

GitHub storage limits prevent uploading the full dataset (≈6 GB), so it is hosted separately on Google Drive.
All scripts included here exactly reproduce the experiments, evaluation, and figures used in the paper.

📁 Repository Structure
/
├── code_RGB
│   ├── RGB_recapture_dataset_DenseNet201.ipynb
│   ├── RGB_recapture_dataset_InceptionV3.ipynb
│   └── RGB_recapture_dataset_Xception.ipynb
├── code_canny
│   ├── canny_recapture_dataset_DenseNet201.ipynb
│   ├── canny_recapture_dataset_InceptionV3.ipynb
│   └── canny_recapture_dataset_Xception.ipynb
└── recapture_dataset   # Not complete dataset. Find full dataset from the drive link.
    ├── original
    └── recapture 
│   
│
└── README.md           # Documentation (this file)

📦 Full Dataset Download (6+ GB)

The complete dataset used in our experiments is publicly available here:

👉 Google Drive (Public Access):
https://drive.google.com/drive/folders/1yS5EGEMTEV4ip1nyvYB2H2Y7JTNOpa_c

The dataset includes:

Authentic images

Recaptured images (multiple devices, screens, lighting conditions)

Canny-edge processed frames

Train/test split as used in the paper

Metadata + annotation files

GitHub’s 100MB-per-file limit and overall repo size limit prevent hosting it here.


📬 Contact

For questions or replication assistance:

Jahidul Islam
Email: jahid.info97@gmail.com
