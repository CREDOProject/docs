.. This file is generated from CREDOProject/cookiecutter.
   You need to consider modifying the TEMPLATE or modifying THIS FILE.

.. include:: ../README.rst

Introduction
============

.. ADDITIONAL CONTENT START

.. ADDITIONAL CONTENT END

Getting Started
===============

.. note::

   We assume you already have a Sphinx documentation,
   if not, see `Getting Started with Sphinx`_.

First, downloading extension from PyPI:

.. code-block:: console

   $ pip install credodocs

Then, add the extension name to ``extensions`` configuration item in your conf.py_:

.. code-block:: python

   extensions = [
             # …
             'docs.Credo Documentation',
             # …
             ]

.. _Getting Started with Sphinx: https://www.sphinx-doc.org/en/master/usage/quickstart.html
.. _conf.py: https://www.sphinx-doc.org/en/master/usage/configuration.html

.. ADDITIONAL CONTENT START

.. ADDITIONAL CONTENT END

Contents
========

.. toctree::
   :caption: Contents

   changelog

The Sphinx Notes Project
========================

The project is developed by `CREDOProject`__,
as part of **The Sphinx Notes Project**.

.. toctree::
   :caption: The Sphinx Notes Project

   Home <https://sphinx.silverrainz.me/>
   Blog <https://silverrainz.me/blog/category/sphinx.html>
   PyPI <https://pypi.org/search/?q=docs>

__ https://github.com/SilverRainZ
