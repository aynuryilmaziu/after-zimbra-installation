# after-zimbra-installation
Configuring Zimbra compression settings using Ansible Playbook.

# Usage:
export ANSIBLE_INVENTORY=./inventory/
ansible-playbook playbooks/zimbra/dns.yml
ansible-playbook playbooks/zimbra/redirect.yml
ansible-playbook playbooks/zimbra/dumpster.yml
ansible-playbook playbooks/zimbra/sasl.yml
ansible-playbook playbooks/zimbra/smtp_dns_check.yml
ansible-playbook playbooks/zimbra/cbpolicyd.yml
ansible-playbook playbooks/zimbra/ldap_backup.yml
