# QSW_Quantum_Visualization

## Overview

This repository contains **all the plots and code** in the respective `.ipynb` files that were used in the IEEE QSW Conference paper submission 10.

* **`Lagos_Class3.ipynb`** contains all the plots for the images belonging to **class 3** of the MNIST image set, generated on the IBM Quantum machine **Lagos**.
* **`Perth_Class9.ipynb`** contains all the plots for the images belonging to **class 9** of the MNIST image set, generated on the IBM Quantum machine **Perth**.

The file **`quantum_vis_methodology.png`** provides the methodology figure used in the accompanying paper.

### Data

The **`data/`** folder holds **all the datasets** used by every notebook in this repository.

---

## Environment setup

Choose **one** of the following workflows:

| Workflow  | When to use                                                                             | Quick start                                                                            |
| --------- | --------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------- |
| **Conda** | You need to create a conda environment that enables cross‑platform binary dependencies. | `conda env create -f config.yaml`                                                      |
| **Pip**   | You’re working in a pure‑Python, pip‑only workflow.                                     | `python -m venv .venv && source .venv/bin/activate && pip install -r requirements.txt` |

> **Tip**   `config.yaml` describes the full conda environment, while `requirements.txt` lists only Python‑level requirements.

---

## Usage

1. Open any notebook (e.g. `Lagos_Class3.ipynb`) in **VS Code** (recommended) or **JupyterLab**.
2. **Restart the kernel** each time you run a new notebook so that every code block executes from a clean state.
   If you are using **JupyterLab**, remember to restart the kernel every time you run the code blocks as well.

### Reproducing the plots

```bash
# Activate the environment
conda activate quantum-mnist        # or source .venv/bin/activate

# Launch VS Code or JupyterLab
code .                              # VS Code – then open the notebook
# or
jupyter lab
```

---

## Repository layout

```
.
├── data/                      # All datasets used by the notebooks
├── Lagos_Class3.ipynb         # Plots for class 3 / Lagos backend
├── Perth_Class9.ipynb         # Plots for class 9 / Perth backend
├── quantum_vis_methodology.png
├── config.yaml                # Conda environment specification
├── requirements.txt           # Pip environment specification
└── README.md                  # You are here
```

---

## Citation

If you use this code or figure in your research, please cite the associated paper and link back to this repository.

---

## License

Distributed under the MIT License. See `LICENSE` for more information.
