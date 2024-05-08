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
Social Engineering attacks are the various cons used by the hackers to trick people into providing sensitive data to the attackers. The command sudo setoolkit in the prompt gives menu with set prompt:

![image](https://github.com/karthika28112004/creating-a-backdoor-with-SET/assets/128035087/22800e07-f480-45ff-85bf-974bb9e12868)

The command sudo setoolkit in the prompt gives menu with set prompt. Select menu1 for Social Engineering Attacks:
![image](https://github.com/karthika28112004/creating-a-backdoor-with-SET/assets/128035087/960d95da-e9b2-4e97-9aed-d600d859249e)

It displays the following menu and select 2 for Website Attack Vectors:
![image](https://github.com/karthika28112004/creating-a-backdoor-with-SET/assets/128035087/b855ef65-7651-4aa3-a101-a7955982f00d)

The website Attack Vectors displays the following menu. In this menu3 for Credential Harvester Attack Method is selected:
![image](https://github.com/karthika28112004/creating-a-backdoor-with-SET/assets/128035087/eb85507a-c589-4887-9453-b48777f9b386)

The Credential Harvester Attack Method displays the following menu. In this menu1 for Web Templates is selected:
![image](https://github.com/karthika28112004/creating-a-backdoor-with-SET/assets/128035087/53fcad23-88e1-4b4c-bf98-ce732a6c1aa4)

It shows the following screen in which the ip address of the attacker need to be given which is the default value:
![image](https://github.com/karthika28112004/creating-a-backdoor-with-SET/assets/128035087/6b2ba23f-fd80-4ee8-af16-53ea1626be1b)

It shows the following screen in which the option Google can be selected:
![image](https://github.com/karthika28112004/creating-a-backdoor-with-SET/assets/128035087/96f855a5-91dc-4261-ad4c-1158474189e8)

SET starts my Kali Linux Webserver on port 80, with the fake Google account login page. The setup is done:
![image](https://github.com/karthika28112004/creating-a-backdoor-with-SET/assets/128035087/cf05620d-a606-4d95-8106-5391c95e8406)

In windows IE, on giving the url http://192.168.1.2, the fake Google page is displayed. The victim can enter the username and password
![image](https://github.com/karthika28112004/creating-a-backdoor-with-SET/assets/128035087/169ebfa5-18e0-41aa-9269-83b846109d67)

SET logs the information regarding the Google credentials:
![image](https://github.com/karthika28112004/creating-a-backdoor-with-SET/assets/128035087/4e0e0401-9976-4c8a-bfa6-ca884bfec22c)

SET logs the information in the xml file under /root/.set directory:
![image](https://github.com/karthika28112004/creating-a-backdoor-with-SET/assets/128035087/fe8701b7-d45d-4927-b65f-f5a4c9e7fcc4)





## RESULT:
The Social Engineering Toolkit (SET) is used to create backdoor is  examined successfully
