================
Release Strategy
================

Versioning
==========

- All versions should follow the format of ``MAJOR.MINOR``
- To reduce the maintenance burden, normally we won't do bugfix for non-latest
  versions neither release patch versions
- We may have alpha (such ``1.0a0``) or beta (such as ``1.0b0``) versions before
  the official release

Publishing
==========

We publishing python packages on PyPI, with "sphinxnotes" prefix, just
access https://pypi.org/search/?q=sphinxnotes to get all of them.

PyPI publishing already `automated with Github Actions`__.
If you want to publish package locally, execute ``make upload`` from the project
root (make sure you have your `API token`__ correctly configured)

__ https://github.com/sphinx-notes/cookiecutter/blob/master/%7B%7Bcookiecutter.name%7D%7D/.github/workflows/release.yml
__ https://pypi.org/help/#apitoken
