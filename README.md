# Ansible Django Deployment (ADD)
This is an Ansible playbook for deploying Django application with virtual environment.

# Requirements

For control machine (*Machine that has ssh access to the servers and will be used to run the playbooks*), you will need the followings:

1. Ansible, check [Ansible Installation Guide](http://docs.ansible.com/ansible/latest/intro_installation.html).
2. SSH access for servers in host file.

# Organization

Each directory has a YAML file that represents Ansible playbook. Each YAML file has tasks which are responsible for Django deployment. Each tech stack (nginx, apache2, redis, celery, ..) has its own directory.

# Bugs and Other Issues

Please use the GitHub issue tracking system to report bugs, feature requests, or other issues with ADD.

# License

The ADD is released under the MIT license.

# Keeping in touch

* [Twitter](https://twitter.com/ahmedhosnycs)
* [LinkedIn](https://www.linkedin.com/in/ahmedhosnycs/)
* [Website](https://ahmedhosnycs.com)



