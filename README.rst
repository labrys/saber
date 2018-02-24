========
Overview
========

.. start-badges

.. list-table::
    :stub-columns: 1

    * - docs
      - |docs|
    * - tests
      - | |travis| |appveyor| |requires|
        | |codecov|
    * - package
      - | |version| |wheel| |supported-versions| |supported-implementations|
        | |commits-since|

.. |docs| image:: https://readthedocs.org/projects/saber/badge/?style=flat
    :target: https://readthedocs.org/projects/saber
    :alt: Documentation Status

.. |travis| image:: https://travis-ci.org/labrys/saber.svg?branch=master
    :alt: Travis-CI Build Status
    :target: https://travis-ci.org/labrys/saber

.. |appveyor| image:: https://ci.appveyor.com/api/projects/status/github/labrys/saber?branch=master&svg=true
    :alt: AppVeyor Build Status
    :target: https://ci.appveyor.com/project/labrys/saber

.. |requires| image:: https://requires.io/github/labrys/saber/requirements.svg?branch=master
    :alt: Requirements Status
    :target: https://requires.io/github/labrys/saber/requirements/?branch=master

.. |codecov| image:: https://codecov.io/github/labrys/saber/coverage.svg?branch=master
    :alt: Coverage Status
    :target: https://codecov.io/github/labrys/saber

.. |version| image:: https://img.shields.io/pypi/v/saber.svg
    :alt: PyPI Package latest release
    :target: https://pypi.python.org/pypi/saber

.. |commits-since| image:: https://img.shields.io/github/commits-since/labrys/saber/v0.1.0.svg
    :alt: Commits since latest release
    :target: https://github.com/labrys/saber/compare/v0.1.0...master

.. |wheel| image:: https://img.shields.io/pypi/wheel/saber.svg
    :alt: PyPI Wheel
    :target: https://pypi.python.org/pypi/saber

.. |supported-versions| image:: https://img.shields.io/pypi/pyversions/saber.svg
    :alt: Supported versions
    :target: https://pypi.python.org/pypi/saber

.. |supported-implementations| image:: https://img.shields.io/pypi/implementation/saber.svg
    :alt: Supported implementations
    :target: https://pypi.python.org/pypi/saber


.. end-badges

Library for the SABnzbd API

* Free software: BSD 2-Clause License

Installation
============

::

    pip install saber

Documentation
=============

https://saber.readthedocs.io/

Development
===========

To run the all tests run::

    tox

Note, to combine the coverage data from all the tox environments run:

.. list-table::
    :widths: 10 90
    :stub-columns: 1

    - - Windows
      - ::

            set PYTEST_ADDOPTS=--cov-append
            tox

    - - Other
      - ::

            PYTEST_ADDOPTS=--cov-append tox
