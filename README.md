# Active-Directory-Lab (Nov 2025 – Jan 2026)

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
1. Setup the Active Directory Environmnet
<img width="879" height="380" alt="Screenshot 2026-03-22 125319" src="https://github.com/user-attachments/assets/3557ee5e-5dc1-456c-8290-3d1ce2d7d7f6" />
Ref 1: Active Directory
<br> </br>
2. Create a Splunk account to ingest logs
<img width="1917" height="1010" alt="Screenshot 2026-02-22 193650" src="https://github.com/user-attachments/assets/17a92668-f7eb-49d8-ae91-dbca3ba930a8" />
Ref 2: Splunk Setup
<br> </br>
3. Create a custom Splunk query
<img width="1919" height="496" alt="Screenshot 2026-02-24 111929" src="https://github.com/user-attachments/assets/3ba7963c-f1db-4d97-9e41-2c3441b69b18" />
Ref 3: Custom Splunk Query
<br> </br>
4. Generate Unauthorized login attempts
<img width="1887" height="910" alt="Screenshot 2026-02-24 154618" src="https://github.com/user-attachments/assets/e6aeae48-af54-4381-9daa-3fbc081c5032" />
Ref 4: Unauthorized Logins
<br> </br>
5. Create an automated response with Shuffle to alert the analyst and disable compromised accounts
<img width="1144" height="363" alt="Screenshot 2026-02-26 151449" src="https://github.com/user-attachments/assets/73e59055-6c01-43d1-aa4c-06e3585936ee" />
Ref 5: Shuffle Automation
<br> </br>
<img width="1546" height="947" alt="Screenshot 2026-02-26 153125" src="https://github.com/user-attachments/assets/393b898d-3b4d-4081-8561-212681597ce6" />
Ref 6: Email Notification
<br> </br>
<img width="1393" height="614" alt="Screenshot 2026-03-22 130611" src="https://github.com/user-attachments/assets/0c4a4ee5-b4cc-487e-b505-cb75eeba99fa" />
Ref 7: Slack Notification
<br> </br>
<img width="1208" height="836" alt="Screenshot 2026-02-26 151737" src="https://github.com/user-attachments/assets/03349b63-4d9e-4545-905d-08acb3a49187" />
Ref 8: Account Disabled

