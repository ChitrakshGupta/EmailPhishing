# EmailPhishing
This repository demonstrates the creation and execution of email phishing campaigns using the Social Engineering Toolkit (SET). It is designed for educational and research purposes only, aiming to raise awareness about the risks of phishing attacks and how to mitigate them.

Here’s a well-formatted section you can add to your GitHub README file:

## **Tools for Phishing Attacks**

Below are some commonly used tools for performing phishing attacks (for educational and ethical purposes only):

- **Social-Engineer Toolkit (SET):** A comprehensive tool for penetration testing, including phishing campaigns.  
- **HiddenEye:** A tool primarily used for phishing attacks on social media platforms.  
- **Gophish:** An open-source phishing framework designed for ethical testing and security awareness training.  

### **Tool Used in This Project**  
For this project, we used the **Social-Engineer Toolkit (SET)** to demonstrate a phishing attack. SET provides a user-friendly interface and pre-configured templates for simulating realistic phishing emails.

### **Environment Setup**
- **Operating System:** Kali Linux  
- **Required Accounts:**  
  - **One Gmail Account**: Used to send phishing emails (as the attacker).  
  - **Another Gmail Account**: Used as the victim's account to receive the phishing email.  
Here’s your content restructured and formatted with placeholders for the images to be added later:

## **Steps Involved in the Phishing Attack**

### 1. **Installing SET (Social-Engineer Toolkit)**  
The first step is to install the Social-Engineer Toolkit (SET) on Kali Linux. Kali Linux provides a **sandbox environment** for penetration testing and ethical hacking, where you can safely perform simulated phishing attacks without putting the system at risk.  

``` sudo setoolkit
```




### 2. **Exploring SET's Options**  
In the screenshot above, you can see that SET provides various options for performing different tasks, most of which are used for penetration testing under the domain of web and app security.  

Phishing attacks fall under **social engineering**, where the attacker manipulates the target to reveal crucial information.  

![SET Options](https://github.com/ChitrakshGupta/EmailPhishing/blob/master/images/Picture1.png)  



### 3. **Choosing the Attack Method**  
SET offers many types of social engineering attacks. For this demonstration, we selected the **Credential Harvester Attack Method**, which is designed to capture login credentials like email IDs and passwords.  

![Credential Harvester Method](https://github.com/ChitrakshGupta/EmailPhishing/blob/master/images/Picture2.png)  
![Credential Harvester Method](https://github.com/ChitrakshGupta/EmailPhishing/blob/master/images/Picture3.png)  


---

### 4. **Using Web Templates for Phishing**  
In this step, we used SET's built-in **Gmail Web Template** to create a fake login page. This page is hosted on the Kali Linux machine to collect input (email ID and password) from the victim. Other templates are also available in SET for different purposes.  

![Gmail Web Template Setup](https://github.com/ChitrakshGupta/EmailPhishing/blob/master/images/Picture4.png)  


### 5. **Configuring the Phishing Page**  
We used the Kali Linux machine's IP address to host the fake Gmail login page. This ensures the phishing attack is conducted in a controlled environment.  

Next, we crafted a phishing email, embedding the IP address where the fake Gmail login page is hosted.  
![Phishing Email Configuration](https://github.com/ChitrakshGupta/EmailPhishing/blob/master/images/Picture5.png)  

---
![Phishing Email Configuration](https://github.com/ChitrakshGupta/EmailPhishing/blob/master/images/Picture6.png)


---

### 6. **Sending the Phishing Email**  
Below is the final phishing email sent to the target user. The email embeds the fake login page link, tempting the user with a message (e.g., offering money) to log in through their Google account.  

![Phishing Email Sent](https://github.com/ChitrakshGupta/EmailPhishing/blob/master/images/Picture7.png)  

---

### 7. **Victim Interaction with the Fake Page**  
Once the phishing email is sent, the victim receives it and is tempted to click the link, believing it is legitimate.  



After clicking the link, the victim is redirected to the fake login page. Here, they are asked to enter their Gmail credentials, thinking it will grant them access to the promised reward.  
![Victim Email Received](https://github.com/ChitrakshGupta/EmailPhishing/blob/master/images/Picture8.png)  

---

### 8. **Harvesting Credentials**  
When the victim submits their login information, the credentials are captured by the attacker. Below is an example of the credentials harvested:  

![Captured Credentials](https://github.com/ChitrakshGupta/EmailPhishing/blob/master/images/Picture9.png)  

---

### **Conclusion**  
We successfully performed a phishing attack and obtained the Gmail ID and password of the target user. This demonstrates how attackers can exploit human behavior to access sensitive information.  

While this example focused on Gmail credentials, phishing attacks can also target internet banking details, social media accounts, and other platforms.  

SET (Social-Engineer Toolkit) is a powerful tool widely used by red teams for penetration testing and vulnerability assessment. However, ethical usage and proper authorization are crucial when performing such tests. Other tools, both open-source and paid, can also be used for phishing and penetration testing.  

---

### **Ethical Reminder**  
This demonstration was conducted in a controlled environment for educational purposes only. Unauthorized phishing is illegal and unethical. Always ensure proper authorization and use these techniques responsibly.  

---

