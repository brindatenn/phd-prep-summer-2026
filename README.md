# phd-prep-summer-2026

Notebooks from my summer 2026 preparation before starting a PhD in Computer Science at UCL (Oct 2026 – Sep 2030), supervised by Dr He Wang (Professor, Virtual Environment and Computer Graphics Group, UCL Computer Science).

My PhD research focuses on model compression, continual learning and security for VLA models in embodied systems. This repo holds the PyTorch foundations that the work builds on.

## Contents

`week1/`: PyTorch foundations

| Notebook | What it covers |
|---|---|
| `pytorch_fundamentals.ipynb` | Tensors: creation, dtypes, shapes, indexing, reshaping, matrix operations, CPU/GPU device handling |
| `pytorch_workflow_fundamentals.ipynb` | The end-to-end workflow: data → model → loss & optimiser → training/evaluation loop → saving & loading |
| `neural_network_classification.ipynb` | Binary and multi-class classification with non-linear networks: activations, loss choice, accuracy |
| `autograd_intro.ipynb` | How autograd builds the computation graph and computes gradients |

Each notebook is a condensed reference I wrote while working through [Zero to Mastery: Learn PyTorch for Deep Learning](https://www.learnpytorch.io/) (chapters 00–02), plus a standalone notebook on autograd.

## Running the code

Written for Google Colab (free tier, T4 GPU). Open any notebook in Colab and run it top to bottom.

## Status

Complete. This repo is a snapshot of my pre-PhD foundations phase.
