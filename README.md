# stactools-geoparquet-items

[![PyPI](https://img.shields.io/pypi/v/stactools-geoparquet-items)](https://pypi.org/project/stactools-geoparquet-items/)

- Name: geoparquet-items
- Package: `stactools.geoparquet_items`
- [stactools-geoparquet-items on PyPI](https://pypi.org/project/stactools-geoparquet-items/)
- Owner: @m-mohr

Uses stac-geoparquet to generate a geoparquet for a list of STAC items.

## Installation

```shell
pip install stactools-geoparquet-items
```

## Command-line Usage

Description of the command line functions

```shell
stac geoparquet-items create https://example.com/collections/id/items result.geoparquet
```

```shell
stac geoparquet-items create /path/to/folder result.geoparquet
```

Use `stac geoparquet-items --help` to see all subcommands and options.

## Contributing

We use [pre-commit](https://pre-commit.com/) to check any changes.
To set up your development environment:

```shell
pip install -e .
pip install -r requirements-dev.txt
pre-commit install
```

To check all files:

```shell
pre-commit run --all-files
```

To run the tests:

```shell
pytest -vv
```
