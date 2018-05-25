This is a repository of ansible playbooks for hosts on VTLUUG's network

## Prerequisites

```ansible-galaxy install geerlingguy.ntp``` for ntp

```ansible-galaxy install geerlingguy.nfs``` for nfs



To execute a playbook on all machines, run 
```ansible-playbook main.yml -i hosts.cfg -K -u <user>```


To limit execution to specific hosts, run
```ansible-playbook main.yml -i hosts.cfg --limit=<host group> -k -u <user ```
