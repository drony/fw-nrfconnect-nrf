.. _getting_started:

Getting started
###############

To quickly get started with the |NCS|, use the `Getting Started Assistant <Getting Started Information_>`_ to set up your development environment.
Alternatively, check the :ref:`gs_installing` section for instructions on setting up your environment manually.

.. important::
   The Getting Started Assistant guides you through setting up your environment to work with the latest release.
   With the introduction of the :ref:`zephyr:west` tool, the way to clone the repositories has changed considerably.
   Therefore, if you work with the latest version of the |NCS| repositories instead of the latest release, follow the steps outlined in this section for cloning the repositories.

We recommend using SEGGER Embedded Studio for building your applications. See :ref:`gs_programming` for the download links and instructions.
In case you run into problems, see :ref:`gs_programming_ts` .

Once you are set up, check out the :ref:`samples`.
If this is the first time you work with embedded devices, it is probably a good idea to program an unchanged sample to your board first and test if it works as expected.
After that, pick a sample that is related to the application you want to create and start developing!

.. toctree::
   :maxdepth: 2

   gs_installing
   gs_programming
   gs_testing
   gs_modifying
