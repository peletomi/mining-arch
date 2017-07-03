Node:
1. Install [Antergos](antergos.com)
2. Enable ssh service:
```
  sudo systemctl enable sshd.service && sudo systemctl start sshd.service
```

Provisioner:
1. Put hosts into `/usr/local/etc/ansible/hosts`.

2. Execute Ansible Playbook:
```
  ansible-playbook playbook.yml --ask-become-pass
```
