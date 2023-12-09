AWS CloudWatch Agent
=====================

Role to deploy AWS CloudWatch Agent

Requirements
------------

Role Variables
--------------

Definition and usage of variables could be found in defaults/main.yml.

Dependencies
------------

It is required to have the AWS Cli installed and configured. You can
install directly from aws or use the role (dorancemc.awscli)[https://github.com/dorancemc/ansible-awscli/]


Example Playbook
----------------

```yaml
- hosts: servers
  roles:
      - { role: dorancemc-ansible-CloudWatchAgent, tags: [ 'cloudwatchagent' ] }
```

License
-------

Apache 2.0

Author Information
------------------

- Dorance Martinez @dorancemc
