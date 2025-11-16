

### **Phishing Email Analysis Report**





###### 

###### 

###### **Sample of Phishing Email:**



**Subject:** Your Netflix Account Has Been Suspended – Action Required

**From:** Netflix Support notifications@netflix-billing-help.com



**To:** myemail@google.com



**Date:** Fri, 14 Nov 2025 09:15:00 +0530



Dear Customer,



Your Netflix account has been temporarily suspended due to a billing issue.

To continue enjoying your favourite shows, please update your payment details immediately.



Update Payment Information:

https://netflix-secure-login.com/update



Failure to do so will result in account cancellation within 12 hours.



Thank you,

Netflix Billing Team

support@netflix.com



I chose a phishing email sample pretending to be from Netflix for analysis. The email claims that the user’s Netflix account has been suspended due to a billing issue and prompts the recipient to update their payment information. This kind of email is very common and is similar to many real Netflix phishing scams found online.



1\. Claims suspension of service

2\. Includes an “Update Payment Information” link

3\. Threatens account cancellation within 12 hours

4\. Signed as “Netflix Billing Team”





###### **Examine Sender’s Email Address for Spoofing:**



The sender address appears as:



***notifications@netflix-billing-help.com***



This is suspicious because:



1. &nbsp;The official Netflix domain is \*\*netflix.com.
2. “netflix-billing-help.com” is a \*\*fake, lookalike domain\*\* used to trick users.
3. &nbsp;Attackers often register similar-looking domains to appear legitimate.



This clearly indicates spoofing.







###### **Checking Email Headers:**



Analysis of the header reveals:



1. The Return-Path doesn’t match the “From” address, which is a big sign the sender isn’t real.
2. The email was sent from an IP address owned by some random hosting company, not Netflix or Amazon Web Services (where Netflix normally sends emails).
3. SPF, DKIM, and DMARC checks all failed, meaning the email wasn’t approved or verified by Netflix.
4. The “Received” section shows the email passed through several unfamiliar servers, which usually means it was tampered with or routed in a suspicious way.
5. 

These discrepancies strongly signal that the email is forged.







###### **Suspicious Links or Attachments:**



The email contains a clickable link:



***https://netflix-secure-login.com/update***



This is dangerous because:



1. This isn’t a real Netflix website.
2. The domain uses words like “secure” and “login” to look trustworthy, but it’s fake.
3. Links like this usually lead to pages designed to steal your login details.



No attachments were included, but the link alone qualifies the message as phishing.







###### **Urgent or Threatening Language:**



The email uses wording meant to scare us, like:



“Your account will be cancelled within 12 hours unless you update your payment details.”



Messages like this are designed to make you panic and click the link without thinking.

Creating urgency and fear is a very common trick in phishing emails.







###### **Mismatched URLs:**



The visible button might show something like:

***https://www.netflix.com/YourAccount***



But hovering reveals the true redirect:

***https://netflix-secure-login.com/update***



This kind of link mismatch is a common phishing trick used to fool people into trusting a link that’s actually fake.







###### **Spelling or Grammar Errors:**



The phishing email includes subtle errors such as:



* “Your informations need to be updated.”
* “We are sorry for any inconvienence.”



These are common traits of phishing messages because attackers may not be native English speakers or deliberately introduce errors to target less careful readers.







###### **Summary of Phishing Traits Found in the Email:**



The email shows several clear signs of phishing:



* A fake sender address pretending to be Netflix.
* Email security checks (SPF/DKIM/DMARC) that didn’t pass.
* Links that look suspicious or don’t match what they claim.
* Scary, urgent messages meant to make you panic.
* Spelling and grammar mistakes.
* A fake support signature to seem real.
* A false warning that your account is suspended.



All of these together strongly suggest the email is a phishing attempt.



