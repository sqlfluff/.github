![SQLFluff](https://raw.githubusercontent.com/sqlfluff/sqlfluff/main/images/sqlfluff-wide.png)

# The SQL Linter for Humans

[![ReadTheDocs](https://img.shields.io/readthedocs/sqlfluff?style=flat-square&logo=Read%20the%20Docs)](https://sqlfluff.readthedocs.io)

**SQLFluff** is a dialect-flexible and configurable SQL linter. Designed
with ELT applications in mind, **SQLFluff** also works with Jinja templating
and dbt. **SQLFluff** will auto-fix most linting errors, allowing you to focus
your time on what matters.

## [SQLFluff core](https://github.com/sqlfluff/sqlfluff)

[![PyPi Version](https://img.shields.io/pypi/v/sqlfluff.svg?style=flat-square&logo=PyPi)](https://pypi.org/project/sqlfluff/)
[![PyPi License](https://img.shields.io/pypi/l/sqlfluff.svg?style=flat-square)](https://pypi.org/project/sqlfluff/)
[![PyPi Python Versions](https://img.shields.io/pypi/pyversions/sqlfluff.svg?style=flat-square)](https://pypi.org/project/sqlfluff/)
[![PyPi Status](https://img.shields.io/pypi/status/sqlfluff.svg?style=flat-square)](https://pypi.org/project/sqlfluff/)
[![PyPi Downloads](https://img.shields.io/pypi/dm/sqlfluff?style=flat-square)](https://pypi.org/project/sqlfluff/)

The core python library `sqlfluff` is the cornerstone of the SQLFluff family.
This is the project which is published on [pypi as `sqlfluff`](https://pypi.org/project/sqlfluff/).

If you're looking for somewhere to get started with SQLFluff, particularly in a
CLI or CI/CD context, this is almost certainly the place to start.

## [SQLFluff dbt templater](https://github.com/sqlfluff/sqlfluff/tree/main/plugins/sqlfluff-templater-dbt)

[![PyPi Version](https://img.shields.io/pypi/v/sqlfluff-templater-dbt.svg?style=flat-square&logo=PyPi)](https://pypi.org/project/sqlfluff-templater-dbt/)
[![PyPi License](https://img.shields.io/pypi/l/sqlfluff-templater-dbt.svg?style=flat-square)](https://pypi.org/project/sqlfluff-templater-dbt/)
[![PyPi Python Versions](https://img.shields.io/pypi/pyversions/sqlfluff-templater-dbt.svg?style=flat-square)](https://pypi.org/project/sqlfluff-templater-dbt/)
[![PyPi Status](https://img.shields.io/pypi/status/sqlfluff-templater-dbt.svg?style=flat-square)](https://pypi.org/project/sqlfluff-templater-dbt/)
[![PyPi Downloads](https://img.shields.io/pypi/dm/sqlfluff-templater-dbt?style=flat-square)](https://pypi.org/project/sqlfluff-templater-dbt/)

If you're using SQLFluff within the context of a [dbt](https://www.getdbt.com/)
project you might also be looking for to install along side the core SQLFluff
library above. This is the project which is published on
[pypi as `sqlfluff`](https://pypi.org/project/sqlfluff-templater-dbt/).

This is a plugin for SQLFluff and allows the `dbt` templater to be selected.
Currently, this plugin is maintained within the same git repository as the main
SQLFluff project because of fairly tight coupling between the two.

## [SQLFluff VSCode extension](https://github.com/sqlfluff/vscode-sqlfluff)

If you're developing SQL code within VSCode as your IDE, you may find our
maintained VSCode extension helpful. This project is published on
[OpenVSX as `vscode-sqlfluff`](https://open-vsx.org/extension/sqlfluff/vscode-sqlfluff)
or on the [Visual Studio Marketplace as `dorzey.vscode-sqlfluff`](https://marketplace.visualstudio.com/items?itemName=dorzey.vscode-sqlfluff).

## [SQLFluff Github Actions](https://github.com/sqlfluff/sqlfluff-github-actions)

Many users deploying SQFluff within a CI/CD context do so on the Github Actions
platform. For those users we provide a few templates of how some organisations
have done the same. These are provided as templates and examples. We recommend
that you personalise them to your own use case as applicable.

# Documentation

For full documentation visit [docs.sqlfluff.com](https://docs.sqlfluff.com/en/stable/).
This documentation is generated from the
[core SQLFluff repository](https://github.com/sqlfluff/sqlfluff), so to any issues or
contributions should be focussed there.

# SQLFluff on Slack

We have a fast-growing community
[on Slack](https://join.slack.com/t/sqlfluff/shared_invite/zt-o1f4x0e8-pZzarAIlQmKj_6ZwD16w0g),
come and join us!

# SQLFluff on Twitter

Follow us [on Twitter @SQLFluff](https://twitter.com/SQLFluff) for announcements
and other related posts.

# Contributing

We are grateful to all our [contributors](https://github.com/sqlfluff/sqlfluff/graphs/contributors).
There is a lot to do in this project, and we are just getting started.

If you want to understand more about the architecture of **SQLFluff**, you can
find [more here](https://docs.sqlfluff.com/en/latest/internals.html#architecture).

If you would like to contribute, check out the
[open issues on GitHub](https://github.com/sqlfluff/sqlfluff/issues). You can also see
the guide to [contributing](CONTRIBUTING.md).
