# AI-Research

Educational collection of interactive Jupyter notebooks covering foundational math for ML, neural network fundamentals, PyTorch basics, and transformer architectures.

---

## 🚀 Quick Overview

- **Purpose:** Learn and experiment with core concepts in machine learning and deep learning through runnable notebooks.
- **Main topics:** Math foundations, single-neuron & layer implementations, PyTorch tensor operations, and transformer attention mechanisms.

---

## 📁 Project Structure

```
intro/                # Math foundations and examples
  math/               # Math-focused notebooks (derivatives, vectors, gradients, matrices, probability)
neural network/      # Building neurons and layers from scratch
pytorch/              # Tensors, indexing, reshaping, and matrix ops in PyTorch
transformers/         # Attention & transformer architecture notebooks
```

Examples of notebooks included:
- `intro/math/1_math_functions_examples.ipynb`
- `neural network/1_single_neuron_from_scratch.ipynb`
- `pytorch/creating_tensors.ipynb`
- `transformers/1_attention_mechanism.ipynb`

---

## ⚙️ Requirements & Setup

1. Install Python 3.8+ (use a virtual environment).
2. Create and activate a venv (example):

```bash
python -m venv .venv
# Windows
.\.venv\Scripts\Activate.ps1  # PowerShell
# macOS / Linux
source .venv/bin/activate
```

3. Install dependencies:

```bash
pip install -r requirements.txt
```

Note: `requirements.txt` currently includes `numpy` and `matplotlib`. If you want to run PyTorch notebooks, install PyTorch separately following the instructions at https://pytorch.org/ (choose the right CUDA / CPU build).

4. Start Jupyter Lab or Notebook and open the notebooks:

```bash
pip install jupyterlab
jupyter lab
```

Or open notebooks directly in VS Code with the Jupyter extension.

---

## 🧪 How to use

- Open any notebook and run the cells sequentially.
- For reproducibility, restart the kernel and run all cells when trying new changes.
- Keep dependencies up-to-date and pin versions in `requirements.txt` if needed.

---

## 🤝 Contributing

Contributions are welcome! Please:
1. Open an issue for proposed changes or improvements.
2. Make changes in a feature branch and open a pull request.
3. Add notebook examples, additional notes, or improved explanations.

---

## 📄 License

No license is currently included. If you'd like to apply a license (e.g., MIT), add a `LICENSE` file and I can update the README to reflect it.

---

## 💬 Contact / Repo

Repository: `Tushar0326/AI-Research`


