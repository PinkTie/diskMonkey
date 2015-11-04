# diskMonkey
Linux shell script to monitor disk space and notify you upon reaching a defined threshold

## Usage
Set as a cronjob for as often as you would like disk space to be checked

## Settings
At the top of the script you will find 3 options to change:  
ADMIN – where notifications are sent either a local account (root) or remote email address (you@yourdomain.tld)  
ALERT – the level at which you want to be alerted   
EXCLUDE_LIST – defines partitions to ignore  


## Requirements
This script makes use of the mail command, which is found in mailutils (Ubuntu/Debian) or mailx (Redhat/CentOS)


## Compatibility
This script has been tested on Ubuntu and LinuxMint
