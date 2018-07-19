# OpenLDAP-Cluster-Zabbix
Monitoring OpenLDAP Cluster with Zabbix 3.4. It's a script that checks LDAP Provider - Consumer status, and sync status between them.

You should:
1) Put **ldap_check_status.sh** in LDAP **Consumer** and make it executable for zabbix user.

2) Put **openldap_cluster_status.conf** in /etc/zabbix/zabbix_agentd.conf.d directory in **LDAP Consumer**.

3) Import **zabbix_openldap_template.xml**.

4) Import **zabbix_openldap_value_mapping.xml**.

5) Modify the item parameter and replace with LDAP Provider FQDN or IP.

![OpenLDAP-Zabbix](https://i.imgur.com/ZY2OY9q.png)
