**Lightweight Latent Generative Modeling for Efficient Time Series Augmentation (L-GTA)**
- Project Overview:
The Need for Lightweight Modeling
L-GTA: A lightweight latent generative model utilizing 1D CNN and GRU for efficient time series data augmentation and synthesis.
Architectures."Our primary goal was to solve a critical bottleneck in time series augmentation: the high computational cost of the original L-GTA framework, which used a powerful but demanding Transformer model.
- Our Innovation:
The CNN-GRU HybridWe successfully made the framework lightweight and highly efficient by replacing the resource-intensive Transformer encoder with a streamlined, hybrid architecture: an optimized blend of a 1D Convolutional Neural Network (CNN) and a Gated Recurrent Unit (GRU).
This key change allowed us to:
**Drastically Reduce Complexity:** Significantly cut down the parameter count and memory use.
**Maintain Fidelity:** Keep the framework's ability to model complex temporal behavior accurately.
**Achieve Scalability:** Make the training and deployment much faster and accessible for typical hardware resources.
**- Repository Contents**
This project is organized logically for easy review and reproduction of results.
- Directory and Content Discription:

1. src/	Source Code: Contains the core Python scripts for the framework, including the implementation of the 1D_CNN_GRU_VAE.py model and the training/testing pipeline.
2. notebooks/	Experimentation: Contains Jupyter notebooks used for initial data analysis, model fine-tuning, and generating the specific figures and plots included in the paper.
3. docs/	Documentation: Includes the final main.tex source file, the bibliography (mybibfile.bib), all generated figures (ml4.jpeg, etc.), and the final compiled PDF paper submission.

**Getting Started**
1. Environment Setup
All required Python libraries are listed in requirements.txt. Install them using a virtual environment for best practice:

- Bash
pip install -r requirements.txt

2. Data Access
The large time series dataset used in the paper is hosted externally.

3. Running the Framework
To reproduce the model training and evaluate the performance of the lightweight augmentation, execute the main script:

**Paper and Citation**
The complete paper, which details the architectural changes and computational benefits, is available in the docs/ folder.

Final PDF: docs/L-GTA-IEEE-Paper.pdf

**Contact**
Author/Maintainer: Ghania, Samia, and Laraib

GitHub: @ghania68-Ab

- Email: 
ghaniaqureshi68@gmail.com
samiashahzad010gmail.com
