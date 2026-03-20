# Active-Directory-Lab

## Objective
The Active Directory Lab project aimed to establish a controlled environment for simulating and detecting cyber attacks. The primary focus was to ingest and analyze logs within Splunk, generating test telemetry to mimic real world attack scenarios. This experience was designed to deepen understanding of network security and defensive strategies.

### Skills Learned
- Using Splunk to write custom queries
- Deploying a Windows AD DS environment to manage users
- Creating a SOAR workflow with Shuffle

### Tools Used
- Vultr as the cloud platform to deploy a Windows virtual machine and set up the firewall
- Active Directory to manage the users
- Splunk as the SIEM through the Universal Forwarder to detect unauthorized logins
- Slack and Email for alerting the analyst
- Shuffle as the SOAR platform to respond to the login attempt, communicate with the analyst, and disable the Active Directory account

## Steps
1. Setup the Active Directory Enviromnet
2. Create a Splunk account to ingest logs
3. Generate Unauthorized login attempts
4. Create a custom Splunk query
5. Create an automated respose with Shuffle to alert the analyst and disable compromised accounts
