# Applied_Probability_and_Statistics

This repository contains six small, self-contained Jupyter notebooks illustrating core algorithms from applied probability and statistics. Each notebook uses tiny toy datasets so cells execute quickly and are suitable for classroom exercises.

## Getting Started with GitHub Codespaces

### Prerequisites

- **GitHub account:** Students need a GitHub account to create a Codespace.
- **Codespaces enabled:** Ensure GitHub Codespaces is enabled for your account or organization (check your GitHub account settings or ask your instructor/administrator).

### Opening this repo in a Codespace

1. Go to the repository page on GitHub.
2. Click the green **Code** button.
3. Select the **Codespaces** tab.
4. Click **Create codespace on `main`** (or the default branch).

Note: creating the Codespace can take a minute the first time while the environment is provisioned.

### Environment setup inside Codespaces

- Python is available by default in the Codespace.
- If this repository provides a `requirements.txt`, install dependencies with:

```bash
pip install -r requirements.txt
```

- If instead an `environment.yml` is provided (Conda), use:

```bash
conda env update -f environment.yml
conda activate <env-name>
```

- To install extra packages during your session:

```bash
pip install <package-name>
```

### Running the notebooks

In the Codespace, open the folder containing the six notebooks and open any notebook file. The notebooks included are:

- `Naive_Bayes_Tiny_Spam_Classifier.ipynb`
- `MLE_Estimating_Normal_Parameters.ipynb`
- `EM_1D_GMM.ipynb`
- `Markov_Chain_Weather.ipynb`
- `HMM_Toy_Forward_Viterbi.ipynb`
- `Monte_Carlo_Estimate_Pi.ipynb`

If prompted when opening a notebook, select the default Python kernel. You can run cells one-by-one (recommended for learning) or use the editor's **Run All** command to execute the whole notebook.

### Common issues / FAQ

- **Kernel fails to start:** Try reloading the Codespace window (browser refresh) and ensure any required dependencies are installed (see the `pip install -r requirements.txt` step if present).
- **Plots don't appear:** Make sure earlier cells that set up imports or data were run in order before running plotting cells. Restart the kernel and run cells sequentially if needed.

If you run into problems, ask your instructor or open an issue in the repository describing the error and the steps you took.

---

The notebooks are intended to be beginner-friendly; feel free to edit cells and experiment with parameters.