# ansible-cutter

This is a simple [cookiecutter](https://cookiecutter.readthedocs.io/) template which
can be used to create a new ansible project. There are various templates for creating
roles but sometimes you want to create a new top-level project that you pull roles into.

## Installing cookiecutter

    pip install cookiecutter

if you get a bunch of errors on a mac then try this:

    sudo -H pip install --ignore-installed cookiecutter

## Using this template

You can easily add this to your `~/.cookiecutterrc` something like this:

    abbreviations:
      ansible: https://github.com/boyvinall/ansible-cutter.git

Then you can run the following command to create a new ansible project:

    cookiecutter ansible
