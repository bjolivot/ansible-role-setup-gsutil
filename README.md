setup-gsutil
==================

Deploy gsutil on debian like OS



How to use 
----------

Put service_account.json file in playbook's root dir and include role

    - hosts: server
      roles:
         - { role: setup-gsutil}

License
-------

Licensed under the MIT License. See the [LICENSE](LICENSE) file for details.


Author Information
------------------

See my other "work on my computer" ansible things on https://www.github.com/bjolivot
