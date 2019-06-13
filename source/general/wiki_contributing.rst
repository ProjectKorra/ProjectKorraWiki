========================
Contributing to the Wiki
========================

Setting up the environment
==========================

To begin editing the wiki we first need to set our environment up. The prerequisites needed is just `python <https://www.python.org/downloads/>`_.

.. note:: When installing python make sure too tick the ``Add Python to PATH`` option to be able to use python within your terminal/command prompt

First thing you need to do is to fork the git repository and then clone it.

.. note:: Remember to replace *exampleusername* with your actual github username

.. code:: bash

    git clone https://github.com/exampleusername/ProjectKorraWiki.git

The wiki is made with sphinx using the *sphinx_rtd_theme* from readthedocs. We've bundled all you need into one file.
Navigate to the directory you cloned the project to, then we will install all the requirements by running the following command in terminal / command prompt

.. code:: bash

    pip install -r .\requirements.txt

This should install both sphinx as well as the theme.

To check that sphinx is correctly install run:

.. code:: bash

    sphinx-build -version

If sphinx has been installed correctly it should output sphinx-build and the version number For example ``sphinx-build 1.7.5``

The reason we need sphinx is so you can view your changes locally before you submit your changes as a pull request.

Viewing your changes locally
============================

Once you have made some changes and you are ready to see your edits locally open terminal / command prompt and run

.. code:: bash

    .\make.bat html

This should build a copy of the wiki into the build folder in the root directory of your repository.
To view the wiki double click on ``build > html > index.html``

Submitting your changes
=======================

Now that you are happy with your changes remember to commit them using git and make sure to put a detailed message indicating what you have done.
If you are fixing/completing an issue please also reference the issue number in your commit message.

Now you are ready to make a pull request so go ahead and create one `here <https://github.com/ProjectKorra/ProjectKorraWiki/compare>`_.

Remember to select compare across forks as shown in the screenshot below

.. image:: /_static/images/contributing_pr_1.png

Once you are ready and content with your changes hit the *Create pull request* button

.. TODO:// More screenshots need to be placed here.
