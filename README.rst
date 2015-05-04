======================
cookiecutter-pypackage
======================

Cookiecutter template for a Python package. See https://github.com/audreyr/cookiecutter.

Based on https://github.com/audreyr/cookiecutter-pypackage.git, with the following changes:

* Remove support of python 3.x and PyPy.
* Change license from BSD to MIT.
* Customize sphinx:
  * Use napoleon to support google/numpy-style docstrings.
  * Enable linkcode and add glue code for links to github master.
  * Add boilerplate for mocking out packages that ReadTheDocs can ignore.

TODO:

* Add sphinx badge to README.
* add scripts (or at least checklists in contributing.rst) to:
  * create a new module file (inlcuding adding it sphinx, unit tests, etc)
  * update the version number
  * add a new dependency (sphinx mocks, requirements.txt, setup.py, installation.rst)
  * publish a new release (https://gist.github.com/audreyr/5990987)
* 2to3 strategy? (from future imports, 2to3, https://pythonhosted.org/six/)
* Update installation instructions (see notes there)
* Use py.test

Usage
-----

Generate a Python package project::

    cookiecutter https://github.com/dkirkby/cookiecutter-pypackage.git

Then:

* Create a repo and put it there.
* Add the repo to your Travis CI account.
* Add the repo to your ReadTheDocs account + turn on the ReadTheDocs service hook.
* Release your package the standard Python way. Here's a release checklist: https://gist.github.com/audreyr/5990987

References
----------

* https://python-packaging-user-guide.readthedocs.org/en/latest/distributing.html
* http://www.jeffknupp.com/blog/2013/08/16/open-sourcing-a-python-project-the-right-way/
