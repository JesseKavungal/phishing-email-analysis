# Phishing Analysis Report Template

## Headers

**Date:** Tue, 31 Oct 2023 10:10:04 -0900  
**Subject:** The subject of the email indicates that the Outlook account is flagged for unusual activity  

**To:** dderringer@mighty-solutions.net  
**From:** Outlook Support Team <social201511138@social.helwan.edu.eg>  

**Reply-To:**  
**Return-Path:** social201511138@social.helwan.edu.eg  

**Sender IP:** 40.107.22.60  
**Resolve Host:** mail-am6eur05on2060.outbound.protection.outlook.com  

**Message-ID:** `<JMrByPl2c3HBo8SctKnJ5C5Gp64sPSSWk76p4sjQ@s6>`

---

## URLs

- `hxxps://raw.githubusercontent.com/MalwareCube/SOC101/main/assets/01_Phishing_Analysis/microsoft.jpg`  
- `hxxps://0.232.205.92.host.secureserver.net/lclbluewin08812/`

---

## Attachments
 
- **Attachment Name:**   NIL
- **MD5:**  NIL
- **SHA1:**  NIL
- **SHA256:**  NIL

---

## Description

This email claims to be from the Microsoft Outlook support team, warning the recipient about unusual activity in their account. 
The recipient is prompted to click on the link to log in and verify their credentials, which likely leads to a credential-capturing phishing page.

---



### Sender Analysis
- The sender claims to be from Microsoft Outlook support, but the return path and email domain (`social.helwan.edu.eg`) do not belong to Microsoft.
- The sender’s domain, `social.helwan.edu.eg`, does not appear to be associated with Microsoft.
- This discrepancy suggests the domain may be compromised and used by attackers for phishing purposes.

### URL Analysis

**URL:** `hxxps://0.232.205.92.host.secureserver.net/lclbluewin08812/`  
- **Current Status:** The URL is inactive at the time of analysis. However, prior public scans on URLscan and VirusTotal flagged this URL as malicious.
- **Threat Intelligence:** URLscan has previously flagged this URL as malicious. VirusTotal has identified it as malicious according to one of 94 security vendors.

### Attachment Analysis

No Attachments 

---

## Verdict

**Malicious** - _Phishing Campaigns_

---

## Defense Actions

- Blacklist Malicious URLs and IPs
