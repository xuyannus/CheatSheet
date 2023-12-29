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
  - `poetry install`
  - `poetry shell`
  - `poetry add <library>`
  - `poetry remove <library>`
  - `poetry update <library>`
  - Display the package information: `poetry show`
  - Update the dependencies according to the pyproject.toml file:  `poetry update`


* [virtualenv]
  - `pip install virtualenv`
  - `virtualenv venv`
  - `source venv/bin/activate`
  - `pip freeze > requirements.txt`
  - `pip install -r requirements.txt`
  - `deactivate`



