Phishing Email Analysis Report

Incident Type: Phishing (Credential Harvesting)
Confidence Level: High

1. Email Overview
The analyzed email impersonates Microsoft Security and claims that an unusual sign-in attempt was detected. The message urges the recipient to verify their account within a limited timeframe to avoid suspension.

2. Identified Red Flags
Domain impersonation through typosquatting (micros0ft-support.com)
Urgency-based language and time pressure (2-hour deadline)
Generic greeting (“Dear User”)
Embedded login verification link directing to a suspicious domain
Threat of account suspension to induce panic

3. Header Analysis
SPF: Fail — the sending IP is not authorized to send emails on behalf of the domain.
DKIM: None — no cryptographic signature present to verify message integrity.
DMARC: Fail — the domain’s policy rejects unauthenticated emails, confirming the message is unauthorized.

These results strongly indicate email spoofing and malicious intent.

4. Attack Classification
This email is classified as a credential harvesting phishing attack. The attacker’s objective is to trick the user into entering login credentials on a fraudulent website that mimics a legitimate Microsoft login portal.

5. Risk Assessment
If successful, this attack could lead to account compromise, unauthorized access to sensitive information, and potential lateral movement within the organization.
