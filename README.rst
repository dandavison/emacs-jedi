This fork is an experimental, stripped-down version of the real emacs-jedi: https://github.com/tkf/emacs-jedi. A single server process is used instead of a pool of servers.

To use this fork, you must arrange for the variable ``jedi:virtualenv`` to be set in every python buffer to the location of the appropriate virtualenv.
