This document contains information about contributing to this repository. Please read it before contributing.

## Setup Instructions

`fastapi-async-langchain` is built with Python 3.9 and managed by Poetry.
Clone this repository and follow the steps below to get started.

### Create conda environment:

```bash
conda create -n fastapi-async-langchain python=3.9 -y
conda activate fastapi-async-langchain
```

You can choose any other environment manager of your choice.

### Install dependencies:

```bash
pip install poetry
poetry install
```

## CI/CD

fastapi-async-langchain uses `pre-commit` to run code checks and tests before every commit. To install the pre-commit hooks, run the following commands:

```bash
pre-commit install
```
