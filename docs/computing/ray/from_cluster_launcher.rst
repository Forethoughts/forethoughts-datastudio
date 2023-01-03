
=========================================
Ray cluster from Ray Cluster Launcher CLI
=========================================

Ray master branch includes `Ray cluster launcher for Staroid <https://docs.ray.io/en/master/cluster/cloud.html#staroid>`_.
This allows creating a ray cluster using standard ``ray up <cluster configuration yaml>`` CLI command.

Install Ray and dependency libraries
------------------------------------

First, install ray (1.1.0 or newer) and python dependency packages.

.. code-block:: bash

   $ pip install ray staroid kubernetes

Configure Staroid access token
------------------------------

Then, let's configure staroid access token. `Get access token <https://staroid.com/settings/accesstokens>`_ and set
``STAROID_ACCESS_TOKEN`` environment variable.

.. code-block:: bash

   $ export STAROID_ACCESS_TOKEN=[your access token]

Cluster configuration file
--------------------------
