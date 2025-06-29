# 📝 Commands

Welcome to the **Commands Module**. It’s your arsenal. Learn them, master them, or stay clueless forever.

---

## ⚡ All commands explained

This section covers **every default command available in /bin** with purpose, usage, syntax, and notes in **one single read**.

---

`ls` lists directory contents. Syntax: `ls <directory>`. Example: `ls /bin` or just `ls`. Use it to see files and folders. If you don’t know what’s in your directories, you’re operating blind.

`cd` changes your current directory. Syntax: `cd <directory>` or `cd ..` to move up. Example: `cd /bin`. Without this command, you’re stuck in one place.

`pwd` prints your current working directory. Syntax: `pwd`. Example: `pwd`. Know where you are, always.

`cat` displays file contents. Syntax: `cat <file>`. Example: `cat notes.txt`. Concatenate (aka read) text files, scripts, credentials, etc.

`cp` copies files or directories. Syntax: `cp <source> <destination>`. Example: `cp notes.txt Desktop/`. It's just making a copy.

`mv` moves or renames files and directories. Syntax: `mv <source> <destination>`. Example: `mv file.cap Downloads/`. It's just moving the file.

`rm` removes files. Syntax: `rm <file>`. Example: `rm temp.txt`. Clean your mess. Remember: one wrong rm command can end your system.

`rmdir` removes empty directories. Syntax: `rmdir <directory>`. Example: `rmdir old_folder/`. Folders full of garbage mean a cluttered mind. Clean them out.

`mkdir` makes directories. Syntax: `mkdir <directory>`. Example: `mkdir loot`. Organise your scripts and stolen data like an organised individual.

`touch` creates an empty file. Syntax: `touch <file>`. Example: `touch notes.txt`. Fast way to create a file.

`ps` lists running processes. Syntax: `ps`. Example: `ps`. Recon your own system. Know what’s running, what you started, and what shouldn’t be there.

`kill` terminates processes by PID. Syntax: `kill <PID>`. Example: `kill 1337`. Useful in many scenarios.

`chmod` changes file permissions. Syntax: `chmod [permissions] <file>`, where `[permissions]` specifies who (u=user, g=group, o=others) and what (+/- r w x) you’re changing. Example: `chmod u-rx document.txt` removes read and execute permissions from the user on document.txt, meaning the owner can no longer read or run it but can still write. Use it to control who can access or modify your files effectively.

`chown` changes the owner of a file or folder. Syntax: `chown <owner> <file>`. Example: `chown bytehandler document.txt` changes the ownership of document.txt to bytehandler. Useful for managing which user controls specific files.

`chgrp` changes group ownership of a file. Syntax: `chgrp <group> <file>`. Example: `chgrp mygroup document.txt` changes the group owner to 'mygroup'. Useful for managing group-based permissions.

`sudo` runs commands as root. Syntax: `sudo <command>`. Example: `sudo apt-get update`. Required for actions needing elevated privileges. Use it when the system denies you permission. You may also elevate your terminal to root by using `sudo -s` and logging in as root.

`reboot` reboots the machine. Syntax: `reboot`. Example: `reboot`. Quick command for if you are tired of Grey Hack.

`ifconfig` shows network interface configurations. Syntax: `ifconfig`. Example: `ifconfig`. Displays connected Wi-Fi ESSID, BSSID, public IP, local IP, and gateway. Basic networking check.

`iwconfig` connects to Wi-Fi interfaces. Syntax: `iwconfig [net device] [bssid] [essid name] [pass key]`. Example: `iwconfig wlan0 00:11:22:33:44 mynetwork mypass` connects wlan0 to the Wi-Fi with BSSID 00:11:22:33:44, ESSID mynetwork, using mypass as password.

`iwlist` scans for available Wi-Fi networks. Syntax: `iwlist <interface>`. Example: `iwlist wlan0`. Displays BSSID, signal strength (PWR), and ESSID for nearby networks.

`ping` tests connectivity to a host. Syntax: `ping <IP>`. Example: `ping 192.168.1.1`. Confirms if a host is online and reachable.

`nslookup` queries DNS information. Syntax: `nslookup <domain>`. Example: `nslookup domain.com`. Resolves domains to IPs.

`ftp` connects to FTP servers. Syntax: `ftp [user@password] [ip address]`. Example: `ftp handler@pass123 127.0.0.1`. Used to connect to FTP servers with credentials.

`aircrack` cracks Wi-Fi passwords from capture files. Syntax: `aircrack <file.cap>`. Example: `aircrack file.cap`. Attempts to crack WPA/WPA2 handshakes without specifying a wordlist.

`aireplay` injects packets into Wi-Fi networks. Syntax: `aireplay [-b bssid] [-e essid]`. Example: `aireplay -b 00:11:22:33:44 -e mynetwork`. Used to deauthenticate clients or interact with wireless networks to capture handshakes.

`airmon` enables monitor mode on wireless interfaces. Syntax: `airmon start <interface>`. Example: `airmon start wlan0`. Required to put wlan0 into monitor mode for scanning and attacks like capturing handshakes or packet injection.

`useradd` adds a new user. Syntax: `useradd <username>`. Example: `useradd admin2`. Creates additional accounts. Will prompt you to create a password.

`userdel` deletes a user. Syntax: `userdel <username>`. Example: `userdel tempuser`. Removes user accounts no longer needed.

`passwd` changes user passwords. Syntax: `passwd <username>`. Example: `passwd bytehandler`. Updates or resets passwords.

`groups` shows group memberships of a user. Syntax: `groups <username>`. Example: `groups bytehandler`. Displays which groups a user belongs to for privilege checks.

`groupadd` creates a new group. Syntax: `groupadd <user> <groupname>`. Example: `groupadd bytehandler testers`. Adds a group for permission management.

`groupdel` deletes a group. Syntax: `groupdel <user> <groupname>`. Example: `groupdel bytehandler testers`. Removes unused groups from the system.

`whoami` prints the current user. Syntax: `whoami`. Example: `whoami`. Useful to verify user context during operations – or if you’re having an identity crisis.

`whois` retrieves domain registration info. Syntax: `whois <IP>`. Example: `whois 20.18.190.24`. Shows registrar data and ownership details.

---

## ⚠️ Final note

Understand these commands fully. Using tools without understanding their purpose is worthless.
If you don’t understand every command here, don’t call yourself a hacker and go learn how to use them already.

---