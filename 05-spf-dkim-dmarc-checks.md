# SPF, DKIM, and DMARC Checks

To verify the email's authenticity, I parsed the headers through **MX Toolbox** to examine SPF, DKIM, and DMARC records. The results indicated:

SPF: Passed
DMARC: Failed
DKIM: Failed
While the SPF pass suggests that the IP used was authorized to send on behalf of the domain, the DKIM and DMARC failures raise suspicion. 
These failures mean the email lacks proper authentication for ensuring that the content has not been altered and that unauthorized users cannot spoof the domain. 
This further suggests the possibility of a spoofed email.

![image](https://github.com/user-attachments/assets/1246be57-187f-4e2c-8235-871dfe24609a)


