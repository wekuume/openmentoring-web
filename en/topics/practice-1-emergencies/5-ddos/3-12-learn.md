## Steps to fix the problem
![](recap.png)

Step 1: Contact a trusted person who can help with your website (your webmaster, the people who helped you set up your site, your internal staff if you have them and the company that hosts your site).
<br>
Step 2: Work with the company you bought your domain from (like EasyDNS, Network Solutions, GoDaddy) and change the ‘Time to Live’ or TTL to 1 hour.
<br>
This can help you redirect your site much faster once it comes under attack (the default is 72 hours, or three days).
<br>
This setting will often be found in ‘advanced’ properties for your domain, sometimes part of the SRV or Service records.
<br>
Step 3: Move your site to a DDoS mitigation service.  Examples:
-- Deflect.ca
-- Google’s Project Shield
-- CloudFlare’s Project Galileo
<br>
Step 4: As soon as you have regained control, review your needs and decide between a secure hosting provider or simply continuing with your DDoS mitigation service