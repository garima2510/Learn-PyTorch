# PyTorch for Deep Learning: My Learning Notes

This repo has my lab work and notes from the
[PyTorch for Deep Learning Professional Certificate](https://www.deeplearning.ai/specializations/pytorch-for-deep-learning-professional-certificate)
by [DeepLearning.AI](https://www.deeplearning.ai/).

## Contents

| Module | Lab | Topic |
|--------|-----|-------|
| [mod-1](mod-1/) | [C1_M1_Lab_1_simple_nn.ipynb](mod-1/C1_M1_Lab_1_simple_nn.ipynb) | Building and training a single-neuron network (`nn.Linear`) to predict delivery times, then seeing where a linear model fails on non-linear data |

## Getting started

Requirements: Python 3.10+ (developed on Python 3.14).

```powershell
# Create and activate a virtual environment
python -m venv .venv
.venv\Scripts\Activate.ps1        # Windows
# source .venv/bin/activate       # macOS / Linux

# Install dependencies
pip install -r requirements.txt
```

Then open a notebook in VS Code or Jupyter and choose the `.venv` kernel. Each module folder has its own `helper_utils.py`, so run the notebooks from inside their module folder.

## Project structure

```
.
├── mod-1/
│   ├── C1_M1_Lab_1_simple_nn.ipynb   # Lab: simple neural network
│   └── helper_utils.py               # Plotting helpers used by the lab
├── requirements.txt
└── README.md
```

## Acknowledgements

The course content, lab structure and helper utilities come from the
[PyTorch for Deep Learning Professional Certificate](https://www.deeplearning.ai/specializations/pytorch-for-deep-learning-professional-certificate)
by DeepLearning.AI. This repository is a personal learning log and is not affiliated with or endorsed by DeepLearning.AI.
