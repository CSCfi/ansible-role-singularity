[![Build Status](https://travis-ci.org/CSCfi/ansible-role-singularity.svg?branch=master)](https://travis-ci.org/CSCfi/ansible-role-singularity)

ansible-role-singularity
=========

Install and configure singularity 

https://singularity.lbl.gov

Requirements
------------

An already configured repository which has the singularity packages.

The WLCG Linux Repo and OpenScienceGrid have singularity packages.

Role Variables
--------------

see defaults/main.yml 

the settings in singularity.conf is defined with this list:

<pre>
singularity_settings:
</pre>

Dependencies
------------


Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - { role: ansible-role-singularity, x: 42 }

License
-------

MIT

Author Information
------------------

Inspiration from https://github.com/ryanolson/ansible-singularity
