# AIwiki

## Docsify

For full documentation visit [docsify.js.org](https://docsify.js.org).

### Docsify Commands

* `docsify init [path]` - Creates new docs.
* `docsify serve [path]` - Run local server to preview site.
* `docsify start <path>` - Server for SSR.
* `docsify generate <path>` - Docsify's generators.

### Docsify Project Layout

    docs/
        index.html # The configuration file.
        README.md  # The documentation homepage.
        .nojekyll  # Prevents GitHub Pages from ignoring files that begin with an underscore
        ...        # Other markdown pages, images and other files.

### nohup Docsify

* Run Docsify without hanging up - `nohup docsify serve docs -p 3000 > docsify.log 2>&1 &`
* List the `PID` of Docsify - `pgrep -fl docsify` or `jobs -l` or `ps -u $(whoami)`
* Kill the process of Docsify - `kill PID`

## MkDocs

For full documentation visit [mkdocs.org](https://www.mkdocs.org).

### MkDocs Commands

* `mkdocs new [dir-name]` - Create a new project.
* `mkdocs serve` - Start the live-reloading docs server.
* `mkdocs build` - Build the documentation site.
* `mkdocs -h` - Print help message and exit.

### MkDocs Project Layout

    mkdocs.yml    # The configuration file.
    docs/
        index.md  # The documentation homepage.
        ...       # Other markdown pages, images and other files.
