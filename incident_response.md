Final Incident Report 
Incident Type: Credential Harvesting Phishing
Severity: High

Summary:
A simulated phishing email impersonating Microsoft Security was reported by a user. The email used domain typosquatting and urgency-based social engineering to lure the recipient into clicking a fraudulent login link. Header analysis revealed failed SPF and DMARC authentication, confirming the email was unauthorized.

Indicators of Compromise (IOCs):
Sender domain: micros0ft-support.com
Sending IP: 185.234.219.87
Malicious URL: login-microsoft-secure[.]com

Containment Actions:
Quarantined and removed the email from affected mailboxes
Blocked the malicious domain and URL
Checked for additional recipients within the organization
Monitored for suspicious login attempts

Preventive Measures:
Security awareness training for staff
Email filtering and anti-phishing controls
MFA enforcement
Periodic phishing simulations
