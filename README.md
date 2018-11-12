# LaTeX-starterkit

> Sylvain METAYER

## Prerequisites

- `texlive-full`

## Build

- `make build`

The PDF will be generated in `main.pdf`

## Tags

- `git tag -a v1.4 -m "my version 1.4"`

Then remember to push tags with `git push --tags`

## Travis CI

A basic travis CI build is provided.

This will generate a PDF from sources, and perform a basic spellcheck (in french).

PDF will be published in Github Release on every tags.