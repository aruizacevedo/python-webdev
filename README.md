# python-webdev
Template Python Web Development

Setup VS Code for Python with Pyenv and Poetry
https://www.youtube.com/watch?v=547Jr26duHQ

- https//github.com/pyenv/pyenv

## 1. Install `pyenv`


### mac

Install **pyenv**:
`$ brew install pyenv`

Add the following to your `~/.zshrc` (or equivalent):
```bash
export PATH="/home/<user>/.pyenv/bin:$PATH"
eval "$(pyenv init -)"
eval "$(pyenv virtualenv-init -)"
```

Install any version of Python:
`$ pyenv install 3.8.6`

Check installed versions:
`$ pyenv versions`

Set global python:
`$pyenv global 3.8.6`


## 2. Install `poetry`

Note: Make sure you set the global interpreter with `pyenv` first

```bash
pip install poetry
```

Add the following to your shell config
```bash
export PATH=$PATH:$HOME/.poetry/bin
```

## 3. Use it!

`$ poetry init`
-> creates `pyproject.toml` file

`$ poetry install`
-> creates a virtual environment
-> installs all packages

check path to virtual environment
`$ poetry env info --path`





