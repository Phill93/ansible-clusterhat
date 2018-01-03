Role Name
=========

This Role installs and conifgurate all necessary software to use the Raspberry [Clusterhat](https://clusterhat.com)


Requirements
------------

* A Raspberry PI B+
* 1-4 Raspberry Zero
* The Clusterhat
* Raspbian

Role Variables
--------------

see [defaults/main.yml](defaults/main.yml)


Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: raspberries
      roles:
         - { role: phill93.clusterhat }

License
-------

[GPLv3](License.md)

Author Information
------------------

The Clusterhat is a Product from [8086.net](http://www.8086.net/).

All used Clusterhat related software can be found [here](https://github.com/burtyb/clusterhat-image).
