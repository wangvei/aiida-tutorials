.. _querybuilder:

Queries in AiiDA: The Querybuilder
==================================

This part of the tutorial is provided only in interactive mode through a Jupyter notebook, which you will be able to run in your browser.
To accomplish this we first need to start the Jupyter server, if you didn’t do it already at the very beginning of the tutorial.
First make sure you are connected to the virtual machine with local forwarding enabled, as described in section :numref:`connect`.
Then, on the virtual machine, first make sure your are in the ``aiida`` virtual environment:

.. code:: console

    workon aiida

If the virtual environment is successfully loaded, your prompt should be prefixed with ``(aiida)``.
Then you should download the :download:`notebook <../notebooks/querybuilder-tutorial.ipynb>` to your machine and save it as ``querybuilder-tutorial.ipynb``.
Finally, launch the Jupyter server from the directory where you downloaded the notebook and execute the following commands:

.. code:: console

    jupyter notebook --no-browser

If all went well, you should now be able to open up a browser on your local machine and point it to the following address ``http://localhost:8888/?token=2a3ba3...`` (replace the token with the one printed on output by the previous command).
This should now show you a directory navigator with the name of the file ``querybuilder-tutorial.ipynb`` you just downloaded.
To open the notebook, simply click on it.
The notebook will contain partial solutions to certain objectives.
The goal is for you to complete the snippets.
The solutions can also be downloaded from :download:`here <../notebooks/querybuilder-solutions.ipynb>` but try not to use them at first!

See below for a rendered version of the notebook:

.. toctree::

   QueryBuilder Notebook <../notebooks/querybuilder-tutorial.ipynb>

