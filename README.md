#Install
* cd /odoo/custom/addons
* sudo git clone https://github.com/luigisison/myhc.git
#Re-install
* cd /odoo/custom/addons
* sudo rm -rf myhc
* sudo git clone https://github.com/luigisison/myhc.git
#Update a file/directory (Example: partner.py)
* cd /odoo/custom/addons
* sudo rm -rf partner.py
* sudo wget https://raw.githubusercontent.com/luigisison/myhc/master/partner.py

