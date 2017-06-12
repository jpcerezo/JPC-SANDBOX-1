.. image:: https://readthedocs.com/projects/inetlabses-test1/badge/?version=latest
:target: https://inetlabses-test1.readthedocs-hosted.com/en/latest/?badge=latest
:alt: Documentation Status

Presentation of the Movistar Imagenio configs
======================

To check if containers are running, execute the following command. By default you should have 3 containers running

.. code-block:: text

  docker ps

To force containers to stop, execute

.. code-block:: text

  make stop

To access the CLI of the main container for debug,
Start a SSH session using the insecure_key provided in the repo and the script "docker.cli.sh"

.. code-block:: text

  make cli

For the Input containers named __open-nti-input-*__ you can access the logs directly from docker by running :

.. code-block:: text

  docker logs <container name or ID>
