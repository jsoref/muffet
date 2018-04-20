# Muffet

[![Circle CI](https://img.shields.io/circleci/project/github/raviqqe/muffet.svg?style=flat-square)](https://circleci.com/gh/raviqqe/muffet)
[![Go Report Card](https://goreportcard.com/badge/github.com/raviqqe/muffet?style=flat-square)](https://goreportcard.com/report/github.com/raviqqe/muffet)
[![License](https://img.shields.io/github/license/raviqqe/muffet.svg?style=flat-square)](LICENSE)

Muffet is a web site linter which scrapes and inspects all pages in a domain
recursively.

## Features

- Massive speed
- Colored outputs
- Different types of linting
  - HTML syntax check
  - URL validation
  - Link connectivity
  - Misspelling detection (not implemented yet)

## Installation

```
go get -u github.com/raviqqe/muffet
```

## Usage

```
muffet https://your.cool.web.site
```

For more information, see `muffet --help`.

## License

[MIT](LICENSE)
