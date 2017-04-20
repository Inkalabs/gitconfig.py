<!--
README generated with readmemako.py (github.com/russianidiot/readme-mako.py) and .README dotfiles (github.com/russianidiot-dotfiles/.README)
-->

[![python](https://img.shields.io/badge/Language-Python-blue.svg?style=plastic)]()
[![PyPI](https://img.shields.io/pypi/pyversions/gitconfig.svg)](https://pypi.python.org/pypi/gitconfig)
[![PyPI](https://img.shields.io/pypi/v/gitconfig.svg)](https://pypi.python.org/pypi/gitconfig)

[![](https://scrutinizer-ci.com/g/russianidiot/gitconfig.py/badges/quality-score.png?b=master)](https://scrutinizer-ci.com/g/russianidiot/gitconfig.py)
[![](https://codeclimate.com/github/russianidiot/gitconfig.py/badges/gpa.svg)](https://codeclimate.com/russianidiot/gitconfig.py)
[![](https://landscape.io/github/russianidiot/gitconfig.py/master/landscape.svg?style=flat)](https://landscape.io/github/russianidiot/gitconfig.py)

[![](https://scrutinizer-ci.com/g/russianidiot/gitconfig.py/badges/build.png?b=master)](https://scrutinizer-ci.com/g/russianidiot/gitconfig.py)
[![](https://api.travis-ci.org/russianidiot/gitconfig.py.svg)](https://travis-ci.org/russianidiot/gitconfig.py/)
[![](https://app.wercker.com/status/6701d8ad895b107580ba23523aaa414f/s/master)](https://app.wercker.com/russianidiot/gitconfig.py)
[![](https://semaphoreci.com/api/v1/russianidiot/gitconfig-py/branches/master/badge.svg)](https://semaphoreci.com/russianidiot/gitconfig-py)

<p align="center">
    <b>Gitconfig class and gitconfig variable for ~/.gitconfig</b>
</p>

#### Usage

```
from gitconfig import *

gitconfig.sections
>>> [...]

gitconfig.user.password
>>> 'secret'

gitconfig.not_existing
>>> None
```

[Examples/](https://github.com//tree/master/Examples)

Feedback
[![GitHub followers](https://img.shields.io/github/followers/russianidiot.svg?style=social&label=Follow)](https://github.com/russianidiot)
[![GitHub issues](https://img.shields.io/github/issues/russianidiot/gitconfig.py.svg)](https://github.com/russianidiot/gitconfig.py/issues)
