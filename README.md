# ansible-wordpress-init
This ansible script start a new wordpress project
creating:
- latest wordpress structure
- database user
- database password
- database
- nginx config
> :warning: **if you run this script and the database user exist, the database passsword will be modify **: Be very careful here!

you just need modify:
ansible.conf 
 - .pem file
 - inventory file
inventario file
 - hostname
variables/vars.yml
 - variables
