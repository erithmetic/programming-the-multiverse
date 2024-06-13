# programming-the-multiverse

Code repo for my blog series, "[Programming the Multiverse](https://erica.works/programming-the-multiverse-part-1/)"

## Setup

If you're on a mac, install homebrew and python.

**Note that the use of pyenv and poetry help ensure the correct version of python and project packages are used**

```bash
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
brew install pyenv
```

Then clone this repository and run:

```bash
git clone git@github.com:erithmetic/programming-the-multiverse.git
cd programming-the-multiverse
pyenv install
pip install poetry
poetry install
```

### Visual Studio

If you'd like to run the jupyter notebooks in Visual Studio, first install the Jupyter Notebook renderer extension.

When you ran `poetry install` above, it tells you it created a virtual environment, similar to:

```
Creating virtualenv programming-the-multiverse-XzkVdwHA-py3.12 in /Users/you/Library/Caches/pypoetry/virtualenvs
```

Next, open the `.ipynb` file you want to run. In the upper right part of the window there's an option to select a python environment. Click it, then you get a prompt to "change kernel for ..."

Select the option "select another kernel"

Then select "Python environments" and "Create Python Environment"

Next select "Venv" and use the path noted above as a prefix, but append the full path to the python executable, for example:

`/Users/you/Library/Caches/pypoetry/virtualenvs/programming-the-multiverse-XzkVdwHA-py3.12/bin/python`

And you're all set!
