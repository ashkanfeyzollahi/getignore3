# GetIgnore3

<p align="center"><em>😎 Get gitignore files without bothering yourself</em>
    <img alt="GitHub last commit" src="https://img.shields.io/github/last-commit/ashkanfeyzollahi/getignore3">
    <img alt="GitHub License" src="https://img.shields.io/github/license/ashkanfeyzollahi/getignore3">
    <img alt="PyPI - Version" src="https://img.shields.io/pypi/v/getignore3">
</p>

getignore is a simple, no-fuss command-line tool for fetching .gitignore templates from the official GitHub gitignore repository. Whether you're starting a new project or tidying up an old one, getignore lets you easily grab the right .gitignore file for your stack — without digging through websites or typing out boilerplate.

```
usage: getignore [-h] [-L] [-l] [-n] [-c] [-o OUTPUT] [-w]
                 [template_name ...]

Get gitignore files without bothering yourself

positional arguments:
  template_name         Name(s) of gitignore templates to fetch
                        (e.g., Python, Node and etc.)

options:
  -h, --help            show this help message and exit
  -L, --list-cached-templates
                        List cached gitignore templates
  -l, --list-templates  List available gitignore templates
  -n, --no-cache        Don't cache the gitignore template file when
                        downloaded
  -c, --offline         Get the cached gitignore template instead of
                        downloading
  -o, --output OUTPUT   Where to write the gitignore template
                        content to
  -w, --override        Override existing gitignore file instead of
                        appending
```

## Features

* Automatically caches templates for offline use
* Can list available and cached templates
* Customizable output file location and behavior (append or overwrite)
* Simple CLI with minimal setup

## Installation

- You either install it from `pypi` using `pip`:

```bash
pip install getignore3
```

- Or directly install it from `github` using `pip`:

```bash
pip install git+https://github.com/ashkanfeyzollahi/getignore3.git
```

- Or even build it from source!
