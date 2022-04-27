# Building a site with Jupyter Book

## Install

## Build sample page

`jupyter-book create jupyterbook/`

## Build HTML

`jupyter-book build --builder html --path-output docs/jupyterbook jupyterbook`

This puts source into jupyterbook/_build/html, so to remove those intermediate directories, you can run:

`cp -a docs/jupyterbook/_build/html/. docs/jupyterbook`
`rm -rf docs/jupyterbook/_build`