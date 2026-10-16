=================
API documentation
=================

Client
------

The client's ``project`` selects the default project for API calls. An
explicit ``params={'project': ...}`` on an individual call takes precedence.
Query dictionaries supplied by the caller are copied before adding defaults
or a target; they are not mutated. Server authorization still determines
which projects the caller can access.

.. autoclass:: pylxd.client.Client
   :members:


Exceptions
----------

.. autoclass:: pylxd.exceptions.LXDAPIException

.. autoclass:: pylxd.exceptions.NotFound

.. autoclass:: pylxd.exceptions.ClientConnectionFailed

Certificate
-----------

.. autoclass:: pylxd.models.Certificate
   :members:

Container
---------

.. autoclass:: pylxd.models.Instance
   :members:

.. autoclass:: pylxd.models.Container
   :members:

.. autoclass:: pylxd.models.Snapshot
   :members:

Virtual Machine
---------------

.. autoclass:: pylxd.models.VirtualMachine
   :members:


Image
-----

.. autoclass:: pylxd.models.Image
   :members:

Network
-------

.. autoclass:: pylxd.models.Network
   :members:

Operation
---------

.. autoclass:: pylxd.models.Operation
   :members:

Profile
-------

.. autoclass:: pylxd.models.Profile
   :members:

Project
-------

.. autoclass:: pylxd.models.Project
   :members:

Storage Pool
------------

.. autoclass:: pylxd.models.StoragePool
   :members:

Cluster
-------

.. autoclass:: pylxd.models.Cluster
   :members:

.. autoclass:: pylxd.models.ClusterMember
   :members:

.. autoclass:: pylxd.models.ClusterLink
   :members:
