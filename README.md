# gitdriver

[![Code style: black](https://img.shields.io/badge/code%20style-black-000000.svg)](https://github.com/psf/black)
[![Checked with mypy](http://www.mypy-lang.org/static/mypy_badge.svg)](http://mypy-lang.org/)
[![Download from PyPI](https://img.shields.io/pypi/v/gitdriver)](https://pypi.org/project/gitdriver)
[![Latest release](https://img.shields.io/github/v/release/potatoeggy/gitdriver?display_name=tag)](https://github.com/potatoeggy/gitdriver/releases/latest)
[![License](https://img.shields.io/github/license/potatoeggy/gitdriver)](/LICENSE)

Python command line application and library to convert a Google Doc/Sheet/Slide into a Git repo w/revision history.

## Installation

Install the package from PyPI:

```
pip3 install gitdriver
```

Or, to build from source:

Gitdriver depends on [poetry](https://github.com/python-poetry/poetry) for building.

```
git clone https://github.com/potatoeggy/gitdriver.git
poetry install
poetry build
pip3 install dist/gitdriver*.whl
```
