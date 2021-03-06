---
id: network-firewalls-cisco-asa-snmp
title: Cisco ASA
---

| Current version | Status | Date |
| :-: | :-: | :-: |
| 3.3.3 | `STABLE` | Jun  4 2019 |

## Prerequisites

This chapter describes the prerequisites installation needed by plugins to run.

### Centreon Plugin

Install this plugin on each needed poller:

``` shell
yum install centreon-plugin-Network-Firewalls-Cisco-Asa-Snmp
```

### SNMP

It's necessary to enable SNMP on your equipement

## Centreon Configuration

### Create a host using the appropriate template

Go to *Configuration \> Hosts* and click *Add*. Then, fill the form as shown by
the following table:

| Field                   | Value                        |
| :---------------------- | :--------------------------- |
| Host name               | *Name of the host*           |
| Alias                   | *Host description*           |
| IP                      | *Host IP Address*            |
| Monitored from          | *Monitoring Poller to use*   |
| Host Multiple Templates | Net-FW-Cisco-Asa-SNMP-custom |

Click on the *Save* button.

