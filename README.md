# Phishing-Email-Analysis-Task2
Analysis of a phishing email impersonating IDFC FIRST Bank. Includes header inspection, domain spoofing evidence, and security protocol breakdown (SPF/DKIM/DMARC). Demonstrates email threat detection techniques  

![image alt](https://github.com/Premreddy-28/Phishing-Email-Analysis-Task2/blob/48e870cd2e68d7c8f13f94b2d742dcc938cfd9ff/Screenshot%202025-08-06%20094709.png)

**1. Suspicious Sender Domain**
Claimed Sender is "IDFC FIRST Bank" but Actual Domain is smt.plusoasis.com. Legitimate banks use their official domain (e.g., @idfcfirstbank.com).plusoasis.com is unrelated to IDFC and appears fraudulent.  

**2. Generic Greeting**
"Hi Sir" instead of addressing the recipient by name. Banks personalize emails with your full name.  

**3. Unverified Security Claims**
"Standard encryption (TLS)" is mentioned, but TLS alone doesn’t guarantee legitimacy. The email’s origin (ft.openstackmail.com) is not an IDFC-associated server.

**4. Mailed-by vs. Signed-by Mismatch**
Mailed-by is ft.openstackmail.com (third-party service) and Signed-by is smt.plusoasis.com (suspicious domain). Legitimate banks use their own infrastructure.

**5. Urgency Tactics**
"Just one step left" pressures the recipient to act quickly (common in phishing).

**6. Reply-to Address**
Replies go back to info@smt.plusoasis.com, not an official IDFC domain.



