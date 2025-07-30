# GetIgnore3

<p align="center">😎 Get gitignore files without bothering yourself</p>

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

1. **Template Retrieval:**

   * Retrieves one or more .gitignore templates by name (e.g., Python, Node).
   * Lists available .gitignore templates from an online repository.

2. **Caching:**

   * Stores downloaded .gitignore templates locally for reuse.
   * Can retrieve templates in offline mode using the local cache.
   * Option to skip caching of downloaded templates.
   * Lists all locally cached .gitignore templates.

3. **Multiple Templates Support:**

   * Accepts multiple template names at once.
   * Combines the content of all specified templates into a single output.

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
