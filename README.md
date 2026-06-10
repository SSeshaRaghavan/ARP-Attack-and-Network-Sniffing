# ARP-Attack-and-Network-Sniffing
# Explore Network Sniffing and ARP Attacks

# AIM:

To explore network sniffing and ARP Attacks

## STEPS:

### Step 1:

Install kali linux either in partition or virtual box or in live mode

### Step 2:

Investigate on the various categories of tools as follows:


### Step 3:
Open terminal and try execute some kali linux commands

## ARP Attacks:  
ARP spoofing: A hacker sends fake ARP packets that link an attacker's MAC address with an IP of a computer already on the LAN. 
Boot kali and Windows7 virtual machines.
In windows 7 give the command arp -a
## OUTPUT:


From kali linux issue the command :
sudo arpspoof -i eth0 -t <target system> <gateway>
## OUTPUT:
<img width="832" height="523" alt="image" src="https://github.com/user-attachments/assets/7877f16e-d6be-4763-a0cb-4a6d8d09a747" />
<img width="637" height="435" alt="image" src="https://github.com/user-attachments/assets/365f7244-f063-47bc-b59f-b88b39768901" />

 dsniff:
<img width="532" height="241" alt="image" src="https://github.com/user-attachments/assets/d8f10187-7921-4691-8411-44472ffdbee4" />

In Metasploit open the ftp console as below. Also you can try other ftp websites ftp.vim.org
## OUTPUT:
<img width="766" height="125" alt="image" src="https://github.com/user-attachments/assets/26ad02ce-20e1-420c-8df2-74fd320cb398" />

In Kali issue the following commands:
sudo dsnifff
## OUTPUT:
<img width="1914" height="807" alt="image" src="https://github.com/user-attachments/assets/64dc32a5-428c-43ef-bc74-0fb12a562b3b" />

Invoke the wireshark and examine the various menus  and controls of the tool:

## RESULT:
The kali linux tools for ARP Attack and Network Sniffing were identified successfully
