# FUTURE_CS_02
## Phishing Email Detection & Awareness System


## 1.Project Objective
To demonstrate a systematic approach to analyze real phishing email samples , identify common phishing indicators , classify email risk clearly.

## 2.Tools used
- Header Analysis: Google Admin Toolbox (https://mxtoolbox.com/EmailHeaders.aspx) & MXToolbox (https://toolbox.googleapps.com/apps/messageheader/).
- URL,files and IP Investigation:URL Checkers (https://www.virustotal.com/gui/home/upload) , https://www.abuseipdb.com/

## 3.Analysis Approach
- Collection: Securely obtaining phishing samples (.eml files) for inspection.
- Header Analysis: Examining SPF (Sender Policy Framework) , DKIM (Domain Keys Identified email) , and DMARC(Domain based Message Authentication,Reporting and conformance) records to verify sender authenticity.
- Attachments Inspection: Checking for files containing malware and hidden URL redirects.
- Risk Classification: Categorizing samples (Safe/Suspicious/Phishing) based on indicators like urgency, generic greetings, and malicious links.
- Documentation: Creating non-technical reports to educate end-users on "Red Flags."
