![image](https://user-images.githubusercontent.com/90950629/148694600-f55984d8-3bfa-4b37-96b4-4df6904db3b5.png)





# About

A MITM framework script based on python which arp poisons the victims machine on execution which can be used as in for man in the middle attacks  and later resets the mac address of the gateway and the victim to avoid suspicion . 


# Download

1. Clone the repo --- > git clone https://github.com/Purbayan2014/MITM.git
2. Cd into the repository ------- > cd MITM/

# Features
 1. Lightweight as compared to other mitm implementation . 
 2. Can be easily obfuscutable . 
 3. Displays the amount sent to the victim.
 4. Resets the Hardware address on quiting of both the victim and the gateway device.
 
 
# Instructions

Upon starting the script you have to provide the gateway-ip and the target-ip 

spoof_injection.py -t (target-ip) -g (gateway-ip)

![partial_blur](https://user-images.githubusercontent.com/90950629/148695120-fbdaa7bc-4693-4947-853b-00c0fa87e78d.jpg)
 
 
 Upon succesfull 
 
 Initially 
 
![initia](https://user-images.githubusercontent.com/90950629/148695464-82b45b5b-e99e-4daa-b32e-dfdee9ee34c4.jpg)
 
 and then upon completion we can see that the hardware address of the attacker and the gateway is the same
 
 
![final](https://user-images.githubusercontent.com/90950629/148695703-7f569d34-42a6-4bb8-a51b-d85205c97c90.jpg)
 
 And,thus we are the man in the middle and we can analyse each and every packets between the user and the gateway !!! 
 
 
 # Error 
 
 If you get the error that the list is empty then that means the answered list entered by arp poisioning is empty.It doesnt means that the script is broken
 You can try it on another network range with different IP address .
 
 
![partial_blur(1)](https://user-images.githubusercontent.com/90950629/148696029-2b0e7268-c1f3-4401-ad84-da6c372a5c0a.jpg)

 
# Note 
 
MITM is only to be used for legal applications when the explicit permission of the targeted organization has been obtained.
 
