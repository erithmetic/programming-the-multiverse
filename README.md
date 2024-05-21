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
