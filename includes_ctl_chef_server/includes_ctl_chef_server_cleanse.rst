.. The contents of this file are included in multiple topics.
.. This file describes a command or a sub-command for chef-server-ctl.
.. This file should not be changed in a way that hinders its ability to appear in multiple documentation sets.


The ``cleanse`` subcommand is used to re-set the |chef server| to the state it was in before the first time the ``reconfigure`` subcommand is run to destroy all data, configuration files, and logs. 

This subcommand has the following syntax:

.. code-block:: bash

   $ chef-server-ctl cleanse
