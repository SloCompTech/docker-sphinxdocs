# SphinxDocs

<p align="center">
  <img src="https://github.com/familqasimov/docker-sphinxdocs/blob/master/logo/logo.svg" height="30%" width="30%">
</p>

[![Build Status](https://travis-ci.org/SloCompTech/docker-sphinxdocs.svg?branch=master)](https://travis-ci.org/SloCompTech/docker-sphinxdocs)

## What is it ?
It it simple docker which provides tools to easly build sphinx docs.

**Installed themes**
- [Boostrap theme](https://github.com/ryan-roemer/sphinx-bootstrap-theme)
- [Read the docs](https://github.com/rtfd/sphinx_rtd_theme)
- [Guzzle](https://github.com/guzzle/guzzle_sphinx_theme)

## Example build commands
```bash
sphinx-build -b html <sourcedir> <builddir>
```
if you used `sphinx-quickstart` you can use
```bash
make html
```

## External documentation
- [Sphinx](http://www.sphinx-doc.org/en/master/usage/quickstart.html)
- [Read the docs](https://docs.readthedocs.io/en/latest/getting_started.html)
