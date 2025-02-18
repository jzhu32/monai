# MONAI Medical Image Classifier

## Overview
This repository contains code and resources for working with [MONAI](https://monai.io/), the Medical Open Network for AI. MONAI is a PyTorch-based framework designed for deep learning in healthcare imaging applications.

## Installation
To ensure MONAI and required dependencies are installed, run the following commands:

```bash
!python -c "import monai" || pip install -q "monai-weekly[pillow, tqdm]"
!python -c "import matplotlib" || pip install -q matplotlib
%matplotlib inline
```

## Features
- Provides domain-specific tools for medical imaging AI.
- Supports data augmentation, pre-processing, and deep learning model development.
- Compatible with PyTorch and integrates with Ignite for training workflows.

## Model Deployment
The trained MONAI medical image classification model has been deployed on **Hugging Face Spaces**. You can interact with the model at the following link:

🔗 **[MONAI Medical Classifier - Hugging Face Spaces](https://huggingface.co/spaces/josefzhu/monai-medical-classifier)**

The source code for this deployment can be found in the repository:

🔗 **[Hugging Face Repository](https://huggingface.co/spaces/josefzhu/monai-medical-classifier/tree/main)**

## Usage
Refer to the official [MONAI documentation](https://docs.monai.io/) for details on how to use MONAI in your projects. Additional tutorials are available on GitHub:

🔗 **[MONAI Tutorials](https://github.com/Project-MONAI/tutorials/tree/main/2d_classification)**

## Files in This Repository
- `.gitattributes` - Configuration for Git LFS.
- `README.md` - This documentation file.
- `app.py` - The Gradio application for interacting with the model.
- `model_scripted.pt` - The trained model stored using Git LFS.
- `requirements.txt` - Dependencies required for running the application.

---
For any issues or improvements, feel free to contact me at **diz4009@med.cornell.edu** 



