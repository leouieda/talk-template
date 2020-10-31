# Template for Reveal.js based talks

This is a template I use to make [reveal.js](https://revealjs.com/) slides. 
The slide contents are in `content.md`, which is loaded into `index.html`. 
There is also custom styling and CSS classes to place items on slides defined 
in `style.less` (using [Less](http://lesscss.org/)).

Most of the components used are included in the repository so that the 
presentation can work offline in a pinch. The only exception is math support
which uses MathJax from a CDN.

The original inspiration is this template by Matthew Turk: 
https://github.com/matthewturk/mjt-talk-template

## Serving the slides

## Locally

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

## GitHub Pages

Go to your repository `Setting > GitHub` Pages and select `Source` as your 
`master` or `main` branch and folder `/ (root)`. You probably want to select 
`Enforce HTTPS` as well.

Your talk should now be served at https://USERNAME.github.io/REPOSITORY
(it may take a little while for this to happen). 
For example, this template is served at
https://www.leouieda.com/talk-template/ (I use a custom domain).

## License

The template (`content.md`, `index.html`, and `style.less`) is licensed under a
<a href="https://creativecommons.org/licenses/by/4.0/">Creative Commons
Attribution 4.0 International License</a>.
