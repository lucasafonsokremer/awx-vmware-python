Custom python script for VMware dynamic inventory. Created for collect VMware information for AWX inventories.

Created by Lucas Afonso Kremer

https://www.linkedin.com/in/lucasafonsokremer

Requirements
------------

* Libs:

```
- pyVmomi
```

* ENVIROMENT Variables:

```
- VMWARE_USERNAME
- VMWARE_PASSWORD
- VMWARE_SERVER
- VMWARE_VALIDATE_CERTS (true or false)
```

How to use
----------

* Import this script on AWX accessing "Resources > Inventory Scripts" menu.

Based on
--------

For informations about the original AWX VMware plugin:

[AWX plugin](https://github.com/ansible-collections/vmware/blob/master/scripts/inventory/vmware_inventory.py)

For informations about VMware variables, check this link:

[INI with vars](https://github.com/ansible-collections/vmware/blob/master/scripts/inventory/vmware_inventory.ini)
