ansible-jira
=========

Ansible role to install jira and set-up either mysql or postgres to act as the backend datastore

Requirements
------------

This role assumes:

1) The availability of either postgres or mysql to act as a backend for jira. The database can either be local or remote to the jira host. A default install will provide jira configured to use it's internal test datastore but this is not recomended for production use

2) A suitable JRE or JDK is required to run Jira and should be made available on the target host

Role Variables
--------------

TBA

Dependencies
------------

None

Example Playbook
----------------

    - hosts: servers
      roles:
         - { role: cmstokoe.jira }

License
-------

Apache 2.0

Author Information
------------------

This role was created by [Chris Stokoe](https://github.com/cmstokoe) a Systems Engineer and Technical Architect with over 20 years experience working in information-science.
