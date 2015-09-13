# Ansible role to Install Loggly - Tweaked for my DigitalOcean needs - use at your own risk

This Ansible role installs/updates and configures loggly,
based on a fork.

## Variables

``` yaml
loggly_account_name:
loggly_token:
loggly_username:
loggly_password:
app_name:
app_path:
```
You can also add a vars folder to your project folder and have your variables served by adding them to a file and calling it in your playbook.

```yaml
- hosts: localhost
...
  vars_files:
    - vars/default_vars.yml
...
```

## Dependencies

None

## License

MIT
