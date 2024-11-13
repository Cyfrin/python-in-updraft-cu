# Python in Updraft

This is part of the Cyfrin Updraft Vyper Course. 

You can find the google collab code here: https://colab.research.google.com/drive/1G0jampjfic2wE4eF-rFsH0ewp6q-rKiU?usp=sharing

Or, use the `cyfrin_updraft.ipynb` file in this repo.

- [Python in Updraft](#python-in-updraft)
- [Getting Started](#getting-started)
  - [Prerequisites](#prerequisites)
    - [Optional prerequisites](#optional-prerequisites)
    - [Optional Gitpod or CodeSpaces](#optional-gitpod-or-codespaces)
  - [Installation](#installation)
    - [uv](#uv)
    - [pip/python](#pippython)
- [Usage](#usage)

# Getting Started

## Prerequisites

- [uv](https://docs.astral.sh/uv/)
  - You'll know you've done it right if you can run `uv --version` and see a version number.
- [git](https://git-scm.com/)
  - You'll know you've done it right if you can run `git --version` and see a version number.

### Optional prerequisites

If you're an advanced python user, you can use virtual environments and classic python/pip to work here.

- [python](https://www.python.org/)
- [pip](https://pypi.org/project/pip/)

### Optional Gitpod or CodeSpaces

If you can't or don't want to run and install locally, you can work with this repo in Gitpod. If you do this, you can skip the `clone this repo` part.

<div style="display: flex; justify-content: center; gap: 20px;">
  <a href="https://gitpod.io/#github.com/cyfrin/web3py-favorites-cu">
    <img src="https://gitpod.io/button/open-in-gitpod.svg" alt="Open in Gitpod" style="height: 50px;">
  </a>
  <a href="https://github.dev/Cyfrin/web3py-favorites-cu">
    <img src="https://www.svgrepo.com/show/347707/codespaces.svg" alt="Open in CodeSpaces" style="height: 50px;">
  </a>
</div>

## Installation

```bash
git clone https://github.com/cyfrin/python-in-updraft
cd python-in-updraft
```

### uv 

```bash
uv sync
```

### pip/python

```bash
python -m venv ./venv
source ./venv/bin/activate
pip install -r requirements.txt
```

# Usage

```bash
uv run python basic_python.py
```

Or

```bash
python basic_python.py
```