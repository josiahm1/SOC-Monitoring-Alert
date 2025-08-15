# SOC-Monitoring-Alert

## Objective
This project is aimed to show I have a foundation in monitoring, verifying, and containing security alerts.

### Skills Learned

- Advanced understanding of SIEM concepts and practical application.
- Proficiency in analyzing and interpreting different logs.
- Ability to verify if the alert is a true positive or false positive.
- Ability to verify if malware is malicious or not.
- Development of critical thinking and problem-solving skills in cybersecurity.

### Tools Used

- Security Information and Event Management (SIEM) system for log ingestion and analysis.

## Steps
### Step 1
This alert that shows a malicious macro has been executed is the event I have been tasked to look at. 

![SOC Monitoring Lab - 1](https://github.com/user-attachments/assets/bd10cf04-788c-4e2f-9f75-fd86295a5514)
### Step 2
I looked up the IP address in the log management section to confirm that this alert is real as it triggered the firewall, DNS, OS, and proxy server.

![SOC Monitoring Lab - 2](https://github.com/user-attachments/assets/e13e2cd5-eca3-49e3-a429-9b61e1915fb8)
### Step 3
I looked up the name of the file "edit1-invoice.docm" and confirm that the file had been executed.

![SOC Monitoring Lab - 3](https://github.com/user-attachments/assets/66646f0a-4638-4329-ba36-cf216050c7f4)
### Step 4
After going on Virus Total and typing in the hash value of the file, I found out this a known malicious file.

![SOC Monitoring Lab - 4](https://github.com/user-attachments/assets/3918ef4d-9eec-43a7-9808-9cc15dea24e0)
### Step 5
After identifying that this is a malicious file, the next step is to contain the host from the rest of the network to stop the spread of the malware.

![SOC Monitoring Lab - 5](https://github.com/user-attachments/assets/c36a7118-cf75-461e-acc8-7bc9b3e6eef4)
### Step 6
After further reviewing the email security logs, I indentified the email where this file was downloaded. This is a phishing email.

![SOC Monitoring Lab - 7](https://github.com/user-attachments/assets/66596182-efee-4eba-8f26-1406190f533a)
### Step 7
After I containing this endpoint, I ended this case. The playbook said to update this case to higher professionals and informed them this was a true positive.

![SOC Monitoring Lab - 6](https://github.com/user-attachments/assets/d2a73b74-685a-48a8-8f48-e4a3f42b2ccc)






