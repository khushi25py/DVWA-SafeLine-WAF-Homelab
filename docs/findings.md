# Findings

## SQL Injection Protection

Payload Tested:

1' OR '1'='1

Result:

* SafeLine detected the attack.
* The request was blocked.
* Security events were logged successfully.

## HTTP Flood Protection

A high volume of requests was generated from Kali Linux.

Result:

* SafeLine triggered Anti-Bot protection.
* Excessive requests were limited and challenged.

## Custom Deny Rules

A deny rule was created for the Kali Linux attacker IP.

Result:

* Traffic was blocked successfully.
* Rule hits were recorded in SafeLine.

## Security Visibility

SafeLine provided:

* Attack logs
* Traffic statistics
* Event monitoring
* Rule enforcement visibility
