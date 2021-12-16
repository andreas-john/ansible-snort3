Role Name
=========

install snort3 on a target ubuntu system.

based on https://snort-org-site.s3.amazonaws.com/production/document_files/files/000/008/108/original/Snort_3_on_Ubuntu_18_and_20.pdf from Noah Dietrich
Requirements
------------

role itself executed via ansible on ubuntu 20.04

ansible_instsrc

Role Variables
--------------

not any vars (yet?)

A description of the settable variables for this role should go here, including any variables that are in defaults/main.yml, vars/main.yml, and any variables that can/should be set via parameters to the role. Any variables that are read from other roles and/or the global scope (ie. hostvars, group vars, etc.) should be mentioned here as well.

Dependencies
------------

A list of other roles hosted on Galaxy should go here, plus any details in regards to parameters that may need to be set for other roles, or variables that are used from other roles.

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - { role: username.ansible-snort3, if: 'en0', pp_updatetime: '05:00' }

    or using the newer syntax:
    - hosts: servers
      tasks:
      - include_role:
          name: foo_app_instance
        vars:
          if: 'en0' # default en0
          pp_updatetime: '05:00' # default 13:05

License
-------

tbd

Further Informations
-------------------

according to the pdf splunk is also installed:
Addons for Snort3 working:
Snort 3 JSON Alerts
CyberShef for Splunk

additional plugins (verifying that your dataset is normalised correctly https://github.com/NDietrich/Splunk-Snort3-TA)
Splunk Common Information Model https://splunkbase.splunk.com/app/1621/
Splunk Datasets Add-on: https://splunkbase.splunk.com/app/3245/


Splunk Add-on for Nginx

ToDo:
https://github.com/schose/TA-routeros, mikrotik firewall collector

Author Information
------------------
Andreas JOHN, incinerator@gmx.at
