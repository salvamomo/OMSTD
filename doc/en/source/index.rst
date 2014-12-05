.. OMSTD documentation master file, created by
   sphinx-quickstart on Mon Oct 13 22:59:01 2014.
   You can adapt this file completely to your liking, but it should at least
   contain the root `toctree` directive.

Welcome to OMSTD (Open Methodology for Security Tool Developers)
================================================================


.. figure:: ../../images/logo_200x200.png
    :align: left

OMSTD (Open Methodology for Security Tool Developers) is a series of case studies, grouped and categorised to serve as a guide to build security tools.

Although it can be used to create any kind of tool and in any language, its main focus is around hacking tools written in Python.

We recommend **A careful readthrough of the** :ref:`What's OMSTD <start>` **section in order to fully understand this guide**.

Author
------

This guide has been written and designed by `Daniel García (A.K.A. cr0hn) <http://cr0hn.com/me/>`_.

Official web and Twitter
------------------------

This guide, as well as the example code and presentations, are **free** and published in its repository on Github:

  `https://github.com/cr0hn/omstd <https://github.com/cr0hn/omstd>`_

You can follow additions, updates and news about this guide in the OMSTD Project twitter account:

  `@OMSTD_project <https://twitter.com/OMSTD_project>`_

Licenses
--------

Code
++++

All the code exposed here is distributed under `BSD 3-clausule license <http://opensource.org/licenses/BSD-3-Clause>`_. You can copy and redistribute it without restriction, preserving its authorship and without obtaining direct economic benefit of it.

Text
++++

This guide, as well as ll the text containing it, is distributed under the license: `Creative Commons 4.0 - Attribution-NonCommercial 4.0 International (CC BY-NC 4.0) <http://creativecommons.org/licenses/by-nc/4.0/>`_.

Collaborate with OMSTD
----------------------

Any idea, criticism (constructive, please) or collaboration is welcome. You can get in touch in the following ways:

+ E-mail: (cr0hn<<--AT-->>.cr0hn.com).
+ Issue queue on github.
+ Forking the project and submitting patches via Pull Requests.

If you're interested in helping, there's a `TODO.rst <https://github.com/cr0hn/OMSTD/blob/master/TODO.rst>`_ file containing the ideas not implemented yet.

One of the goals is to translate this guide to other languages. **IF YOU'RE COMFORTABLE IN OTHER LANGUAGES, YOU'RE WELCOME TO HELP US OUT, TOO!**


Who is this guide for?
----------------------

This guide is intended for security auditors and *pentesters* who need to create their own tools, most times *on-the-fly*, and want these to be more than just a simple script.

A *pentester* might be very good at hacking tasks, but not necessarily so good in development knowledge, best practices, design patters, etc.

**In order to use this guide, it's recommended to:**

+ Have a basic knowledge in Python 3 programming (**If you're comfortable with Python 2, you'll be able to follow the guide, too**, so fear not).
+ Have a basic knowledge of Information Security.

Guide structure
---------------

Blocks
++++++

Case Studies are divided in the following blocks:

.. _categories:

+ Development

  + **Structure and organisation (ST)**: How projects are organised.
  + **Behavioral (BH)**: How to interact with different frameworks.
  + **Interaction (IT)**: User interaction with other systems or environments.
  + **Language Specific (LS)**: Tricks, good-practices, and specific uses of the development language (Python in this case).
  + **Input/Output (IO)**: Reports generation (Word, Excel...), exporting data, importing external information (XML / JSON)...
  + **Redistribution (RD)**: Package creation, redistribution, compilation for several systems, portability to different environments, correct use of CVS, etc.
  + **Deployment (DP)**: How to correctly put our application in production.

+ **Hacking** (HH): Hacking-specific examples.
+ **Cracking** (CH): Cracking-specific examples.
+ **Malware** (MH): Malware-specific examples.
+ **Forensic** (FH): Forensic-specific examples.
+ **Hardening** (DH): Hardening-specific examples.

Identifying cases
+++++++++++++++++

With the goal of making this text as reusable as possible, case studies are identified using the following pattern:

    + XX[-EX]-YYY

      + **Problem**: Presentation and description of the case study.
      + **Solution**: Proposed solution.
      + **Implementation**: How to implement the solution.
      + **Annex**: This section might or might not be available. It'll contain clarifications specific to the case study.

Where:
    + **XX** : Block identifier.
    + YYY: Numeric value with the format: 001, 002, 003...
    + EX: If the identifier has this suffix, it means that the case study is a complete example, or sub-project.

Index
-----

.. toctree::
   :glob:
   :maxdepth: 2

   start
   contribute
   develop/index
   hacking/index
   cracking/index
   malware/index
   forensic/index
   hardening/index