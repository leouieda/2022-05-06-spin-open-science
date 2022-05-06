# Getting started with Open Science

**Slides:** https://www.leouieda.com/2022-05-06-spin-open-science

**Recording:** TBD

Presentation for a short workshop about open science practices for the
[SPIN: Seismological Parameters and INstrumentation](https://spin-itn.eu/)
doctoral training network.

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

## License

The template (`slides.md`, `index.html`, and `css/style.less`) is licensed under a
<a href="https://creativecommons.org/licenses/by/4.0/">Creative Commons
Attribution 4.0 International License</a>.
