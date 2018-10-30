## Wordpress setup using Ansible on AWS EC2 instances

#### Run below given Ansible command
 - ansible-playbook -i inventory playbooks/wordpress.yml --vault-password-file ~/.vault_pass.txt

#### Note:
please create .vault_pass.txt file having your vault password

#### These playbooks will create two EC2 instances, one is Centos and another one is Ubuntu, and will install and setup two WP sites on each.

#### Centos:
       - website1.com
       - website2.com

#### Ubuntu:
       - website3.com
       - website4.com
