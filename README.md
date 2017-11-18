gogs_call_api
=========

This role is a collections of plays that call the GOGS api.

Requirements
------------

Git >= 1.7.1 (command line tool) is required to be installed.  The `gogs_list_repositories.yml` installs *JMESPATH* in order to process the Json data returned by GitHub.

Role Variables
--------------

No variables are set in the `defaults/main.yml` or `vars/main.yml` files.

| Play | Inputs | Outputs |
|----------|----------|----------|
| gogs_create_repository | `gogs_url` </br> `gogs_repository_url` | None |
| gogs_list_repositories | `gogs_url` </br> `gogs_search_keyword` | None |
| gogs_push_repository | `gogs_repository` </br> `gogs_clone_folder` | None |
| gogs_configure_url | `gogs_token_url` </br> `gogs_clone_folder`| None |

Dependencies
------------

None.

Example Playbook
----------------

Each play contains instructions on how to use it.  Copy the usage details, uncomment, indent as required and change the variable values as appropriate.


License
-------

Apache

Author Information
------------------

Ian Turner </br>
Snr DevOps Technician
