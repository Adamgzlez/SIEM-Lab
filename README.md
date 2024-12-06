# SIEM LAB

## Objective

The SIEM Lab was to establish an environment to understand Splunk using its searching capabilities, uploading files, and customizing reports and alerts for each given task to help mitigate future attacks. The focus was to analyze logs within a Security Information and Event Management (SIEM) system, analyzing file data that imitated real-world attack scenarios. This hands-on experience was designed to deepen understanding of Splunk as well as custom alerts, reports, and using Splunks search engine to analyze data.

### Skills Learned

- Basic understanding of SIEM concepts and practical application.
- Using fields to analyze and interpret network logs.
- Ability to generate and recognize attack signatures and patterns with reports.
- Enhanced knowledge of security vulnerabilities.
- Developing baselines and centering alerts around them. 

### Tools Used

- Security Information and Event Management (SIEM) system for log ingestion and analysis. (SPLUNK)
- Custom Reports and Alerts
- Splunk searching
- Uploading files
- Using fields

## Steps

1. Finding the DDOS attack and how long did it take to recover report.

[Speed Test File Used](https://drive.google.com/file/d/1sAIEh_vxhjJJpj3NiPx8Wele_-cfEZTK/view)

Based on the file that was uploaded and we searched for the DDOS attack was done around 2020-02-23 14:30:00 or 2:30 pm.

Systems fully recovered at 2020-02-23 23:30:00 or 11:30 pm. It took 9 hours to recover. 

[Report of Download Speeds
](https://github.com/Adamgzlez/SIEM-Lab/blob/main/Screen%20Shot%202023-05-09%20at%2011.05.03%20PM.png)

2. Uploading Nessus reports for and using that data to build an alert and report.

[Nessus File Used
](https://drive.google.com/file/d/1AonO8jAN4nKniZDw5qAYoMamBBXLpkdr/view)

A reports what is currently severe and what isn't to determine what we should work on. 

[Severity Report
](https://github.com/Adamgzlez/SIEM-Lab/blob/main/Screen%20Shot%202023-05-09%20at%2011.57.24%20PM.png)

An alert to help determine when a new vulerabilities are discovered and sends an alert to the team.

[Critical Vulnerabilities Customer Database Alert
](https://github.com/Adamgzlez/SIEM-Lab/blob/main/Screen%20Shot%202023-05-10%20at%2012.00.26%20AM.png)

3. Uploading admin login attempts and finding when the brute force occured and developing a baseline for a new alert.

[Admin Logs Used
](https://drive.google.com/file/d/1q5OJzVpvW0ExKuc8BtQ2LQOqpneLpUUy/view)

Based on the file that was uploaded the burte force attack occured around 2/20/2020 at 23:48:04 or 11:48 pm

Based on the bad logins every hour we can develop a baseline to have a 15 bad login threshold and then splunk should send an alert to notify the team.

[Brute Force Attack Alert
](https://github.com/Adamgzlez/SIEM-Lab/blob/main/Screen%20Shot%202023-05-10%20at%2012.32.45%20AM.png)
