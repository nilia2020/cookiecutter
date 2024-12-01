# {{ cookiecutter.project_name }}

By: {{ cookiecutter.project_author_name }}.

Version: {{ cookiecutter.project_version }}

{{ cookiecutter.project_description }}

## Prerequisites

- [Anaconda](https://www.anaconda.com/download/) >=4.x
- Optional [Mamba](https://mamba.readthedocs.io/en/latest/)

## Create environment

```bash
conda env create -f environment.yml
activate {{ cookiecutter.project_slug }}
