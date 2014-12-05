Inicio
======

.. _start:

What's OMSTD
------------

OMSTD (**O** pen **M** ethodology for **S** ecurity **T** ool **D** evelopers) is a proposal that attempts to be an easy to follow, practical and intuitive best-practices guide for hacking applications creation.

Development of hacking tools is not as hard as it might seem, as long as some guidelines are followed.

This guide is a follow up of my talk **"The power of reptiles: How to create security tools in Python"** at `IV Navaja Negra Conference <http://navajanegra.com>`_.

Current status
--------------

At the moment, this guide collects a limited number of use cases. There's plenty of work to do, and many ideas to be
documented.

With the help of everyone willing to contribute, I hope the number of uses cases and examples grows soon.

Disclaimer!!
------------

This text arises from experience, investigation made on my own, and the most frequent errors I've found when I've tried to create hacking tools, or used tools from other developers in my own projects.

The goal of this text is to be a small guide of good practices which I hope to expand in the future, for the creation of portable, well-designed and maintainable tools.

**The solutions presented here might not be the best or most optimal. They're just my suggestions**. Any improvement or suggestion is welcome.

How to use this guide
---------------------

Theory
++++++

If you're reading this guide for the first time, I recommend you to read the case studies in the order they're presented.

After getting familiarised with them, look for the particular use case you're after.

Examples
++++++++

Every example is under the **examples** directory. It holds several folders that match the block codes (:ref:`see below <categories>` ) and a sub-folder with 3-digit numbers, that references a particular case study. For example:

.. code-block:: bash

    example/bh/001/

Will contain the **case study 001** of the **behavioral** type (BH).

.. _getting-started:

Instructions to get started
---------------------------

The guide is structured in the same way it proposes

The instructions to be able to run all the case studies are as a follows:

1 - Install system dependencies
+++++++++++++++++++++++++++++++

.. code-block:: bash

    sudo python3.4 -m pip install virtualenvwrapper

2 - Configure virtualenvwrapper
+++++++++++++++++++++++++++++++

.. code-block:: bash

    echo "export WORKON_HOME=$HOME/.virtualenvs" > ~/.bashrc
    echo "export PROJECT_HOME=$HOME/Devel" >> ~/.bashrc
    echo "source /usr/local/bin/virtualenvwrapper.sh"  >> ~/.bashrc

3 - Search Python 3.4 interpreter
+++++++++++++++++++++++++++++++++

.. code-block:: bash

    locate python3.4 | grep bin/python | grep python3

.. code-block:: console

      ...
      /opt/local/Library/Frameworks/Python.framework/Versions/3.4/bin/python3.4
      /opt/local/Library/Frameworks/Python.framework/Versions/3.4/bin/python3.4-config
      /opt/local/Library/Frameworks/Python.framework/Versions/3.4/bin/python3.4m
      /opt/local/Library/Frameworks/Python.framework/Versions/3.4/bin/python3.4m-config
      /opt/local/bin/python3.4
      /opt/local/bin/python3.4-config
      /opt/local/bin/python3.4m

4 - Create virtual environment (or sandbox) for tests
+++++++++++++++++++++++++++++++++++++++++++++++++++++

.. code-block:: bash

    mkvirtualenv -p /opt/local/bin/python3.4 omstd

5 - Install OMSTD's global dependencies
+++++++++++++++++++++++++++++++++++++++

Under the root directory of the project, execute:

.. code-block:: bash

    pip install -r requirements.txt

6 - Install local dependencies for each example
+++++++++++++++++++++++++++++++++++++++++++++++

Each case study might contain its own **requirements.txt** with its own dependencies. That way, you're not forced to install all the possible dependencies of the project, unless you really need them.

To install dependencies for a particular example, repeat step 5 with the appropriate dependencies file.
