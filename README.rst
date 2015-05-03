======================
cookiecutter-pypackage
======================

Cookiecutter template for a Python package. See https://github.com/audreyr/cookiecutter.

Based on https://github.com/audreyr/cookiecutter-pypackage.git, with the following changes:
* Remove support of python 3.x and PyPy.
* Change license from BSD to MIT.

TODO:
* Use google/numpy sphinx format.
* Add sphinx badge to README.
* from future imports

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

.. _Travis-CI: http://travis-ci.org/
.. _Tox: http://testrun.org/tox/
.. _Sphinx: http://sphinx-doc.org/
.. _ReadTheDocs: https://readthedocs.org/
.. _`Nekroze/cookiecutter-pypackage`: https://github.com/Nekroze/cookiecutter-pypackage
.. _`tony/cookiecutter-pypackage`: https://github.com/tony/cookiecutter-pypackage
.. _github comparison view: https://github.com/tony/cookiecutter-pypackage/compare/audreyr:master...master
.. _`network`: https://github.com/audreyr/cookiecutter-pypackage/network
.. _`family tree`: https://github.com/audreyr/cookiecutter-pypackage/network/members
