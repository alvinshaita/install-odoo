# Odoo installation script
Install Odoo on linux or aws server

This is a flexible Odoo installation script. It allows for custom configuration during installation.

`ODOO_USER` username of system user.

`PORT` port where Odoo will run.

`VERSION` Odoo version to install. `12` by default, for Odoo V12.

`IS_ENTERPRISE` To install an Enterprise version, set `True`, while `False` installs a Community version.

`SUPERUSER` Odoo master password for the installation.

## Clone repository
``git clone https://github.com/alvinshaita/install-odoo``

## Make the script executable
``sudo chmod +x odoo_installer.sh``

## Run the script
``sudo ./odoo_installer.sh``


