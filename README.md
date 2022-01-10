# odoo_upgrade_script

Used by odoo to allow migration of databases.
Link to download: https://upgrade.odoo.com/upgrade

Sample command given by Odoo to interact with them
```python <(curl -s https://upgrade.odoo.com/upgrade) test -d <your db name> -t <target version>```

To download the script: wget https://upgrade.odoo.com/upgrade -O odoo-upgrade.py


## Goals

The main goal of this is to allow versioning and see changes done by Odoo in their scripts

## Todo

* There is currently no automatisation of the file update
