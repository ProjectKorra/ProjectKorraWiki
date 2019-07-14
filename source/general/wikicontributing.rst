.. _wikicontributing:

========================
Contributing to the Wiki
========================

Setting Up the Environment
==========================

To begin editing the Wiki, you first need to your environment. `Python`_ is the only dependency required.

.. note:: When installing Python make sure to tick the ``Add Python to PATH`` option to be able to use python within your terminal/command prompt


1. Fork the GitHub repository and clone it.

.. note:: Remember to replace *exampleusername* with your actual github username

.. code:: bash

    git clone https://github.com/exampleusername/ProjectKorraWiki.git

The wiki is built with Sphinx using the *sphinx_rtd_theme* from ReadTheDocs.
Navigate to the directory you cloned the project to, then it will install all the requirements by running the following command in terminal / command prompt.

.. code:: bash

    pip install -r .\requirements.txt

This should install both Sphinx as well as the theme.

To check that Sphinx is correctly installed, run:

.. code:: bash

    sphinx-build -version

If Sphinx has been installed correctly, it should output sphinx-build and the version number For example ``sphinx-build 1.7.5``

Sphinx is required to view your changes locally before submitting them.

Viewing Local Changes
=====================

Once you have made some changes and are ready to see your edits locally, open terminal / command prompt and run

.. code:: bash

    .\make.bat html

This should build an HTML version of the wiki in the build folder in the root directory of your repository under the html folder.

Submitting Changes
==================

Now that you are happy with your changes remember to commit them using git and make sure to put a detailed message indicating what you have done.
If you are working on an issue, please include a link to the corresponding Trello Card/GitHub Issue in your commit description.

You are now ready to make a pull request which you can create `here <https://github.com/ProjectKorra/ProjectKorraWiki/compare>`_.

Remember to compare across forks as shown in the screenshot below

.. image:: /_static/images/contributing_pr_1.png

Once you are ready and content with your changes hit the *Create pull request* button.

Your changes will be reviewed and then merged by the Wiki Team. They may request changes and delay merging if they find any errors.

.. TODO:// More screenshots need to be placed here.
