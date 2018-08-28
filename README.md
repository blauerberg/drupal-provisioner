# drupal-provisioner

## Getting Started

1. copy ssh_config.example as ssh_config.
2. change your_username and your_host_ip according to your environment.
3. copy config.yml.example as config.yml
4. execute `ansible-playbook -i hosts site.yml`
5. enjoy :)

## Configuration?

All the default configuration are in roles/*/defaults/main.yml.
You can override the configuration via config.yml.
