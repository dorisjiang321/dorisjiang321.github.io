# dorisjiang321.github.io

# Repo Content

This repository contains self introduction and several posts.

# Prerequisites

- [Quarto]
- [uv]
- [R]

# Instructions

Run the following commands in order from your terminal (shell) and R console as noted:

```bash
git clone git@github.com:dorisjiang321/dorisjiang321.github.io.git

uv sync

uv run quarto render

uv run quarto preview
```

```r
renv::restore()
```


# Open Locally
```bash
uv run quarto preview
```
to launch a local live-reloading preview server.

# Data Source

Gapminder data comes from the [Gapminder] https://www.gapminder.org