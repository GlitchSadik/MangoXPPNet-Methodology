# MangoXPPNet — Official Implementation

This repository contains the original Jupyter Notebooks for the MangoXPPNet architecture and its comparative baseline experiments, as presented in our Q1 journal manuscript.

## Repository Structure
- `MangoLeafBD/` — MangoXPPNet proposed model + AlexNet, VGG16, VGG19, ResNet50 baselines, multi-backbone runner, and ROC/AUC analysis
- `MangoPest/` — Cross-dataset evaluation of MangoXPPNet on MangoPest dataset
- `MLDID/` — Cross-dataset evaluation of MangoXPPNet on MLDID dataset

## Datasets
Raw datasets are NOT included due to size and licensing. Please download them from the official sources below:

1. **MangoLeafBD**
   - Ahmed et al. *Data in Brief* 47 (2023): 108941.
   - DOI: [https://doi.org/10.1016/j.dib.2023.108941](https://doi.org/10.1016/j.dib.2023.108941)

2. **MangoPest (Dataset for pest classification in Mango farms from Indonesia)**
   - Kusrini et al. *Mendeley Data* (2020).
   - DOI: [https://doi.org/10.17632/94jf97jzc8.1](https://doi.org/10.17632/94jf97jzc8.1)

3. **MLDID (Mango Leaf Disease Identification Dataset)**
   - Rahman et al. *Mendeley Data* (2024).
   - DOI: [https://doi.org/10.17632/JPWTPV2C4S.1](https://doi.org/10.17632/JPWTPV2C4S.1)

## Setup and Usage
1. Download and extract the respective dataset(s) into your local environment.
2. Open the desired notebook (e.g. `proposed_mangoxppnet.ipynb` inside any of the dataset folders).
3. Update the path variable in the configuration block to point to your local dataset directory.
4. Run all cells to reproduce training, evaluation, and visualizations.
