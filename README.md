Thoth: Core Template
====================

This role will create an OpenShift Templates required to deploy Thoth.

Role Variables
--------------

This role uses the oc command, and needs a OpenShift API URL and a Token to authenticate. Additionally a namespace to deploy the template into is required.


Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: localhost
      roles:
        - role: thoth-station.core_templates
          openshift_api_url: "https://api.openshift.example.com/"
          token: "{{ OCP_AUTH_TOKEN }}"
          namespace: "thoth-test-core"

License
-------

GPLv3

Author Information
------------------

The Thoth Station Team.