# Network switch monitoring using SNMPv3
Simple Network Management Protocol (SNMP) is an Internet Standard protocol for collecting and organizing information about managed devices on IP networks and for monitoring or modifying that information to change device behavior.

### Objective of the POC
SSPL currently does not support the monitoring of private/public switches.
This POC (Proof of Concept) demonstrates how we can monitor network switches
(like Mellanox SN2100) using SNMPv3 for the future releases of LDR.

### The SNMP POC tried to achive the following things
1. Try SNMPv1, SNMPv2 protocol implemetation using linux virtual machines in agent and the manager roles.
1. Get the management information from Mellanox SN2100 switch and linux agent using SNMPv3 protocol.
1. Configure Manager to recive  SNMPv3 informs for any registered v3 agent.

### Links to the work done during the POC

* [SNMP Architechture](./docs/snmp_arch.md)

* [Resources Used](./docs/resources.md)

* [SNMP GET implementation](./docs/snmp_get_impl.md)

* [SNMP v3 INFORM implementation](./docs/snmp_inform_impl.md)

* [SSPL_trap.py {Update Sensor For the future help}](./src/SNMP_traps.py)

### Please recheck any updated api's from the official documenation
* [Net-Snmp Documentation](http://www.net-snmp.org/)
* [Pysnmp Documentation](https://pysnmp.readthedocs.io/en/latest/)