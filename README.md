# Python Devcontainer

Set up Python environment with Dev Container.

## Setup

- Install VSCode and Docker
- Install Dev Container VSCode Extension (`ms-vscode-remote.remote-containers`)
- Clone this repo

## Usage

### Start

`Ctrl + Shift + P` and run `Reopen in Container`. This will create a container and open it in VSCode.

### Install Python Libraries

Use [poetry](https://python-poetry.org/) to install python libraries.
Poetry records the libraries installed in `pyproject.toml`.
When a container is created, the libraries recorded in `pyproject.toml` will automatically be installed.
So you can keep track of the libraries you installed even if you delete the container.

When you use pip, the libraries installed will not be recorded.