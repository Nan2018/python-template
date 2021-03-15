This repos serves as a template for python repos. It includes

* .gitignore
* .pre-commit-config.yaml, pre-commit hook configurate for auto formatting and linting
* tox.ini, minimal configurations to make `isort`, `black`, and `flake8` compatible with one another
* requirements-dev.txt


Install dependencies by
```
pip install -r requirements-dev.txt
```
Add the `pre-commit` hook for auto-formatting and linting by
```
pre-commit install
```
