# README

## Overview

This repository contains Jupyter notebooks for **ATML PA1** tasks. Each notebook corresponds to specific parts of the assignment:

* **Task 1** → `24280051_24280057_ATML_PA1_Task_1.ipynb`
* **Tasks 2 & 3** → `24280051_24280057_PA1_Task2,3.ipynb`

The notebooks are self-contained and include steps for dataset loading, model training, and evaluation.

---

## Requirements

Before running the notebooks, ensure the following are available:

* Python 3.8+
* Jupyter Notebook or JupyterLab
* Required Python libraries:

  * `torch`
  * `torchvision`
  * `timm`
  * `numpy`
  * `matplotlib`
  * `tqdm`

---

## Running the Notebooks

1. **Open in Canvas**
   Upload the notebooks to Canvas or open them directly in the provided environment.

2. **Set Kernel**
   Use a Python kernel with PyTorch installed.

3. **Run Cells Sequentially**
   Execute cells from top to bottom in order. The notebooks are structured so that imports, dataset preparation, and models are defined before training and evaluation.

4. **Outputs**

   * Training logs and evaluation metrics will display in the notebook.
   * Accuracy/loss plots will render inline.

---

## Notes

* Code is reproducible: running the notebooks top-to-bottom should work without edits.
* If GPU is available, it will be used automatically; otherwise, execution falls back to CPU.
* Datasets (CIFAR-10, STL-10, etc.) will download automatically on first run through `torchvision`.
