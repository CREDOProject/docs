.. _credo_completion_fish:

credo completion fish
---------------------

Generate the autocompletion script for fish

Synopsis
~~~~~~~~


Generate the autocompletion script for the fish shell.

To load completions in your current shell session:

	credo completion fish | source

To load completions for every new session, execute once:

	credo completion fish > ~/.config/fish/completions/credo.fish

You will need to start a new shell for this setup to take effect.


::

  credo completion fish [flags]

Options
~~~~~~~

::

  -h, --help              help for fish
      --no-descriptions   disable completion descriptions
