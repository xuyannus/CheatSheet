Python CheatSheet

Effective Python Book Summary
https://github.com/fabioperez/cheat-sheets/blob/master/python/Effective-Python-summary.md

Python Versions: pyenv
* `pyenv versions`
* `pyenv install 3.8.17`
* `pyenv local 3.8.17`
* `which python`

Virtual Enviorment
* [poetry]
  - `pip install poetry`
  - Installing dependencies: `poetry install`
  - Activate the Python virtual environment: `poetry shell`
  - Install a Python package: `poetry add <library>`
  - `poetry remove <library>`
  - `poetry update <library>`
  - Display the package information: `poetry show`
  - Update the dependencies according to the pyproject.toml file:  `poetry update`
  - poetry config --list
  - poetry config virtualenvs.in-project true


* [virtualenv]
  - `pip install virtualenv`
  - `virtualenv venv`
  - `source venv/bin/activate`
  - `pip freeze > requirements.txt`
  - `pip install -r requirements.txt`
  - `deactivate`



