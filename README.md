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

## Environment Setup
### Step 1: Create Conda Environment
```bash
conda create -n deforestation python=3.11 -y
conda activate deforestation
```

### Step 2: Install Dependencies
```bash
cd attention_unet
pip install -r requirements.txt
```
Note: Original requirements.txt had issues:
- `PIL` → changed to `Pillow`
- `sklearn` → changed to `scikit-learn`

## Dependencies
See `requirements_working.txt` for full list of installed packages. 


## Results
- Baseline accuracy: XX%
- Our reproduction: YY%
- Difference: ±Z%