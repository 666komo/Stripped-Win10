# Stripped-Win10

This is my custom Windows 10 Pro x64 .iso and it is bare metal friendly.
It does NOT include any bloatware, telemetry or data collection (and does not include any browser by default).

![image](https://user-images.githubusercontent.com/118112129/221356135-68002990-0832-47f1-813d-8555c58e2800.png)

# Download

Download the ISO file from Mega:
https://mega.nz/file/fY1STZ7B#NHVV1I2ehVNyyc5VOiIXr6eSc58wlcXgmMuR7b3Phfo

# Installation

(It is recommended to use Rufus Utility to make bootable USB, because it skips data collection and it is able to make local user without hassle with Microsoft account bypass)

1. Install Windows as normal.
2. Pass the OOBE normally.
3. When you are on desktop, install all comulative updates.
4. (Premade local account only) You will problably be prompted after restart to make password, skip this by pressing Enter key.
5. As you can probably see, MS is trying to force some things like Edge in your installation. We are going to get rid of that and install some apps by using CTT WinUtil.
   Simply type in PowerShell (as admin) this command:

   			irm christitus.com/win | iex

6. Install apps of your choice by using this utility.
(When you hit the "Start Install" button, another window will pop up. You have to hit "Install" or "Update". (It is installing Winget))
7. (Recommended!) Go to Updates tab and hit the middle option. (This will make feature updates delay for 2 years, so only updates you will recieve are security updates)
8. I would recommend using some of the tweaks from this utility as long as you know what you are doing. (Only at your own risk!!!)
9. Thats it. Enjoy.

# Credits

All creds to Chris Titus for making this Utility because it is much more simple to operate with stripped down ISOs.
Thanks!

# There is still room for improvement!

There are still some things I want to change or delete. Make sure to watch this repo for updates!

# Disclaimer

Windows (OS) is product made by Microsoft Corporation. This ISO is customized by ME and for MY needs and requirements. I'm NOT responsible for any damages and mistakes made while in installation.
