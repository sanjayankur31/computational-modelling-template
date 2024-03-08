# Contributing guidelines

## Code style

1. We use [flake8](https://pypi.org/project/flake8/) to ensure that the code
   follows a consistent style as part of continuous integration on Travis.
   Currently, the information from flake8 is informative only.

2. The source code uses spaces, and each tab is equivalent to 4 spaces.

3. We use the [reStructuredText (reST)
   format](https://stackoverflow.com/a/24385103/375067) for Python docstrings.
   Please document your code when opening pull requests.

## Pre-commit

A number of [pre-commit](https://pre-commit.com/) hooks are used to improve code-quality.
Please run the following code to set up the pre-commit hooks:

    $ pre-commit install

## Commit messages

Writing good commit messages makes things easy to follow.
Please see these posts:

- [How to write a Git commit message](https://cbea.ms/git-commit/)
- While not compulsory, we prefer [conventional commits](https://www.conventionalcommits.org/en/v1.0.0/)
