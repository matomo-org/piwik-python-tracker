========
Overview
========

.. start-badges

.. list-table::
    :stub-columns: 1

    * - docs
      - |docs|
    * - tests
      - | |travis| |codecov|
    * - package
      - |version| |downloads| |wheel| |supported-versions| |supported-implementations|

.. |docs| image:: https://readthedocs.org/projects/piwik-python-tracker/badge/?style=flat
    :target: https://readthedocs.org/projects/piwik-python-tracker
    :alt: Documentation Status

.. |travis| image:: https://travis-ci.org/piwik/piwik-python-tracker.svg?branch=master
    :alt: Travis-CI Build Status
    :target: https://travis-ci.org/piwik/piwik-python-tracker

.. |codecov| image:: https://codecov.io/github/piwik/piwik-python-tracker/coverage.svg?branch=master
    :alt: Coverage Status
    :target: https://codecov.io/github/piwik/piwik-python-tracker

.. |version| image:: https://img.shields.io/pypi/v/piwik-tracker.svg?style=flat
    :alt: PyPI Package latest release
    :target: https://pypi.python.org/pypi/piwik-tracker

.. |downloads| image:: https://img.shields.io/pypi/dm/piwik-tracker.svg?style=flat
    :alt: PyPI Package monthly downloads
    :target: https://pypi.python.org/pypi/piwik-tracker

.. |wheel| image:: https://img.shields.io/pypi/wheel/piwik-tracker.svg?style=flat
    :alt: PyPI Wheel
    :target: https://pypi.python.org/pypi/piwik-tracker

.. |supported-versions| image:: https://img.shields.io/pypi/pyversions/piwik-tracker.svg?style=flat
    :alt: Supported versions
    :target: https://pypi.python.org/pypi/piwik-tracker

.. |supported-implementations| image:: https://img.shields.io/pypi/implementation/piwik-tracker.svg?style=flat
    :alt: Supported implementations
    :target: https://pypi.python.org/pypi/piwik-tracker


.. end-badges

Official python implementation of the Piwik tracking API. You can use it to track visitors, ecommerce, actions, goals,
generate reports and much more.

* Free software: BSD license

Installation
============

::

    pip install piwik-tracker

Documentation
=============

https://piwik-python-tracker.readthedocs.io/

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
