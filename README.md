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
![272768305-c01350a2-280f-4a20-acc4-99b251cf2555](https://github.com/Sudharsanram/ARP-Attack-and-Network-Sniffing/assets/119393980/447e8cdc-07cc-42b1-811c-f9c62ab29a47)

From kali linux issue the command :
sudo arpspoof -i eth0 -t <target system> <gateway>

## OUTPUT:
![272768730-15ff73f4-6d47-4c0c-bb7e-3698e758424e](https://github.com/Sudharsanram/ARP-Attack-and-Network-Sniffing/assets/119393980/f6ef1da3-71e4-4749-bb8b-ce495b5c4caf)
 dsniff:
In Metasploit open the ftp console as below. Also you can try other ftp websites ftp.vim.org

## OUTPUT:
![272768804-8b02d9cb-ef7b-4a34-a450-6ff6734ee104](https://github.com/Sudharsanram/ARP-Attack-and-Network-Sniffing/assets/119393980/7b4b96e6-04ae-4601-8ee4-cd2a662850e9)
In Kali issue the following commands:
sudo dsnifff

## OUTPUT:
![272769125-70b4832c-d296-4e02-a0ad-f707395640c2](https://github.com/Sudharsanram/ARP-Attack-and-Network-Sniffing/assets/119393980/7159dd79-0dc5-4311-841a-b9c7f32c3620)
Invoke the wireshark and examine the various menus  and controls of the tool:
![272769225-c928c0d4-6c71-4aae-b32a-1ca6d105cb36](https://github.com/Sudharsanram/ARP-Attack-and-Network-Sniffing/assets/119393980/30ca7aaf-90c2-47c8-bac1-01ef2f635907)

## RESULT:
The kali linux tools for ARP Attack and Network Sniffing were identified successfully
