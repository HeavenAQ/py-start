## Introduction

This is a simple project to setup python project with `pytest` and `git`. It allows you to have a project structured like this:

```
.
├── libs/
│   └── __init__.py
├── main.py
├── requirements.txt
├── tests/
├── .git/
└── .gitignore

3 directories, 3 files
```

## Installation

```bash
git clone https://github.com/HeavenAQ/py-start.git
cd py-start
mv pystart </bin/path>
```

## Usage

```bash
pystart --help
    Usage: pystart <project_name>
    Create a new python project with pytest
```

> **NOTE**:
>
> - Please make sure you have `python3`, `pip3`, `virtualenv`, and `git` installed on your machine.
> - Ensure to `export PYTHONPATH=$(pwd)` to make the `libs` directory available to the files under `tests`.
