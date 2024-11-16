# redwatch

[![PyPI](https://img.shields.io/pypi/v/redwatch.svg)](https://pypi.org/project/redwatch/)
[![Changelog](https://img.shields.io/github/v/release/jeedo/redwatch?include_prereleases&label=changelog)](https://github.com/jeedo/redwatch/releases)
[![Tests](https://github.com/jeedo/redwatch/actions/workflows/test.yml/badge.svg)](https://github.com/jeedo/redwatch/actions/workflows/test.yml)
[![License](https://img.shields.io/badge/license-Apache%202.0-blue.svg)](https://github.com/jeedo/redwatch/blob/master/LICENSE)

Watches Reddit for posts

## Installation

Install this tool using `pip`:
```bash
pip install redwatch
```
## Usage

For help, run:
```bash
redwatch --help
```
You can also use:
```bash
python -m redwatch --help
```
## Development

To contribute to this tool, first checkout the code. Then create a new virtual environment:
```bash
cd redwatch
python -m venv venv
source venv/bin/activate
```
Now install the dependencies and test dependencies:
```bash
pip install -e '.[test]'
```
To run the tests:
```bash
python -m pytest
```
