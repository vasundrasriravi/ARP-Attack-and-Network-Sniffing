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
![Screenshot 2024-04-13 144130](https://github.com/vasundrasriravi/ARP-Attack-and-Network-Sniffing/assets/119393983/f78277bc-1cab-4afe-83bc-41a7497e785a)


From kali linux issue the command :
sudo arpspoof -i eth0 -t <target system> <gateway>
## OUTPUT:
![Screenshot 2024-04-15 091515](https://github.com/vasundrasriravi/ARP-Attack-and-Network-Sniffing/assets/119393983/2011aaf4-730d-4930-8bec-e4bb8bbca9e6)

## dsniff:

In Metasploit open the ftp console as below. Also you can try other ftp websites ftp.vim.org
## OUTPUT:
![Screenshot 2024-04-15 091551](https://github.com/vasundrasriravi/ARP-Attack-and-Network-Sniffing/assets/119393983/eb94bf86-ee4a-45a3-b15e-f0b2eab8194d)
In Kali issue the following commands:
sudo dsnifff
## OUTPUT:

![Screenshot 2024-04-15 091902](https://github.com/vasundrasriravi/ARP-Attack-and-Network-Sniffing/assets/119393983/24bb8bf3-b5d7-414b-84bb-957b19a8abcf)
Invoke the wireshark and examine the various menus  and controls of the tool:
## RESULT:
The kali linux tools for ARP Attack and Network Sniffing were identified successfully
