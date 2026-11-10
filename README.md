# PyTorch for Deep Learning: My Learning Notes

This repo has my lab work and notes from the
[PyTorch for Deep Learning Professional Certificate](https://www.deeplearning.ai/specializations/pytorch-for-deep-learning-professional-certificate)
by [DeepLearning.AI](https://www.deeplearning.ai/).

## Contents

### Course 1

| Module | Lab | Topic |
|--------|-----|-------|
| [mod-1](course-1/mod-1/) | [Lab 1: Simple neural network](course-1/mod-1/m1-l1/C1_M1_Lab_1_simple_nn.ipynb) | Building and training a single-neuron network (`nn.Linear`) to predict delivery times, then seeing where a linear model fails on non-linear data |
| [mod-1](course-1/mod-1/) | [Lab 2: Activation functions](course-1/mod-1/m1-l2/C1_M1_Lab_2_activation_functions.ipynb) | Standardizing the data and adding a ReLU activation so the network can learn the curved bike + car delivery-time pattern |

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

Then open a notebook in VS Code or Jupyter and choose the `.venv` kernel. Each lab folder has its own `helper_utils.py`, so run the notebooks from inside their lab folder.

## Project structure

```
.
├── course-1/
│   ├── mod-1/
│   │   ├── m1-l1/
│   │   │   ├── C1_M1_Lab_1_simple_nn.ipynb             # Lab 1: simple neural network
│   │   │   └── helper_utils.py                         # Helpers used by the lab
│   │   └── m1-l2/
│   │       ├── C1_M1_Lab_2_activation_functions.ipynb  # Lab 2: ReLU activation
│   │       └── helper_utils.py                         # Helpers used by the lab
│   └── slides/                                         # Course slides (local only, git-ignored)
├── requirements.txt
└── README.md
```

> **Note:** Course slides are kept locally for reference only. Any `slides/` folder, at any depth, is excluded by `.gitignore` and is not pushed to GitHub.

## Acknowledgements

The course content, lab structure, slides and helper utilities come from the
[PyTorch for Deep Learning Professional Certificate](https://www.deeplearning.ai/specializations/pytorch-for-deep-learning-professional-certificate)
by DeepLearning.AI. This repository is a personal learning log and is not affiliated with or endorsed by DeepLearning.AI.