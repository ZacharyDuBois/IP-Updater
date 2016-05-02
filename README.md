# IP Updater

*v0.1.1*

## Deprecated as of 2015-11-22

I am deprecating this project because I was using this on my Raspberry Pi to keep my home IP updated in DNS. However, I am working on a new thing that can do this called [PI Control](https://github.com/ZacharyDuBois/PI-Control). This will let you automatically update your DNS and even let you control a lot more on your Raspberry Pi. Stay tuned!

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

## Mailing List

To receive updates and information about this project, please subscribe to my
[mailing list](https://we.destroy.tokyo/Projects-Email-List) and select the
projects you would like to be notified about.

## Notices

- Currently run this on my Raspberry Pi to keep DigitalOcean's DNS (and myself via Pushover) updated if my IP changes.
- I recommend this to be run by a cronjob every five minutes. Example in the `INSTALLATION.md`.
- I also recommend you set the file permissions to `700` because it contains some API keys that you don't want other things seeing.
