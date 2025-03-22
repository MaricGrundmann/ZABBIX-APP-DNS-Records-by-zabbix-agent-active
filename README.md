# ZABBIX-APP-DNS-Records-by-zabbix-agent-active
Zabbix Template to monitor DNS Records
- Tested with v. 7.0.10

## Features
- Monitor any DNS Record

## Macros
|Macro|Value|Description|
|-----|-----|-----------|
{DOMAINS.ARRAY}|domain.tld:A,domain2.tld:MX|Array of monitored Records|
{DNSSERVER}|(optional)|Define custom DNS Server|

## Trigger
- (Warning) Record changed
- (High) Record no longer available
