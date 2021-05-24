Role Name
=========

An Ansible role to install [Apache JMeter](https://jmeter.apache.org). 

Requirements
------------

* Java 8 or above

Role Variables
--------------

Following are the variables you can set in `defaults\main.yml`:

* JMeter version (defaults to 5.4.1)
* Download URL
* JMeter base directory name

Dependencies
------------

To install Java, you can use this role `ansible-galaxy install lean_delivery.java`.

Example Playbook
----------------

Sample playbook to install JMeter.

    - name: JMeter
      hosts: servers
      roles:
        - jmeter-install

License
-------

MIT

Author Information
------------------

NaveenKumar Namachivayam

- [Blog](https://qainsights.com)
- [Free JMeter tutorials from basics to advanced](https://www.youtube.com/playlist?list=PLJ9A48W0kpRIjLkZ32Do9yDZXnnm7_uj_)
