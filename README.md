# Intrusion-detection-using-honeypot

Honeypots are used to capture information from unauthorized intruders that are tricked into accessing them because they appear to be a legitimate part of the network. In this project Kali linux is used. For demonstrating implementation of honeypot 'Pentbox' has to be installed in Kali linux. Pentbox is a tool that allows us to create honeypot in our system. Pentbox comes in low interaction type of honeypot. We can only get to know that someone is trying to attack and their ip address can be found. 
We will open a fake port according to your preference and insert a fake message. You can also provide the option to save the log and save the name of the log. You can see that the honeypot is activated on the required port and similarly you can manually activate honeypots for other ports.
For every attempt of intrusion that was made, it gets alerted and a log is created where the attacker IP and port is recorded.


git clone https://github.com/technicaldada/pentbox

![cis_1](https://github.com/Shreya-Chinchane/Intrusion-detection-using-honeypot/assets/53463113/a0e6c3e1-838b-4c60-892d-5c58ed395218)


cd pentbox

![cis_2](https://github.com/Shreya-Chinchane/Intrusion-detection-using-honeypot/assets/53463113/d126def0-df07-4957-8863-63c94bbc3fb3)


Extract all file from zip file pentbox.tar.gz

![cis_3](https://github.com/Shreya-Chinchane/Intrusion-detection-using-honeypot/assets/53463113/eb96f9a3-0ae8-450d-8687-a68267c274e3)


ls to view files.

![cis_4](https://github.com/Shreya-Chinchane/Intrusion-detection-using-honeypot/assets/53463113/f7543d70-77e9-41fa-9f97-c1905275516e)


To use pentbox type ./pentbox.rb

![cis_5](https://github.com/Shreya-Chinchane/Intrusion-detection-using-honeypot/assets/53463113/6e848140-6985-436c-b84e-f3d95f5b8d40)


Select
1.	FAST CONFIGURATION (AUTO)

![cis_6](https://github.com/Shreya-Chinchane/Intrusion-detection-using-honeypot/assets/53463113/326d5003-3e21-4f8a-ba38-d517c1e866a5)


![cis_7](https://github.com/Shreya-Chinchane/Intrusion-detection-using-honeypot/assets/53463113/ec8a7dbd-4c40-4075-9e5f-31c2d0c5e9f0)


Honeypot is activated on port 80.

Now go to browser from kali linux machine itself and type the ip address http://localhost/192.168.2.211

![cis_8](https://github.com/Shreya-Chinchane/Intrusion-detection-using-honeypot/assets/53463113/b25f2e9a-b7b9-4789-8210-874972d69414)


Select
2.	MANUAL CONFIGURATION

![cis_9](https://github.com/Shreya-Chinchane/Intrusion-detection-using-honeypot/assets/53463113/4c551e57-99ad-4e5f-853f-a86031ebc450)


![cis_10](https://github.com/Shreya-Chinchane/Intrusion-detection-using-honeypot/assets/53463113/103ef95f-164e-42c1-bc62-8fc92976d714)


Create a log file log.txt 

![cis_11](https://github.com/Shreya-Chinchane/Intrusion-detection-using-honeypot/assets/53463113/eb6d752e-65d1-4c48-a174-32b3f3f3718e)


![cis_12](https://github.com/Shreya-Chinchane/Intrusion-detection-using-honeypot/assets/53463113/e06e3ab5-ae35-4bcb-a997-a85d4975b0f0)


Logs stored in log.txt

![cis_13](https://github.com/Shreya-Chinchane/Intrusion-detection-using-honeypot/assets/53463113/da99b6d8-fb15-4c70-9a54-fb26ccbc6afc)


