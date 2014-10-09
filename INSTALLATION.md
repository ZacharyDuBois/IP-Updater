# Installation

*v0.1.1*

#### 1)

Download the script and fill out the information in the variables block.

#### 2)

Save the file into `/etc/` (That's where mine is located).

#### 3)

Set the file to permissions of `700`.

    chmod 700 /etc/ip-updater

#### 4)

Add a cronjob in your crontab.

    crontab -e
    0,5,10,15,20,25,30,35,40,45,50,55 * * * * /etc/do-ipupdate

#### 5)

Keep an eye on the log file to make sure it works :)
