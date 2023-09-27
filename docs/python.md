# Mac Python development environment setup

### Install [Homebrew](https://brew.sh)

### Install [pyenv](https://github.com/pyenv/pyenv) (Optional)

**Installation**

1. `brew install pyenv`
2. `echo 'export PATH="$HOME/.pyenv/shims:$PATH"' >> ~/.zshrc`

**Usage**

1. `pyenv install <version>`
2. `pyenv versions`
3. `pyenv global <version>`

### Install [Poetry](https://python-poetry.org)

**Installation**

1. `brew install poetry`
2. `poetry config virtualenvs.in-project true`

**Usage**

1. `poetry init`
2. `poetry env use <version>` (optional)
3. `poetry install`
