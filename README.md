# Description
Quick and dirty Ansible playbook to stop and start the OSD services on your OSD hosts

# Stop Services
$ ansible-playbook osd_services.yml -kK --tags stop -i inventory

# Start Services
$ ansible-playbook osd_services.yml -kK --tags start -i inventory