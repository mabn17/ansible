# Ansible

A collection to setup my personal and work infrastructure on your local machine.

## Install command
Install prerequieistes and run the playbook.

```bash
./install
ansible-playbook local.yml --ask-vault-pass --tags {ENV}
```

Substitute {ENV} your enviroment. Currently supports:
 - `wsl2`
 - `ubuntu`
 - `mac` (Not yet tested)

### Commands

To encrypt your own file: `ansible-vault encrypt --ask-vault-password --output=output-file input-file`
