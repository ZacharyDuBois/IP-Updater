# IP Updater

*v0.1*

## Features

- Checks for IP changes via [icanhazip](http://icanhazip.com)
- Logs IP changes and actions taken.
- DigitalOcean DNS ready (With APIv2).
- Pushover ready.
- Easy to make it do more.

## Requirements

- Bash
- Curl
- Cron

## Notices

- I currently run this on my Raspberry Pi to keep DigitalOcean's DNS (and myself via Pushover) updated if my IP changes.
- I recommend this to be run by a cronjob every five minutes. Example below:

    0,5,10,15,20,25,30,35,40,45,50,55 * * * * /etc/do-ipupdate.bash

- I also recommend you set the file permissions to 700 because it contains many API keys that you don't want watching eyes to see.

    chmod 700 /path/to/script

Copyright (c) Zachary DuBois, 2014. All Rights Reserved.
