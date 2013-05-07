snmp2sapwalk
============

This is a Google App Engine project that allows output generated by Net-SNMP's
snmpwalk utility to be converted for use with the SimpleAgentPro simulator
software from SimpleSoft, Inc.

The snmpwalk output must be created with specific arguments to snmpwalk.
Otherwise, snmpwalk will perform irreversible formatting on the data.

```
snmpwalk -v2c -c <community> -ObentU <ipaddress> .1 > myagent.snmpwalk
```
