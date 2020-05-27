# Template for Reveal.js based talks

This is a template I use to make [reveal.js](https://revealjs.com/) slides. The
slide contents are in `content.md`, which is loaded into `index.html`. There is
also custom styling and CSS classes to place items on slides defined in
`style.less`.

## Serving the slides

Install [livereload](https://github.com/lepture/python-livereload):

```
pip install livereload
```

or

```
conda install livereload -c conda-forge
```

Use `make serve` to start a server at http://localhost:8000. The page will
automatically reload the page when you update any of the files in the
repository.

## License

The template (`content.md`, `index.html`, and `style.less`) is licensed under a
<a href="https://creativecommons.org/licenses/by/4.0/">Creative Commons
Attribution 4.0 International License</a>.
