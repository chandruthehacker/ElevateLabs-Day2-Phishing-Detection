# 🛡️ Task 2: Phishing Email Detection

## 📌 Overview of My Work

In this task, I explored how hackers craft and send phishing emails, and what kinds of social engineering tactics they commonly use. I extensively studied over **100+ real phishing emails** to identify patterns and key indicators of phishing.

I discovered that most phishing emails are designed to appear **legitimate** and often include keywords like:

- **Urgent**
- **Password Reset**
- **Lottery Win**
- **Invoice Download**

These are commonly used to create a sense of urgency and trick recipients into acting without thinking.

---

## 🔍 What Hackers Do with Phishing Emails

Once a phishing email is opened, hackers may:

- Collect device information such as **IP address**, **Operating System**, and browser details.
- Perform **reconnaissance** using this data.
- Attach malicious files (e.g., **Trojan**, **Steganography**, or **Malware**) designed to:
  - Install spyware or keyloggers.
  - Encrypt the victim’s data (**Ransomware**) and demand payment.
  - Exploit vulnerabilities in outdated software.

Many victims unknowingly open these attachments, resulting in major security breaches, especially in organizations that lack strong **threat detection** measures.

---

## ⚠️ Precautions to Avoid Phishing

- **Never click suspicious links or attachments** in emails without verifying them.
- **Double-check the sender**—especially the **email domain and spelling**.
- Legitimate organizations **never ask for sensitive information** via email links.
- Be aware of **email spoofing**, where attackers forge the sender address.
- Use **header analysis** tools to inspect where the email actually originated.

---

## 🧠 My Work

I analyzed more than 100 phishing emails to understand their format, content, and psychological manipulation techniques. This helped me build an intelligent email analysis tool (explained below).

---

## 📧 Example: Sample Phishing Email

```txt
Subject: Your Package is Delayed / Unable to Deliver - Action Required  
From: noreply@ups-shipping-alerts.net  

Dear Customer,

We regret to inform you that there has been an issue with the delivery of your package (Tracking #1ZW234567890). The delivery was unsuccessful due to an unpaid shipping fee/incorrect address.

To reschedule your delivery and avoid further delays, please update your information and pay the outstanding fee of $2.99 by clicking on the link below:

[Link: hxxps://ups-tracking-portal.delivery-updates.org/reschedule]

Please note that if the information is not updated within 48 hours, your package will be returned to the sender.

Thank you,  
UPS Delivery Team
```

---

## 🔎 Suspicious Indicators:
- **Suspicious Sender Domain:** noreply@ups-shipping-alerts.net is not the official domain (ups.com).
- **Urgent Language:** Phrases like "Action Required" increase urgency.
- **Low-Value Fee:** The $2.99 fee is a trick to lure clicks without raising suspicion.
- **Phishing Link:** The URL is fake and not related to the official UPS website.
- **Lack of Official Contact Methods:** No phone number or manual instructions provided.
- **Social Engineering:** Uses psychological pressure to trick the user.

---

## ✅ Best Practices to Protect Yourself
- Never click links or download attachments from unknown sources.
- Verify email authenticity by checking the sender's domain and address.
- Use email header analysis tools.
- Enable multi-layered security like spam filters, firewalls, and antivirus software.
- Educate yourself and your team on phishing, email spoofing, and social engineering tactics.

---

### 📂 [SamplePhishMails/](https://github.com/chandruthehacker/ElevateLabs-Day2-Phishing-Detection/tree/main/SamplePhishMails)

This folder contains a collection of over **10 real-world phishing email samples** I analyzed during this project. Each sample demonstrates various phishing techniques, such as:

- Fake login pages  
- Spoofed domains  
- Suspicious keywords (e.g., *Urgent*, *Password Reset*)  
- Malicious attachments and phishing links  
- Social engineering tactics

These samples were used to improve the accuracy of my **AI-powered phishing detection tool** and can be useful for educational or analysis purposes.

---

## 🤖 My AI-Powered Phishing Email Detector Tool

To help users detect phishing emails more efficiently, I built a smart tool that integrates Google Generative AI through an API.

### 🔧 Features:
- Built with Python + Web Interface
- Users can paste email content into a text box.
- On clicking “Analyze Email”, it sends the content to Google’s AI with my custom prompt.
- Returns a detailed, well-formatted report labeling the email as:
✅ Legitimate
⚠️ Suspicious
❌ Phishing
- It has over 90% accuracy in identifying phishing emails.
- 🔗 [Source Code](https://github.com/chandruthehacker/phishing-email-detector)
- 🔗 [Own Blog](https://chandruthehacker.github.io/portfolio/projects/all-projects/phising-email-detector/phising-email-detector.html)


---

> 🧠 “Think before you click. Detect before you risk.”
