########################
Document Writer Tutorial
########################


| This is mostly edited version of https://docs.readthedocs.io/en/latest/getting_started.html
| Free free to check it out


| Notice: Although it's possible to write docs to Markdown, but it's not recommended
| Since you lose many "helpers" from Sphinx with Markdown


********************
Install Dependencies
********************


Python and ``pip``
==================
| Python and ``pip`` are so common, and there are too many ways to install them.
| Find a method to install them
| Most common method for MacOS would be `Homebrew <https://brew.sh/>`_


Sphinx
======
.. code-block:: bash

  pip install sphinx sphinx-autobuild


*****************
Write and Preview
*****************


Build Manually
==============
.. code-block:: bash

  cd /path/to/spacious-readthedocs/docs
  # Make changes
  make html
  # Open built local HTML file in browser yourself, like `open _build/html/index.html`


Build Automatically
===================
.. code-block:: bash

  cd /path/to/spacious-readthedocs/docs
  sphinx-autobuild . _build/html
  # Make changes
  # Open built local HTML file in browser yourself, like `open _build/html/index.html`
