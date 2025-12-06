# Deforestation_Detection
For the second assignment for the course "Artificial Intelligence for Sustainable Development", the Deforestation Detection paper (David, J.; Ce, Z.) will be used as baseline and attention-based U-Net will be transferred to new contexts.


# ----------------------------------------------------------------
# 1: Replicate the baseline AI methodology using the open dataset
# -----------------------------------------------------------------
## Project Overview
Replication of attention-mechanism U-Net for deforestation detection.
See `1_Replication.ipynb` for complete replication process.

Original repository: https://github.com/davej23/attention-mechanism-unet => Cloned in a submap: 'attention_unet'

## System Requirements
- Operating System: Windows 11
- Python Version: 3.11
- Conda version: 25.5.1
- Hardware: GPU-backed Jupyter Notebook (AWS) -> used for training the Attention U-Net models.

## Environment Setup
### Step 1: Create Conda Environment
```bash
conda create -n deforestation python=3.11 -y
conda activate deforestation
```

### Step 2: Installed Dependencies
Started with installing the dependencies of original repo:  `install -r requirements.txt`
Some packages were depreciated and thus replaced.
All dependencies finally used and installed are exported and documented in `environment.yml`.


## Platform-specific issues
- Original requirements.txt had issues:`sklearn` -> changed to `scikit-learn`
- Keras and Tensorflow Version Incompatibility
    - Original paper uses Keras 2.X, and tesorflow 2.15, while modern setup uses Keras 3.X and tensorflow 2.19. This resulted in some depreciated functions (e.g. K.init_shape(x) -> replaced to x.shape)


## Results
xxx table


# ----------------------------------------------------------------
# 2. Identify a local chalenge
# -----------------------------------------------------------------
See `2_Local_Challenge.ipynb` for more information on the chosen challenge and its SDG alignment.


# ----------------------------------------------------------------
# 3. Dataset Curation
# -----------------------------------------------------------------
See `3_Dataset_Curation.ipynb` for more information onhe dataset, the collection process, its limitation and the preprocessing pipeline.

