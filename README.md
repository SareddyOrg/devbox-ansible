Personal Development Box
========================

This my personal development environment. There are many like it, but
this one is mine.

Installation:

    $ virtualenv env
    $ source env/bin/activate
    $ pip install -r requirements.txt

To create the environment:

    $ vagrant up

To update the environment:

    $ vagrant provision

To work on a project, clone it to the `src` directory and it will be
available in the VM at `/vagrant/src`.

Python
======

Versions:
- `2.7.13`
- `3.6.1`

Elixir & Erlang/OTP
===================

Versions:
- Erlang/OTP: `19.3`
- Elixir: `1.4.1`

Packages from: [Erlang Solutions](https://www.erlang-solutions.com/resources/download.html)

Golang
======

Versions:
- `1.8` (default)
- `1.7.5`

Go tools are installed in `/usr/local/go/VERSION/go`; `GOROOT` and `PATH`
environment variables are configured for the default version.
