# ML4GW CERN AI Workshop tutorial 2026

This is a one-hour tutorial on [ML4GW](https://ml4gw.github.io/ml4gw/) tools,
showcasing the different components and how they are useful in the context of
training neural network models for GW science.

Dependency requirements are specified in `requirements.txt`. You can use
[uv](https://docs.astral.sh/uv/getting-started/installation/) to install dependencies.
```bash
$ uv venv --python=3.12 && uv pip install -r requirements.txt
```
Start the `jupyter-notebook` using the `uv` entrypoint, or if using vscode, select
the python interpreter from the created virtualenv.
```bash
$ uv run jupyter-notebook
```

## Alternatively, use Google Colab
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/deepchatterjeeligo/cern-aigw-2026/blob/main/ml4gw-tutorial.ipynb)

You will need to save the notebook under your own namespace to run or make changes.
To select a session with a GPU, click on the runtime (likely present on the top left), select "Change runtime type" and choose one of the free GPU sessions, like T4.

