# Before You Run This Notebook

To run the notebook successfully, make sure the environment is set up first.


## Requirements

- Python and Conda installed
- The environment file `lorenz.yaml`
- CPU execution is supported

## Setup Steps

1. Clone the repository:

```bash
git clone https://github.com/isabellaascione/toy_ml_examples.git
cd toy_ml_examples/lorenz
```

2. Create the Conda environment (recommended):

```bash
conda env create -f lorenz.yaml
```

3. Activate the environment:

```bash
conda activate lorenz_env
```

4. Launch Jupyter or VS Code Notebook and select this environment as the kernel.
5. Run the notebook from top to bottom.

## If You Do Not Use Conda

If you do not use Conda, create a virtual environment with `venv` or your preferred tool, then install the required packages with `pip`.

Example:

```bash
python -m venv .venv
source .venv/bin/activate
pip install -r requirements.txt
```

The `requirements.txt` file in the `lorenz` folder contains the Python packages used by the notebook.

## Data

No external data files are required to run the notebook. All data used in the Lorenz examples is generated inside the notebook.

## Reproducibility Note

For best reproducibility, use the same package versions defined in `lorenz.yaml`.

Results may vary slightly across different versions of Python, TensorFlow, NumPy, SciPy, scikit-learn, and across different hardware (CPU/GPU).

## Download

Project files can be downloaded here:

https://github.com/isabellaascione/toy_ml_examples.git

## Use of AI 

GitHub Copilot was used to generate part of the code


## Acknowledgements
Mike Bell contributed code used in some of the notebooks, particularly the ensemble-based notebooks.

