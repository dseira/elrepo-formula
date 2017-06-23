==============
elrepo-formula
==============

Install the ElRepo RPM Repo and GPG Key on CentOS 6/7 (not tested in RHEL).

.. note::

    See the full `Salt Formulas installation and usage instructions
    <http://docs.saltstack.com/en/latest/topics/development/conventions/formulas.html>`_.

Available states
================

.. contents::
    :local:

``elrepo``
----------

Installs the GPG key and the ElRepo RPM package for the current OS.

The repository is disabled by default.
