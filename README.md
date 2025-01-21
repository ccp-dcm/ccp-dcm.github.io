Building
========

To build the website locally, you need Sphinx and a couple of plugins:
```console
  python -m pip install sphinx sphinx_bootstrap_theme sphinx_design
```
Then:
```console
  make html
```
The resulting files will appear in `build/html`.

If you further install sphinx-autobuild:
```console
  python -m pip install sphinx-autobuild
```
then you can start a local web server that automatically rebuilds when you save any source file with:
```console
  make auto-html
```
Point your web browser at [http://127.0.0.1:8000/](http://127.0.0.1:8000/) to see the site.

Editing
=======

Simply edit the rst files in the `source` directory. See also the [sphinx documentation](https://www.sphinx-doc.org/en/master/usage/restructuredtext/index.html),
the [sphinx design documentation](https://sphinx-design.readthedocs.io/en/latest/) and the [sphinx bootstrap documentation](http://ryan-roemer.github.io/sphinx-bootstrap-theme/README.html).

Publishing
==========

Pushes to the main branch will be published to the website automatically via a GitHub Action. A red cross on the main branch page on GitHub indicates an error in this process. Click on the red cross for more information.
