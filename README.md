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
## OUTPUT

<img width="448" height="247" alt="image" src="https://github.com/user-attachments/assets/6d8b2a70-98d6-4bb4-ba95-5471f35adf16" />


The command sudo setoolkit in the prompt gives menu with set prompt. Select menu1 for Social Engineering Attacks:
## OUTPUT

<img width="460" height="221" alt="image" src="https://github.com/user-attachments/assets/201a96c1-a970-47b3-919a-84669644d997" />


It displays the following menu and select 2 for Website Attack Vectors:
## OUTPUT

<img width="821" height="753" alt="image" src="https://github.com/user-attachments/assets/ff5472c8-090b-4d4a-8228-ea4ed1987076" />


The Credential Harvester Attack Method displays the following menu. In this menu1 for Web Templates is selected:
## OUTPUT

<img width="755" height="473" alt="image" src="https://github.com/user-attachments/assets/b99ddd20-04b9-40af-97ed-5aa3c4b70706" />


It shows the following screen in which the ip address of the attacker need to be given which is the default value:
## OUTPUT


<img width="696" height="325" alt="image" src="https://github.com/user-attachments/assets/54956400-991d-4385-b3ae-58db62eed245" />




It shows the following screen in which the option Google can be selected:
## OUTPUT

<img width="587" height="330" alt="image" src="https://github.com/user-attachments/assets/e0e1bd59-8829-47cb-a69f-54f87502ad76" />




SET starts my Kali Linux Webserver on port 80, with the fake Google account login page. The setup is done:
## OUTPUT


<img width="843" height="137" alt="image" src="https://github.com/user-attachments/assets/72967842-7534-45cd-8dc9-a80115ef4be1" />



In windows IE, on giving the url http://192.168.1.2 (use appropriate IP address), the fake Google page is displayed. The victim can enter the username and password
## OUTPUT
<img width="682" height="650" alt="Screenshot 2026-08-25 140500" src="https://github.com/user-attachments/assets/ba819982-ec87-46fe-83f6-14c9521d9a0b" />


SET logs the information regarding the Google credentials:
## OUTPUT

<img width="1215" height="238" alt="image" src="https://github.com/user-attachments/assets/ac124c92-702f-4dd1-96ec-227dcf0b9e8d" />


SET logs the information in the xml file under /root/.set directory:
## OUTPUT

<img width="771" height="51" alt="image" src="https://github.com/user-attachments/assets/7d512256-0136-4251-bfd1-2d902fd65610" />











## RESULT:
The Social Engineering Toolkit (SET) is used to create backdoor is  examined successfully
