# Info

This repository contains ...

## Editable install instructions

Python version: `3.xx`

0 - Install Python to operating system.

1 - Clone repository.

2 - Create python virtual environment in project directory, with specific Python version:

- Windows with Python launcher: `py -3.xx -m venv venv`
- MacOS & Linux: `python3.xx -m venv venv`
- Other options based on your environment manager.

3 - Activate virtual environment:

- Windows terminal: `venv/Scripts/activate`
- bash: `venv/bin/activate`
- [Other options](https://docs.python.org/3/library/venv.html#how-venvs-work) based on your OS & shell.

4 - Perform editable install in project directory: `pip install --editable .`

- Installing with optional dependencies: `pip install --editable .[optional1, optional2]`

Methods from the scripts in `src` can be imported anywhere in the project directory.
Any changes to the scripts in `src` will take effect immediately.
