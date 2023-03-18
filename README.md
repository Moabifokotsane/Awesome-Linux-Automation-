# Awesome-Linux-Automation-
Awesome Linux Automation is a curated list of tools, scripts, and resources for automating Linux system administration tasks. The repository aims to provide a comprehensive collection of open-source automation solutions for developers, system administrators, and DevOps engineers to streamline their workflow and increase productivity
          
> Content

<sub>1. How to Automate Program Installation</sub>

<sub>2. </sub>



## 1. Automate Program Installation

**1. You need latest pip version installed in your machine** 

```linux
sudo apt update -y && sudo apt upgrade -y && sudo apt install pip -y
```

**2. Make a requirements.txt file and list down all the programs you need installed in your machine**

```linux
sudo nano requirements.txt
```
- You can Use any editor of choice **(Make sure You know how to close VI editor ✌️😅🤣🥱)** **( :wq + enter)**
- List the programs you need installed in the machine

>Example: 

```linux
nmap

dnsmap

whois
```


**3. After listing down the required programs close the editor and in your absolute working directory type in**

```linux 
sudo pip install -r requirements.txt
```

>YOU ARE DONE AUTOMATING INSTALLATION PROCESS 


