## Install
- Install using `brew` or build from source
```
$ brew install PyEnv
```

## Virtual Environments
```
$ python -m venv .venv
$ ls .venv/bin
$ source .venv/bin/activate // you’ll see env in shell
```

## Commands
```
$ pyenv install <version> // installs particular version
$ pyenv uninstall // to uninstall version
$ pyenv install -l // list versions to install
$ pyenv install —list
$ python -V // python version
$ pyenv versions // lists all versions currently installed
$ pyenv global <version> // set global version
$ pyenv local <version> // set local version, creates a .py 
$ pyenv which // shows path to executable for the current python version
$ pyenv help // list of available commands
$ pyenv shell // sets local version for current shell session
```
