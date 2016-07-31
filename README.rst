PWDGEN
======

.. image:: https://badges.gitter.im/al3xv3gas/pwdgen.svg
   :alt: Join the chat at https://gitter.im/al3xv3gas/pwdgen
   :target: https://gitter.im/al3xv3gas/pwdgen?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge

About
=====
PWDGEN is an example application. It is supposed to illustrate how to build a CLI using
the NIGHTHAWK module. This application assumes the following situation: A user has to think of
a password and cannot come up with one. This application however, solves the problem by generating
a number of key codes. This number of key codes is specified by the user. As and additional helper,
a TXT file is created, containing all the generated key codes. After using this application, the folder
in which the application was run should not contain a log file if PWDGEN has been run previously in the
same directory and the  directory has been cleared of the log file created by the user during that
previous session.

Usage
=====
Install PWDGEN with Git:

.. code-block:: bash

    $ git clone https://github.com/al3xv3gas/pwdgen
    $ cd pwdgen
    $ python setup.py install
    

Import it into Python:

.. code-block:: bash

    >>> import pwdgen

Changelog:
==========
.. code-block:: bash

    version 2016.0:
        - initial release
        - minor optimizations
        

Direct download:
================

Issues: https://github.com/al3xv3gas/pwdgen/issues
Download: https://github.com/al3xv3gas/pwdgen/releases
Help: Gitter
