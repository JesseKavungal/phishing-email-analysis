# Email Header Analysis 

Using Sublime Text, I opened the email header in raw format to inspect the sender's details. The initial "**Received**" header read as follows:

"Received: from DM4P223MB0544.NAMP223.PROD.OUTLOOK.COM (2603:10b6:8:a6::5) by LV3P223MB0968.NAMP223.PROD.OUTLOOK.COM with HTTPS; Tue, 31 Oct 2023 19:10:10 +0000"

While the "From" address displayed as "Outlook Support Team," the actual "From" and "Reply-To" addresses were:

"From: Outlook Support Team <social201511138@social.helwan.edu.eg>"

This mismatch is a strong indicator of phishing, as the email claims to be from Outlook but uses an untrusted domain (helwan.edu.eg).
![Image1](https://github.com/user-attachments/assets/f6a1155d-97ce-4f48-b0ec-39243e702d83)

![Image2](https://github.com/user-attachments/assets/45c08a4a-7388-4f93-9e17-42b361a34f2a)
