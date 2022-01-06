# Template for my reveal.js based slides

This is a template I use to make [reveal.js](https://revealjs.com/) slides
for talks and lectures.
It adds some custom styling and CSS classes for making columns, footnotes, 
and more.

**Preview:** https://www.leouieda.com/talk-template

> The original inspiration is this template by Matthew Turk:
> https://github.com/matthewturk/mjt-talk-template

## What's included

`index.html`: This is the master document that sets up reveal.js and 
its plugins and loads the slide content from `slides.md`. 
**Change the HTML title tag here**.

`slides.md`: Markdown file with the actual slide content. The template
includes some slides that demo the custom CSS classes available.
**Add your content here.**

`css/style.less`: Custom styling and CSS classes (using 
[Less](http://lesscss.org/)). Edit to tweak colours, sizes, fonts, 
spacing, etc.

`assets`: Images used in the presentation. You can probably delete all 
of these when making your slides. Replace the `favicon.png` with a 
32 x 32 px image to customize the icon (this is set in `index.html`).

`fonts`: Sources for the [FontAwesome](https://fontawesome.com/) icon 
font and [Computer-Modern](https://github.com/dreampulse/computer-modern-web-font)
(the default LaTeX font). Included in the repository for offline 
access. You could remove them and include fonts from a CDN (like
Google Fonts) in `index.html`.

`packages`: "Vendored" versions of reveal.js, Less, and 
[KaTeX](https://katex.org/) (for maths) that are used. 
Having them in the repository is important for using the slides offline
(on a plane or lecture room without easy internet access).

`serve.py`: Python script that serves the slides and reloads them
whenever the source files change. Very handy for development.
See below for instructions.

## Serving the slides locally

Unfortunately, you can't just open the `index.html` file on browser
to view your slides. 
Reveal.js requires an actual local server. 
You can set one up however you'd like.
Below, I provide instructions for doing so in Python (which is what 
I use most of the time) but it would work with any other local 
server.

First, install the [livereload](https://github.com/lepture/python-livereload)
Python package:

```
pip install livereload
```

or

```
conda install livereload -c conda-forge
```

Then, start a server at http://localhost:8008 by running:

```
python serve.py
```

The slides will open on your default browser and will automatically reload 
when you update any of the files in the repository.

## Serving on GitHub Pages

Go to your repository "Setting > Pages" and select "Source" as your
`main` branch and "Folder" as `/ (root)`. You probably want to select
"Enforce HTTPS as well.

Your slides should now be served at https://USERNAME.github.io/REPOSITORY
or equivalent if you're using a custom domain.
It may take a little while for this to happen.

For example, this template is served at
https://www.leouieda.com/talk-template.

## Exporting to PDF

You can save your slides to PDF for a backup or to distribute 
(I find students like this because they can annotate the PDF).
To do so, add `?print-pdf` to the end of the URL (either local
server or hosted) and then print the page to PDF.

This **works best on Chrome/Chromium**. The slides tend to be 
distorded on Firefox for some reason.

**WARNING:** Videos and gifs don't work on PDFs.

## License

The template (`slides.md`, `index.html`, and `css/style.less`) is licensed under a
<a href="https://creativecommons.org/licenses/by/4.0/">Creative Commons
Attribution 4.0 International License</a>.
