# pyenv-install-latest

This is a plugin for pyenv to install the latest version of python.

## Install

To install, clone into the pyenv plugins folder.

```
git clone https://github.com/killjoy1221/pyenv-install-latest $PYENV_ROOT/plugin/pyenv-install-latest
```

## Commands

The following commands are available. Use `--help` for usage.

### `pyenv install-latest`

Installs the latest python version. If an argument is given, will install the
latest version of that release.

### `pyenv uninstall-outdated`

Uninstalls all outdated versions. Only the latest installed version for each
release will be kept.

### `pyenv update-all`

Installs the latest version all currently installed python releases.
