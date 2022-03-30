Ansible playbook to install the excellent ZFS utililty, [sanoid](https://github.com/jimsalterjrs/sanoid), by @jimsalterjrs 

Tasks:
+ installs sanoid
+ copys ```sanoid.conf``` to /etc/sadoid/
+ enables the systemd timers

*example use*
```bash
ansible-playbook -i inventory.ini main.yaml --connection=local -K
```