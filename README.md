# Spectral Example Notebooks

[![Python 3.10+](https://img.shields.io/badge/python-3.10%2B-blue?logo=python&logoColor=white)](https://www.python.org/)
[![Runs on Colab](https://img.shields.io/badge/runs%20on-Google%20Colab-F9AB00?logo=googlecolab&logoColor=white)](https://colab.research.google.com/)
[![Made by Principled Intelligence](https://img.shields.io/badge/made%20by-Principled%20Intelligence-0D1117)](https://principled-intelligence.com)

Ready-to-run notebooks for trying **[Spectral](https://principled-intelligence.com/products/spectral)** with example AI chatbots.

Spectral helps you test whether an AI assistant behaves the way you expect before you rely on it in real use. These examples walk you through running a chatbot, connecting it to Spectral, and reviewing the evaluation results.

You do not need to install anything to start. The recommended path opens in Google Colab and guides you through each step.

## Start here

New here? Start with the hosted-model notebook. It is the simplest first run and uses a CPU Colab runtime.

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://drive.google.com/file/d/1qtkqy3oDb5_JufaUd9vEUvwgY2jTXYyt/view?usp=sharing)

By the end of the notebook, you will have:

- A small RAG chatbot running in Colab
- A live endpoint that Spectral can evaluate
- An evaluation result you can inspect in Spectral

RAG, or retrieval-augmented generation, is a common chatbot pattern where the AI answers using a provided set of documents.

## Before you start

The notebooks will guide you through their own setup. In general, expect to need:

- A Google account to open Colab
- Access to the [Spectral dashboard](https://spectral.principled.app/)
- API keys or tokens for the services used by the notebook you choose

## Choose a notebook

| Notebook | Choose this if... | Link |
|---|---|---|
| Create a Simple RAG Chatbot - OpenAI | You want the easiest first run and have access to a hosted model provider | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://drive.google.com/file/d/1qtkqy3oDb5_JufaUd9vEUvwgY2jTXYyt/view?usp=sharing) |
| Create a Simple RAG Chatbot - Local Model | You want to try a model that runs inside the notebook runtime | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1DgT1c97SKXCH_oSiEc3f3CBca-s2PM4p?usp=sharing) |
| Create a Simple RAG Chatbot - OpenAI + Spectral Bridge | You need Spectral to evaluate an internal or private target | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://drive.google.com/file/d/1FNxov8N2LXcU2SODDQWtBL2yWm3mXdPe/view?usp=sharing) |

A hosted model API means the chatbot uses a model from a provider such as OpenAI, Anthropic, or Google. A local/open model runs in the notebook runtime instead.

Spectral Bridge is for private connectivity. Use the hosted-model notebook first unless you already know you need this path.

## Run in Colab or locally

Colab is the recommended path for beginners because the notebooks are designed to run top-to-bottom with minimal local setup.

Local setup is optional and intended for users who are already comfortable with Python and Jupyter. If you prefer to run locally, use Python 3.10 or newer, open the notebook in Jupyter-compatible tooling, and follow the same notebook cells. Local runs may require adapting notebook-specific environment setup.

## If something does not work

- Restart the Colab runtime and run the cells again from the top.
- Check that your required API keys or Spectral credentials are set.
- Use the hosted-model notebook before trying local models or private connectivity.

## Learn more

- [Spectral](https://principled-intelligence.com/products/spectral)
- [Principled Intelligence](https://principled-intelligence.com)

## License

This repository is licensed under the Apache License 2.0.
