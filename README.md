# Dialexa Python Cookiecutter

[![pre-commit.ci status](https://results.pre-commit.ci/badge/github/datanrd/dialexa-python-cookiecutter/develop.svg)](https://results.pre-commit.ci/latest/github/datanrd/dialexa-python-cookiecutter/develop)

[![codecov](https://codecov.io/gh/datanrd/dialexa-python-cookiecutter/branch/develop/graph/badge.svg?token=NFT6UC1HAW)](https://codecov.io/gh/datanrd/dialexa-python-cookiecutter)


Cookiecutter template for a Python package, built with popular develop tools and conform to best practice.

## Features

This template will create a Python project with the following features:


* [Poetry](https://python-poetry.org/): Manage dependency, build and release
* [Mkdocs](https://www.mkdocs.org): Writing your docs in markdown style
* Testing with [Pytest](https://pytest.org) (unittest is still supported out of the box)
* Code coverage report and endorsed by [Codecov](https://codecov.io)
* Format with [Black](https://github.com/psf/black) and [Isort](https://github.com/PyCQA/isort)
* Lint code with [Flake8](https://flake8.pycqa.org) and [Flake8-docstrings](https://pypi.org/project/flake8-docstrings/)
* Check static type with [Mypy](http://mypy-lang.org/) (optional)
* [Pre-commit hooks](https://pre-commit.com/): Formatting/linting anytime when commit your code
* [Mkdocstrings](https://mkdocstrings.github.io/): Auto API doc generation
* Command line interface using [Click](https://click.palletsprojects.com/en/8.0.x/) (optional)
* [Pyinvoke](https://docs.pyinvoke.org): Pythonic task runner as an alternative to makefiles
* Continuous Integration/Deployment by [GitHub actions](https://github.com/features/actions), includes:
    - publish dev build/official release to TestPyPI/PyPI automatically when CI success
    - publish documents automatically when CI success
    - extract changelog from CHANGELOG and integrate with release notes automatically
* Host your documentation from [GitHub Pages](https://pages.github.com) with zero-config

## Quickstart

Install the latest Cookiecutter if you haven't installed it yet (this requires Cookiecutter 1.4.0 or higher):

```
pip install -U cookiecutter
```

Generate a Python package project:

```
cookiecutter https://github.com/datanrd/dialexa-python-cookiecutter.git
```

Then follow **[Tutorial](docs/tutorial.md)** to finish other configurations.
