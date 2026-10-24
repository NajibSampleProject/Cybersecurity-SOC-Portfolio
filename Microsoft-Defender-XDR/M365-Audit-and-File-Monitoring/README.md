# Lab Evidence

## Microsoft 365 Audit Logging & File Monitoring Lab

### Overview

This hands-on lab focused on enabling Microsoft 365 audit logging and file monitoring to improve security visibility and support investigation of user, administrator, and file activity.

### 1.What I Configured

Enabled Microsoft 365 audit logging
Enabled recording of user and administrator activity
Accessed Microsoft Defender security settings
Configured Microsoft Defender for Cloud Apps
Enabled file monitoring
Verified the security monitoring configuration
Enabled Microsoft 365 Audit Logging

### I accessed:

Microsoft 365 Admin Center → Security → Setup & configuration → Audit
I then enabled recording of user and administrator activity.
Audit logging helps security teams understand:
Who performed an action
What action occurred
When it occurred
Which Microsoft 365 service was involved

### Screenshot: Audit Logging 

![Microsoft 365 Audit Logging](screenshots/01-Audit-Log-Enabled.png)

### Microsoft Defender Audit
### 2. Enabled Microsoft 365 Audit Logging

Inside Microsoft Defender, I navigated to:

Setup & configuration → Audit

I reviewed the Audit page and enabled the recording of user and administrator activity where required.

Enabling audit logging allows security teams to record important activities performed within the Microsoft 365 environment.

This information can later support:
- Security investigations
- User activity analysis
- Administrator activity monitoring
- Incident response
- Compliance reviews

### Evidence:

![Microsoft Defender Audit](screenshots/01-Audit-Log-Enabled.png)

### Cloud Apps File Monitoring
### 3. Opened Microsoft Defender Settings

I then navigated to:

Setup & configuration → Settings → Cloud apps

From the Cloud Apps settings, I located:

Information Protection → Files

This section provides configuration options related to file monitoring.

### Evidence:

![Cloud Apps File Settings](screenshots/03-cloud-apps-settings.png)

### File Monitoring Enabled
### 4. Enabled File Monitoring

Within the Files settings, I verified that Enable file monitoring was selected.

Where required, I enabled the option and saved the configuration.

File monitoring provides additional visibility into file-related activities within supported Microsoft cloud environments.

### Evidence:

![File Monitoring Enabled](screenshots/04-file-monitoring-enabled.png)


### Security Relevance:

This lab helped me understand an important principle in cybersecurity:
You cannot effectively investigate activity that you are not logging.

Microsoft 365 audit logging provides visibility into user and administrator actions, while file monitoring helps security teams observe file-related activity.

A simplified security workflow is:

User Activity → Audit Logs → Monitoring → Investigation → Incident Response

These capabilities can assist SOC and security teams with identifying unusual behaviour and investigating potential security incidents.

### Skills Practised 
Through this lab, I gained hands-on experience with:
- Microsoft 365 Admin Center
- Microsoft Defender
- Microsoft 365 Audit
- Microsoft Defender for Cloud Apps
- Audit logging configuration
- User and administrator activity monitoring
- File activity monitoring
- Security visibility
- Cloud security administration
- Security investigation readiness

### Key Learning

My main takeaway from this lab was the importance of enabling logging and monitoring before a security incident occurs.

Audit logs can provide valuable evidence about:
- Who performed an action
- What action occurred
- When the activity occurred
- Which Microsoft 365 service was involved
This information can help security analysts reconstruct activity during an investigation and determine whether behaviour is legitimate or potentially suspicious.

