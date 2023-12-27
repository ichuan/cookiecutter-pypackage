# cookiecutter-pypackage
A [cookiecutter](https://github.com/cookiecutter/cookiecutter) template for python package project, with `poetry` as dependencies management tool.


## Usage
First, install cookiecutter if you don't have it:

```
pipx install cookiecutter
```


Then, create an empty python package project with:

```
pipx run cookiecutter gh:ichuan/cookiecutter-pypackage
```


When the dirs are created, run `poetry install` to install dependencies.
