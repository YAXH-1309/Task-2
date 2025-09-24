📧 Phishing Email Analysis – Task 2 (Cyber Security Internship)

📌 Objective

The goal of this task is to analyze a phishing email sample and identify its suspicious characteristics. This exercise improves awareness of phishing tactics, email spoofing, header analysis, and threat detection.


---

🔎 Steps Performed

1. Collected a Sample Email

Used a mock phishing email pretending to be from PayPal.

Saved the raw email including headers.



2. Checked Sender Information

Sender email looked like: support@paypa1.com (note the “1” instead of “l”).

This is a classic case of email spoofing.



3. Analyzed Email Headers

Used Google Message Header Analyzer.

SPF/DKIM failed → email not from PayPal’s authorized servers.

Originating IP traced to an unknown server location.



4. Inspected Links and Attachments

Hovered over link: http://secure-paypal-login-update.com → fake site, not PayPal.

Found a .zip attachment named Invoice.zip, which is unusual for PayPal.



5. Reviewed Email Content

Urgent language: “Update your account in 24 hours or it will be locked.”

Grammar errors: “We has detect unusual activity.”

These are strong phishing red flags.





---

🛠 Tools Used

Email Client (Gmail sample) – to export raw email.

Google Message Header Analyzer – to check SPF, DKIM, IP.

Manual Inspection – hovering over URLs, checking content.



---

⚠️ Phishing Indicators Identified

1. Spoofed sender address (paypa1.com).


2. Failed SPF/DKIM authentication.


3. Mismatched URL (fake login site).


4. Threatening/urgent language.


5. Poor grammar and spelling mistakes.


6. Suspicious attachment (Invoice.zip).




---

📖 Key Learnings

Always check email headers to validate authenticity.

Hover before you click on links to check the real destination.

Be aware of social engineering tactics (urgency, fear, fake rewards).

Never open unexpected attachments.


# Task-2
