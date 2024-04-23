.. _credo_conda:

credo conda
-----------

Retrieves a conda package and its dependencies.

Synopsis
~~~~~~~~


Retrieves a conda package and its dependencies.

::

  credo conda [flags]

Examples
~~~~~~~~

::


  Install a conda package:
  	credo conda numpy

  Install a conda package from a channel:
  	credo conda scipy --channel=bioconda


Options
~~~~~~~

::

      --channel string   Conda channel to use.
  -h, --help             help for conda
