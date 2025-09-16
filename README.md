# Scientific Software Development Demo

> Author: [Luna Dellazzeri](https://github.com/lunadellazzeri)  
> Email: lunadellazzeri@etu.univ-lyon1.fr

This repository provides a cosmology package developed as part of a course on Scientific Software Development, focusing on how to package Python code.

## Requirements

To use this package you will need to have Python (ideally v3.11) installed with the following dependencies:

### Core Dependencies
- python=3.11
- numpy>=1.25
- python-build
- twine

### Development Dependencies
- black
- isort
- myst-parser
- numpydoc
- pytest
- pytest-emoji
- pytest-cov
- sphinx
- sphinx-book-theme


### Optional Dependencies
- astropy (for verification)

### Additional Dependencies (via pip)
- pytest-pydocstyle
- line_profiler
- memory_profiler

### Manual install

All of these packages can easily be installed from [PyPI](https://pypi.org/) using `pip`.

```bash
pip install numpy>=1.25 build twine black isort myst-parser numpydoc pytest pytest-emoji pytest-cov sphinx sphinx-book-theme pytest-pydocstyle line_profiler memory_profiler
```