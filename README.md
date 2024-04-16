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

From kali linux issue the command :sudo arpspoof -i eth0 
![322249642-2b189817-c9be-4b2f-a4a8-fc1aa6531e11](https://github.com/pradeepasri26/ARP-Attack-and-Network-Sniffing/assets/131433142/42c57747-0db8-42b2-a44b-6ed1a4e2edff)

From Kali linux issue the command : sudo arpspoof -i etho -t
![322249670-6aac1a9e-b424-4c28-a24e-3810e17eb68c](https://github.com/pradeepasri26/ARP-Attack-and-Network-Sniffing/assets/131433142/1c2ae4f9-8fcf-42b8-8b4e-17b6f0a76167)

dsniff:In Metasploit open the ftp console as below. Also you can try other ftp websites ftp.vim.org
## OUTPUT:

![322249686-f680d9a7-3814-4d78-8bde-cc1afb743cd4](https://github.com/pradeepasri26/ARP-Attack-and-Network-Sniffing/assets/131433142/a45261c6-893d-4f11-9d21-a6d1a8eb343a)

In Kali issue the following commands:sudo dsnifff
## OUTPUT:

![322249698-510f0e9f-01f6-49e9-a133-6a6296139154](https://github.com/pradeepasri26/ARP-Attack-and-Network-Sniffing/assets/131433142/8cae85d3-b265-4d38-b277-4506a10f606c)

Invoke the wireshark and examine the various menus  and controls of the tool:
![322249702-19c33e91-31d9-49f7-b0ba-542c7c26ee70](https://github.com/pradeepasri26/ARP-Attack-and-Network-Sniffing/assets/131433142/2f2c4ace-5809-46b9-98e7-daaf9a4f4bbc)


## RESULT:
The kali linux tools for ARP Attack and Network Sniffing were identified successfully
