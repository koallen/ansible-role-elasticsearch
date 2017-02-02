Ansible Role: Elasticsearch
===========================

An Ansible role for deploying elasticsearch on Debian/RedHat family OS.

Requirements
------------

Java 7+ is required for elasticsearch. Please refer to [geerlingguy.java](https://galaxy.ansible.com/geerlingguy/java/) or [williamyeh.oracle-java](https://galaxy.ansible.com/williamyeh/oracle-java/). No dependencies on Java will be included for maximum flexibility.

Role Variables
--------------

Available variables are listed below along with their defaults

    elasticsearch_path_data: ""

Sets the `path.data` value in config file. It specifies where the data are stored.

    elasticsearch_network_host: ""

Sets the `network.host` value in config file. It specifies which interface to listen on for the service.

Dependencies
------------

None.

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - { role: koallen.elasticsearch }

License
-------

MIT

Author Information
------------------

You are welcomed to check out my blog [here](https://shawnliu.me).
