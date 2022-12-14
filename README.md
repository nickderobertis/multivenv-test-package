

[![](https://codecov.io/gh/nickderobertis/multivenv-test-package/branch/main/graph/badge.svg)](https://codecov.io/gh/nickderobertis/multivenv-test-package)
[![PyPI](https://img.shields.io/pypi/v/multivenv-test-package)](https://pypi.org/project/multivenv-test-package/)
![PyPI - License](https://img.shields.io/pypi/l/multivenv-test-package)
[![Documentation](https://img.shields.io/badge/documentation-pass-green)](https://nickderobertis.github.io/multivenv-test-package/)
![Tests Run on Ubuntu Python Versions](https://img.shields.io/badge/Tests%20Ubuntu%2FPython-3.8%20%7C%203.9%20%7C%203.10-blue)
![Tests Run on Macos Python Versions](https://img.shields.io/badge/Tests%20Macos%2FPython-3.8%20%7C%203.9%20%7C%203.10-blue)
![Tests Run on Windows Python Versions](https://img.shields.io/badge/Tests%20Windows%2FPython-3.8%20%7C%203.9%20%7C%203.10-blue)
[![Github Repo](https://img.shields.io/badge/repo-github-informational)](https://github.com/nickderobertis/multivenv-test-package/)


#  multivenv-test-package

## Overview

A package to use as test data for testing the multivenv package

## Getting Started

Install `multivenv-test-package`:

```
pip install multivenv-test-package
```

A simple example:

```python
import multivenv_test_package

# Do something with multivenv_test_package
```

See a
[more in-depth tutorial here.](
https://nickderobertis.github.io/multivenv-test-package/tutorial.html
)

## Development Status

This project is currently in early-stage development. There may be
breaking changes often. While the major version is 0, minor version
upgrades will often have breaking changes.

## Developing

First, you need a couple global dependencies installed, see their documentation for details:
- [pipx](https://pypa.github.io/pipx/installation/)
- [direnv](https://direnv.net/docs/installation.html)

Then clone the repo and run `npm install` and `mvenv sync dev`. Make your changes and then run `just` to run formatting,
linting, and tests.

Develop documentation by running `just docs` to start up a dev server.

To run tests only, run `just test`. You can pass additional arguments to pytest,
e.g. `just test -k test_something`.

Prior to committing, you can run `just` with no arguments to run all the checks.

## Author

Created by Nick DeRobertis. MIT License.

## Links

See the
[documentation here.](
https://nickderobertis.github.io/multivenv-test-package/
)
