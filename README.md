****PROJECT TITLE****

**Lightweight Latent Generative Modeling for Efficient Time Series Augmentation (L-GTA)**

****Project Overview****

The Need for Lightweight Modeling

**L-GTA:**

A lightweight latent generative model utilizing 1D CNN and GRU for efficient time series data augmentation and synthesis.
Architectures."Our primary goal was to solve a critical bottleneck in time series augmentation: the high computational cost of the original L-GTA framework, which used a powerful but demanding Transformer model.

**Our Innovation:**

This repository houses the final work for my research on improving the Latent Generative Time Series Augmentation (L-GTA) framework.

The initial challenge with L-GTA was its use of a resource-heavy Transformer encoder, which made training slow and demanding on hardware. My goal was to make this powerful augmentation technique practical and scalable.

Our Team successfully implemented a new, lightweight architecture by replacing the Transformer with a hybrid system: an optimized "1D Convolutional Neural Network (CNN") paired with a "Gated Recurrent Unit (GRU)".

This innovation achieved the following core results:

1. _**Reduced Complexity:**_ The model now has significantly fewer parameters, lowering the computational barrier to entry.

2. _**Faster Training:**_ Training and deployment are much quicker, allowing for rapid experimentation.

3. _**High Fidelity:**_ Despite being lighter, the model maintains its ability to generate high-quality, realistic synthetic time series.


****Repository Contents****

This project is organized logically for easy review and reproduction of results.
- Directory and Content Discription:

1. **src/	Source Code**: Contains the core Python scripts for the framework, Contains the final CNN-GRU VAE model implementation and the main training/testing pipeline.
   
2. **notebooks/	Experimentation:** Jupyter notebooks used for data preparation, model tuning, and generating the specific performance visuals used in the paper.
   
3. **docs/	Documentation:** Includes the final main.tex source file, the bibliography (mybibfile.bib), all generated figures (ml4.jpeg, etc.), and the final compiled PDF paper submission.

****How to Run My Code****

1. Environment Setup
   
Clone the repository and install all dependencies listed in the requirements.txt file:
- I used Git BASH
  
_git clone https://github.com/ghania68-Ab/L-GTA-Time-Series-Augmentation.git
cd L-GTA-Time-Series-Augmentation
pip install -r requirements.txt_

2. Data Access
The large time series dataset used in the paper is hosted externally.
DataSet Link: [https://drive.google.com/drive/folders/1CHgJxzx3XQJKvHiJLs1S8UQ_-Nd006bt?usp=drive_link]

_Source Data_: We worked on Three different datasets 'Tourism, M5 Forecasting, and San Francisco Crime Classification Dataset (Processed into time series format).
_The linked folder (Colab Notebooks) contains the primary dataset file:_ L_GTA_model_DATA.npy.


**Paper and Citation**
The complete paper detailing the methodology, architectural changes, and computational results is available for your review in the docs/ directory.

**Final PDF:** `docs/L-GTA-IEEE-Paper.pdf`
**LaTeX Source Files:** `docs/main.tex` and `docs/mybibfile.bib`


**Contact**
_Authors_
Ghania Jawed, Samia Shahzad, and Laraib Ali

- Email:_ 
[ghaniaqureshi68@gmail.com]
