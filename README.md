Thoth: Core Template
====================

This role will create all OpenShift Templates required to deploy Thoth.

Role Variables
--------------

This role uses the oc command, and needs an OpenShift API URL and the user executing the playbook must be logged in.

Additionally a namespace to deploy the template into is required.

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: localhost
      roles:
        - role: thoth-station.core_templates
          openshift_api_url: "https://api.openshift.example.com/"
          namespace: "thoth-test-core"

License
-------

GPLv3

Author Information
------------------

The Thoth Station Team.