Role Name
=========

update hostname and related files
on RedHat linux: /etc/hostname and /etc/hosts

Requirements
------------

None

Role Variables
--------------
  
**ansible_hostname_domain**: the new domain name (optional)  
>  default: keep existing domain name as found in /etc/hosts

**ansible_hostname_hostname**:  the new hostname (optional)  
>  default: keep existing hostname as found in /etc/hosts

Dependencies
------------

None

Example Playbook
----------------

    - hosts: localhost
      roles:
         - { role: ansible_hostname, ansible_hostname_domain: newdomain.local, ansible_hostname_hostname: newhostname }

License
-------

MIT

Author Information
------------------

Yimin Zheng. bzcnsh at yahoo.com  
