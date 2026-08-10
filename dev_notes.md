# Useful developer notes

### Linting and formating in jupyter notebook

For linting and formatting we use pylint and black, through the nbqa. Mypy does the static type checking

`pip install nbqa pylint black mypy`

After having installed the libraries we can run

`nbqa black your_notebook.ipynb`

`nbqa pylint your_notebook.ipynb`

`nbqa mypy your_notebook.ipynb`

source: https://www.pythontutorials.net/blog/how-to-use-pylint-or-other-linters-with-jupyter-notebooks/
