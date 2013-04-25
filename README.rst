venv - python virtualenv shortcuts
###############################################################################

``venv`` is a small bash script that helps bootstrapping and managing a custom python environment in your home directory. It uses ``virtualenv`` and ``pip`` internally and is really just a little helper script. No magic.

If you run it for the first time, `venv` creates a single virtual environment in ``$HOME/.venv/`` for you. If ``virtualenv`` is not installed on your system, a fresh copy is downloaded from online sources. No need to download ``virtualenv``, ``setuptools`` or ``pip`` manually.

Usage
-----

``venv`` or ``venv python``
  Run a python shell. This is a shortcut for ``'$HOME/.venv/bin/activate; python'``
``venv PROG``
  Run a programm or script installed to ``$HOME/.venv/bin/``. (e.g. ``venv ipython``).
``venv PIP_COMMAND``
  Run pip with the specified command (e.g. ``venv install ipython``).
``venv MODULE``
  Run a python module as a script (same as ``venv python -m MODULE``)
        
        
