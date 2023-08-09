# This repogitory playbooks based on following URL.
https://github.com/dell/iac-storage-automation/tree/main/ansible/powerprotect%20data%20manager

But, the uri is used in ad-hoc backup has already ommited and fix some part of other files.
I added restore to original playbook too.

# Ansible PowerProtect Data Manager
A collection of Ansible playbooks for Dell PowerProtect Data Manager. The playbooks leverage the URI module to interact with PPDM REST API. They include the following operations:

1. register an asset to an existing policy
2. perform an ad-hoc backup of an asset
3. restore the latest backup available to new vm(no test)
4. restore the latest backup available to original vm
5. Read Lock mysql talbes, perform ad-hoc backup and unlock mysql


