.. This is an included how-to. 


To view permissions for an environment object:

#. Open |opscode manage|.
#. Click |opscode manage policy|.
#. Click |opscode manage policy_environments|.
#. Select an enviromnent.
#. Click the |opscode manage tab_permissions| tab.

   where:

   .. list-table::
      :widths: 60 420
      :header-rows: 1
   
      * - Permission
        - Description
      * - |opscode manage permission delete|
        - |permission delete| This permission is required for any user who uses the ``knife environment delete [object_name]`` argument to interact with objects on the |chef server oec| server.
      * - |opscode manage permission grant|
        - |permission grant| This permission is required for any user who configures permissions using the |opscode manage admin| tab in the |opscode manage| user interface.
      * - |opscode manage permission read|
        - |permission read| This permission is required for any user who uses the ``knife environment show [object_name]`` argument to interact with objects on the |chef server oec| server.
      * - |opscode manage permission update|
        - |permission update| This permission is required for any user who uses the ``knife environment edit [object_name]`` argument to interact with objects on the |chef server oec| server.