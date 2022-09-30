# Material For MkDocs (Broken Nav)
See https://github.com/squidfunk/mkdocs-material/issues/4369

## Installation

```shell
export GH_TOKEN=XYZToken
python3 -m pip install mkdocs git+https://${GH_TOKEN}@github.com/squidfunk/mkdocs-material-insiders.git --upgrade
```

**How to install an old version**  

Use the commit id like this.

```shell
python3 -m pip install git+https://${GH_TOKEN}@github.com/squidfunk/mkdocs-material-insiders.git@62d4e1caac3cca088cce4c16ed399fa25f958fe3 --upgrade
```

**How to check version info**

```shell
python --version
mkdocs --version
pip show mkdocs-material | grep -E ^Version
```

## Build the site

```
python3 -m mkdocs serve
```