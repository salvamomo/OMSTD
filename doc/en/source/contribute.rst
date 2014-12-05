How to contribute
=================

.. _contribute:

OMSTD is a free and open-source project. If you want to share your experience with other people, you'll be very welcome.

There are several ways to contribute to the project:

+ :ref:`Bug or error-fixing and improvements <contrib_sec1>`.
+ :ref:`Proposals for new case studies <contrib_sec2>`.
+ :ref:`Submission of a new case study <contrib_sec3>`.
+ :ref:`Help with translations <contrib_sec4>`.

.. _contrib_sec1:

Bug or error-fixing and improvements
------------------------------------

If you detect any **fail** or points that could be improved, you can:

+ **Raise a ticket** or issue, and it'll be dealt with as soon as possible (:ref:`Annex 2 <annex_2_patch_github>`).
+ Send a patch to correct the error (:ref:`Annex 1 <annex_1_patch_github>`).

.. _contrib_sec2:

Proposals for new case studies
------------------------------

If you want to **suggest a new case study**, **raise a ticket** with your proposal (:ref:`Annex 2 <annex_2_patch_github>`).

The proposal will be classified and cataloged based on the nature of the case study.

.. _contrib_sec3:

Submission of a new case study
------------------------------

The **preferred** way to submit new case studies is as follows:

+ **fork** the project (:ref:`Annex 3 <annex_3_patch_github>`).
+ **Submit a patch** with the new case study (:ref:`Annex 1 <annex_1_patch_github>`).

This way, everything will be logged and it'll be easer for everyone to follow updates.

.. _contrib_sec4:

Help with translations
----------------------

This case is very similar to the :ref:`Submission of a new case study <contrib_sec3>`, with a small difference:

+ **fork** the project (:ref:`Annex 3 <annex_3_patch_github>`).
+ **Copy the folder** :samp:`doc/es` to the :samp:`doc/LANG` directory, where *LANG* is the ISO code of the language for which you're creating the translation (e.g: If you're were **translating to French it'd be** :samp:`doc/fr`. You'll be working and translating in this directory.
+ **Submit a patch** with the new translation (:ref:`Annex 1 <annex_1_patch_github>`).

Annexes
-------

.. _annex_1_patch_github:

Annex 1: Patch submission in GitHub
+++++++++++++++++++++++++++++++++++

After *forking* and pushing the changes in code to the forked repository, follow these instructions:

1. Create a *Pull Request*:

.. figure:: ../../images/contrib-002.png

2. Create a new patch proposal by clicking *New pull request*:

.. figure:: ../../images/contrib-003.png

3. GitHub will detect the changes made, extracted from the commits of the changes, and prepare the request. To finish the submission, just click in *Create pull request*:

.. figure:: ../../images/contrib-004.png

.. _annex_2_patch_github:

Annex 2: Raising an issue in GitHub
+++++++++++++++++++++++++++++++++++

Opening a new issue in GitHub is trivial through its ticketing system:

1. Go straight to the issue queue by following https://github.com/cr0hn/OMSTD/issues, or go to the project home: https://github.com/cr0hn/OMSTD, and click in *Issues*, on the right sidebar.

.. figure:: ../../images/contrib-005.png

2. In this screen you can see all the open and raised issues. To create a new one, click in *New Issue*:

.. figure:: ../../images/contrib-006.png

3. To raise a new issue you need to give it a title and description. It's recommended that you are **concise in the title**, and **explain in detail** the issue, improvement, or proposal.

.. figure:: ../../images/contrib-007.png

.. _annex_3_patch_github:

Annex 3: Forking a project in GitHub
++++++++++++++++++++++++++++++++++++

Creating a fork of a project in GitHub is very easy:

#. Sign-in with your GitHub account,
#. Go to the project repository: https://github.com/cr0hn/OMSTD
#. Click in the top-right button with the text *Fork*. The next picture shows how:

.. figure:: ../../images/contrib-001.png