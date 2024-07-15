# Clean Python Project Template

A tool for creating skeleton python project, built with popular develop tools and
conform to the best practice.


## Features

This tool will create Python project with the following features:

* [Poetry]: Manage version, dependancy, build and release
* [Mkdocs]: Writting your docs in markdown style
* Testing with [Pytest] (unittest is still supported out of the box)
* Code coverage report and endorsed by [Codecov]
* [Tox]: Test your code against environment matrix, lint and artifact check.
* Format and lint code with [Ruff]
* [Pre-commit hooks]: Formatting/linting anytime when commit/run local tox/CI
* [Mkdocstrings]: Auto API doc generation and docstring template (vscode and its extension [autodocStrings] is required)
* Command line interface using [Python Fire] (optional)
* Continuouse Integration/Deployment by [github actions], includes:
    - publish dev build/official release to TestPyPI/PyPI automatically when CI success
    - publish documents automatically when CI success
    - extract change log from github and integrate with release notes automatically
* Host your documentation from [Git Pages] with zero-config
* Support multiple versions of documentations (by [mike])
* Create repo and push initial commits by repo.sh script

## Quickstart
This is a cookiecutter template. so if you don' have cookiecutter installed, please installed with `pip` or your favorite package manager.

Just use Cookiecutter to start your project. Type on the terminal:

```
cookiecutter https://github.com/fccoelho/python-project
```

then follow the instructions on the screen.


Then follow the **[Tutorial]** to finish configurations.

# Credits

This repo is forked from [zillionare/python-project-wizard](https://github.com/zillionare/python-project-wizard), and includes  the following tools:


[poetry]: https://python-poetry.org/
[mkdocs]: https://www.mkdocs.org
[pytest]: https://pytest.org
[codecov]: https://codecov.io
[tox]: https://tox.readthedocs.io
[Ruff]: https://github.com/astral-sh/ruff
[isort]: https://github.com/PyCQA/isort
[mkdocstrings]: https://mkdocstrings.github.io/
[Python Fire]: https://github.com/google/python-fire
[github actions]: https://github.com/features/actions
[Git Pages]: https://pages.github.com
[Pre-commit hooks]: https://pre-commit.com/
[mike]: https://github.com/jimporter/mike
[autoDocStrings]: https://marketplace.visualstudio.com/items?itemName=njpwerner.autodocstring
[Tutorial]: https://zillionare.github.io/python-project-wizard/tutorial/
[audreyr/cookiecutter-pypackage]: https://github.com/audreyr/cookiecutter-pypackage
[briggySmalls]: https://github.com/briggySmalls/cookiecutter-pypackage

# Links
## cfg4py
[cfg4py](https://pypi.org/project/cfg4py/) is a great tool for managing configuration files, supporting configuration for different environments (dev, prodction and test), automatically converting yaml-based configuration to python class, so, you can access configuration items by attribute, thus, enable auto-completion (by IDE). It also supports live-reload, remoting central configuration, config template and more.
