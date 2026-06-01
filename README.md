# Task-2-Phishing-Email-Analysis

## Objective

To analyze a suspicious email and identify phishing characteristics used by attackers to steal sensitive information.

## Sample Phishing Email

From: [support@paypa1.com](mailto:support@paypa1.com)

Subject: Urgent! Your Account Will Be Suspended

Dear Customer,

We detected unusual activity on your account. Please verify your account immediately by clicking the link below:

http://paypal-security-check.com/login

Failure to verify your account within 24 hours will result in account suspension.

Thank you,
PayPal Security Team

---

# Phishing Indicators Found

## 1. Sender Email Spoofing

The sender email address is "[support@paypa1.com](mailto:support@paypa1.com)".

The legitimate PayPal domain is "paypal.com".

The attacker replaced the letter "l" with the number "1" to deceive users.

Result:
This is a clear example of email spoofing.

---

## 2. Suspicious URL

The email contains the link:

http://paypal-security-check.com/login

This is not an official PayPal domain.

Attackers commonly create fake websites that resemble legitimate services.

Result:
The link is suspicious and may be used to steal login credentials.

---

## 3. Urgent and Threatening Language

The email contains phrases such as:

* "Urgent"
* "Immediately"
* "Within 24 hours"
* "Account Suspension"

These phrases create panic and pressure the victim into acting quickly.

Result:
This is a common social engineering technique.

---

## 4. URL Mismatch

The email claims to be from PayPal but directs users to a different domain.

Displayed identity:
PayPal

Actual destination:
paypal-security-check.com

Result:
The URL does not match the legitimate organization.

---

## 5. Grammar and Spelling Issues

Phishing emails often contain grammatical errors and awkward wording.

Example:
"Failure to verify your account within 24 hours will result in account suspension."

Although minor, the wording appears unusual compared to official communications.

Result:
Language quality raises suspicion.

---

## 6. Header Analysis Findings

Email headers can be analyzed using free tools such as MXToolbox Header Analyzer.

Potential findings:

* SPF Failure
* DKIM Failure
* DMARC Failure
* Mismatched Return-Path
* Suspicious originating IP address

Result:
Authentication failures indicate possible spoofing.

---

## 7. Social Engineering Techniques

The attacker attempts to gain the victim's trust by impersonating PayPal.

Methods used:

* Authority (pretending to be PayPal)
* Fear (account suspension)
* Urgency (24-hour deadline)

Result:
The email uses social engineering to manipulate users.

---

# Conclusion

The analyzed email contains several phishing indicators including sender spoofing, suspicious links, urgency tactics, URL mismatch, and social engineering techniques. Based on the evidence, the email is classified as a phishing email designed to steal user credentials.

---

# Outcome

Through this task, I learned how to:

* Identify phishing emails
* Detect email spoofing
* Analyze suspicious links
* Examine email headers
* Recognize social engineering tactics
* Improve email threat detection skills

These skills help in protecting users and organizations from phishing attacks.
