# Dynamic_configurationOfHaproxyOverCloud
Task Description:  Use Ansible playbook to Configure Reverse  Proxy i.e. Haproxy and update it's configuration  file automatically on each time new Managed node (Configured With Apache Webserver ) join the inventory.  This setup should be over cloud

In addition you have to add privilage escalation and key pair in ansible.cfg file.Key must be in .pem format
and given permission to it. using chmod 400 <keyName>
