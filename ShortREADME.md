# Task2_Analyze-Phishing-Email-
 Identify phishing characteristics in a suspicious email

### 1. Obtain a sample phishing email - Sample.

<img width="1394" height="868" alt="image" src="https://github.com/user-attachments/assets/4dfcffc4-ecd4-404d-bd1f-0db2d465d3b2" />

###  2. Examine sender's email address for spoofing.

*Red Flag: Sender's email address is : services@paypal-accounts.com* <br>
**Domain Spoofing detected: Use of "paypal-accounts.com" instead of "@paypal.com"**

### 3. Check email headers for discrepancies 

*Header analysis shows - Team Support - missing proper authentication and no info as below*

<img width="241" height="348" alt="image" src="https://github.com/user-attachments/assets/96edb709-0681-4c00-a50f-b4e74c2adde3" />

*Taken from Header analysis tool - https://cybercheck360.com/tools/email-header-analysis*

###  4. Identify suspicious links or attachments.

**"Confirm Your Information" button most likely redirects to fake PayPal login page designed to steal credentials** <br>

Additionally, there is no visible url shown in the email - seems to be suspicious 

### 5. Look for urgent or threatening language in the email body.

*Multiple tactics - threatening have been identified* <br>
$Example$ <br>
*"Your account access has been limited"* <br>
*"You have 24 hours to solve the problem"* 

**This highlights false urgency**

### 6. Note any mismatched URLs

*a) The email cannot verify the actual destination  without hovering  <br>
b) The sender domain already shows mismatch as specified previously   <br>
c) The confirm Button likely leads to a fraudulent domain falsifying domain address* 

### 7. Verify presence of speling or grammar errors.

*a) "We are sorry to inform you that you no longer have access" -  phrasing suspicious  <br>
b) Missing punctuation: "Your PayPal account is limited, You have 24 hours" should be "limited. You have"  <br>
c) "We believe that your account is in danger from unauthorized users" - weird usage of words coming from Paypal template* 


###  8. Summarize phishing traits found in the email

*High Risk Indicators:* <br>

1. Spoofed domain: paypal-accounts.com <br>
2. Account threat: Claims account limitation and permanent disability <br>
3. Time pressure: 24-hour deadline  creates fake urgency  <br>
4. Data harvesting: Request for "confirm account details" - redirecting to fake domain <br>
5. Suspicious button: Unclear destination link <br>
6. Poor professional language used: Multiple language issues <br>
7. Generic greeting: "Dear PayPal customer" instead of actual name 


#### Interview questions - Answers 

1. What is phishing? <br>
*A. Phishing is a cybercrime where attackers impersonate legitimate organizations through fraudulent emails, websites, or messages to steal sensitive information* <br>

2. How to identify a phishing email? <br>
*A. We can look for suspicious sender addresses, urgent/threatening language or mismatched URLs, unexpected attachments, and verify the sender's domain*  <br>

3. What is email spoofing? <br>
*A. The practice of forging email headers to make messages appear as if they come from a trusted source*  <br>

4. Why are phishing emails dangerous? <br>
*A. They can steal login credentials, financial information, and personal data, leading to identity theft, financial fraud, and account takeovers*  <br>

5. How can you verify the sender’s authenticity?  <br>
*A. Check if the sender's email domain matches the organization's official domain*  <br>

6. What tools can analyze email headers?  <br>
*A. We can use email header analysis tools include MXToolbox Header Analyzer or Cybercheck360*  <br>

7. What actions should be taken on suspected phishing emails?  <br>
*A. We should never click links or download attachments, report it to your IT security teamand run security scans*  <br>

8. How do attackers use social engineering in phishing?  <br>
*A. Attackers exploit human psychology by creating urgency, fear, authority and trust.*  










