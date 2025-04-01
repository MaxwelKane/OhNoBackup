# OhNoBackup
# Table of Contents
1. [Emergency](#emergency)
    1. [Phone Gone](#phone-stolenbroke)
    2. [Computer Gone](#computer-stolenbroke)
        1. [Computer Setup](#computer-setup)
    3. [All Gone](#all-gone)
2. [YubiKey](#yubikey)
3. [Backup Codes]()
4. [Data Backup](#data-backup)
5. [Services Down]()
6. [Monthly Check](#monthly-check)

Rules: 
There must be backup codes. 
Yubikey if and only if there is a backup code. 


# Emergency:
## Phone Stolen/Broke:
App store is under one email 
and apple is under main email
For apple photos, we should have it backed up to google. Give me a minute on that. 

## Computer Stolen/Broke:
The thing is, I have 3 computers.
Desktop: There is litterally nothing on here. Probably good if it dies because of the fucked config I have on it.

Primary Laptop: Everything should be backed up to the cloud in a Folder for primary laptop.

Secondary Laptop:
Everything should've been ported a while ago. There should be a folder for this as well under old laptop.

### Computer Setup
vs code, github, google shit, proton vpn, xournal, latex, prog languages. 

## All Gone
Don't Jump!!
Everything should be in amazon, google, idrive, you have the extra bitwarden account with all of the backup codes.
There should also be a large physical backup drive somewhere safe.


Okay, all of my files are on my laptop, google drive, laptop, desktop computer. 

My backup stack: 
IDrive,
AWS s3 glacier,
Google Drive,
Physical hard drive
(Hopefully a nas one day)

My Password Stack:
Bitwarden
[Backup Codes](#backup-codes)
YubiKeys

Things That are worth securing:
Google Drive,
Cloudflare,
AWS,
GCP,
Robinhood,
All other brokers,
discord,
other emails,
vercel,
youtube channels, 
github,
digital ocean,
bank account,
idrive,
godaddy,
fly.io, 
idrive, 
icloud, 
insta, 
x, 
twitch?, 



flash drives scattered
random ssd's around

# YubiKey 
I have 2 Yubikey Keys. 
## YubiKey Pins 

5C Pin Phone pass the one that’s like about working on urself. I don't know if it's standard, but 2 is ABC, 9 is WXYZ.

My other pin should be 123456, but idk. 

# Backup Codes
Backup codes are kept in a seperate bitwarden account. 
Without getting specific, this account is the one you use for financial stuff. The password is also pretty hard. 


### Backup codes stored in second bitwarden account:
Github
Google
Bitwarden


# Data Backup
**3-2-1 Backups**

Rclone is compatible with everything here
If not, there is an automatic sync. 

**See todo we need to take out idrive autobackup**

Phone: On device, iCloud, Google Drive, S3 Glacier, Physical (Different regions of couse)

Laptop: On device, Google Drive, Github, S3 Glacier, physical

Desktop: None needed, no information
Extra laptop: Same as above. 

Bitwarden: on device, bitwarden cloud

# List of all services


## Vulnerabilities
Robinhood only has support for SMS. Obviously, this is cause for concern. 
Google Skip password when possible off/on

# Monthly Check
Make sure you know your yubikey pins. 
Make sure you know your bitwarden passwords.
Make sure you know your s3 shit. 

Backup!!!!!
dsa
df
dsf
ads

check for connected apps and devices 

## todo 
find my other yubikey...
find a way to prevent sim swapping
put yubikey in safety deposit box
robinhood vulnerability
port old laptop.
backup laptop
icloud backup to google drive
all things worth backing up and all things worth securing. 
offline storage protocall
get rid of idrive autobackups
configure other services for thingmibob
backup ur shit!

extra: 
A lot is taken from https://github.com/geerlingguy/my-backup-plan
Ansible playbooks, we use this for 
Veeam is free aparantly. 


