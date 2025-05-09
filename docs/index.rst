.. cashflower documentation master file, created by
   sphinx-quickstart on Wed Nov 16 18:28:29 2022.
   You can adapt this file completely to your liking, but it should at least
   contain the root `toctree` directive.


cashflower
==========

Cashflower is an open-source Python framework for actuarial cash flow models.

.. image:: https://acturtle.com/static/img/assets/turtle.svg
   :width: 240px
   :align: center

Key features:
 * **easy to use** - run your first cash flow model with just few commands,
 * **open source** - freely accessible to all users and available on PyPI,
 * **flexible** - integrate your project with other popular Python libraries.

Quick start
^^^^^^^^^^^

You're just a few commands away from running your first cash flow model with cashflower:

..  code-block:: bash
    :caption: terminal

    $ pip install cashflower
    $ python
    >>> from cashflower import create_model
    >>> create_model("my_model")
    >>> quit()
    $ cd my_model
    $ python run.py

Congratulations, you’ve just run your first cash flow model with cashflower!

Cheat sheet
^^^^^^^^^^^

A cheat sheet is a quick-reference document that provides essential code snippets and syntax examples.

You can download `the Cashflower cheat sheet (PDF) <https://www.acturtle.com/static/pdf/cheat_sheet.pdf>`_.

.. image:: https://acturtle.com/static/img/docs/cheat_sheet_mini.jpg
   :target: https://www.acturtle.com/static/pdf/cheat_sheet.pdf
   :align: center

License
^^^^^^^

Cashflower is distributed under `the MIT License <https://github.com/acturtle/cashflower/blob/main/LICENSE>`_.

Contributions and Support
^^^^^^^^^^^^^^^^^^^^^^^^^

Cashflower is an open-source project, and we welcome contributions from the community.
If you encounter any issues, have suggestions, or want to contribute to the development,
please visit our `GitHub repository <https://github.com/acturtle/cashflower>`_.


|

.. toctree::
   :maxdepth: 2
   :caption: Contents:

   user_guide
   advanced
   developer_guide
   modules
   Repository <https://github.com/acturtle/cashflower/>
   Blog <https://acturtle.com/>
