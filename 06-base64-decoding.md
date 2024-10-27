# Base64 Encoded Content

The email contained sections of Base64 encoding, which attackers often use to obfuscate links or payloads in phishing attempts. 
After decoding the Base64 content, I discovered it led to a Microsoft login page that was designed to redirect the user to a fake sign-in page. 
This is a common technique for capturing credentials from unsuspecting users.

![image](https://github.com/user-attachments/assets/f73a9e27-2ca8-42a2-a296-47c328826d6a)
