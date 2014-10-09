# IP Updater

*v0.1.1*

## Features

- Checks for IP changes via [icanhazip](http://icanhazip.com).
- Logs IP changes and actions taken.
- DigitalOcean DNS ready (With APIv2).
- Pushover ready.
- Easy to make it do more.

## Requirements

- Bash
- Curl
- Cron

## Notices

- Currently run this on my Raspberry Pi to keep DigitalOcean's DNS (and myself via Pushover) updated if my IP changes.
- I recommend this to be run by a cronjob every five minutes. Example in the `INSTALLATION.md`.
- I also recommend you set the file permissions to `700` because it contains some API keys that you don't want other things seeing.
