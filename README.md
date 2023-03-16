shosts
=========

Deploy shosts files.

Requirements
------------

None.

Role Variables
--------------

Available variable

Available variables are listed below, along with default values (see `defaults/main.yml`):

    root_shosts

Dependencies
------------

None.

Example Playbook
----------------

    - name: Assure root shosts
      hosts: managed
      roles:
        - role: shosts
          vars:
            root_shosts:
              "source_host1":
                - "uname1"
                - "uname2"
              "source_host2":
                - "uname1"

License
-------

This project is licensed under the MIT License.

Author Information
------------------

This role was created in 2022 by Anthony Pagan.
