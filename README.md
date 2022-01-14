# Sandbox: Python

## Prerequisites

* pyenv
* pyenv-virtualenv

Then run:

```sh
eval "$(pyenv init -)"
eval "$(pyenv virtualenv-init -)"
```

## Usage - Initial setup

```sh
pyenv install 3.10.1
pyenv virtualenv 3.10.1 sandbox--python
```

## Usage

```sh
pyenv exec python -c 'print("Hello World")'
```
