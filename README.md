# creating-a-backdoor-with-SET
creating a backdoor with SET - Ethical Hacking Techniques course

# AIM:
To Create a backdoor with Social Engineering Toolkit (SET)

## DESIGN STEPS:

### Step 1:

Install kali linux either in partition or virtual box or in live mode


### Step 2:

Investigate on the various categories of tools as follows:

### Step 3:

Open terminal and try execute some kali linux commands

## EXECUTION STEPS AND ITS OUTPUT:
Social Engineering attacks are the various cons used by the hackers to trick people into providing sensitive data to the attackers. 
The command sudo setoolkit in the prompt gives menu with set prompt:


![Screenshot 2025-05-12 044547](https://github.com/user-attachments/assets/272e4f1a-7360-4c16-95a2-cb065f51f877)

It displays the following menu and select 2 for Website Attack Vectors:
![Screenshot 2025-05-12 044605](https://github.com/user-attachments/assets/e852d988-b474-439d-b2a4-0020d4968029)

The website Attack Vectors displays the following menu. In this menu3 for Credential Harvester Attack Method is selected:
![Screenshot 2025-05-12 044615](https://github.com/user-attachments/assets/a03b8755-195c-4c05-825b-f66cc3f74643)
![Screenshot 2025-05-12 044625](https://github.com/user-attachments/assets/7cc3fc8b-24f1-4d17-a56f-7e9d10e759ad)

![Screenshot 2025-05-12 044634](https://github.com/user-attachments/assets/a0ad903e-a7fd-4413-abcf-13df127674d3)
SET starts my Kali Linux Webserver on port 80, with the fake Google account login page. The setup is done:

![Screenshot 2025-05-12 044643](https://github.com/user-attachments/assets/17144fd8-8b29-4347-ac93-30b726c2bfcf)
In windows IE, on giving the url http://192.168.1.2, the fake Google page is displayed. The victim can enter the username and password
![Screenshot 2025-05-12 044653](https://github.com/user-attachments/assets/2b214374-c6ea-4a22-8ea9-53f4a82a1b63)

SET logs the information regarding the Google credentials:
![Screenshot 2025-05-12 044707](https://github.com/user-attachments/assets/fe7a2f57-8ceb-4aca-b85e-f21bde8b29ac)



SET logs the information in the xml file under /root/.set directory:

![Screenshot 2025-05-12 044715](https://github.com/user-attachments/assets/6f7cd37d-4dc8-422f-8709-5faf4c65ecbc)

RESULT:
The Social Engineering Toolkit (SET) is used to create backdoor is examined successfully

## RESULT:
The Social Engineering Toolkit (SET) is used to create backdoor is  examined successfully
