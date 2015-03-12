Development Box
===================

This my personal development environment. There are many like it, but
this one is mine.

Installation:

    $ virtualenv env
    $ source env/bin/activate
    $ pip install ansible

To create the environment:

    $ vagrant up

To update the environment:

    $ vagrant provision

To work on a project, clone it to the `src` directory and it will be
available in the VM at `/vagrant/src`.
