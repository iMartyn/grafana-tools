grafana-tools
=============

Misc Grafana tools, like Import &amp; Export, and dashboard generation

Added by Martyn :

grafana-dashboards-import - takes the json created by grafana-dashboards-export and outputs SQL to import them into a mysql datastore in a format suitable for grafana 3

usage:
```python grafana-dashboards-import > output.sql```
