# Stripped-Win10

This is my custom Windows 10 Pro x64 .iso and it is bare metal friendly.
It does NOT include any bloatware, telemetry or data collection (and does not include any browser by default).

# Download

Download the ISO file from Mega:
https://mega.nz/file/fY1STZ7B#NHVV1I2ehVNyyc5VOiIXr6eSc58wlcXgmMuR7b3Phfo

# Installation

(It is recommended to use Rufus Utility to make bootable USB, because it skips data collection and it is able to make local user without hassle with Microsoft account bypass)

1. Install Windows as normal .iso.
2. Pass the OOBE normally.
3. When you are on desktop, install all comulative updates.
4. (Premade local account only) You will problably be prompted after restart to make password, skip this by pressing Enter key.
5. As you can probably see, MS is trying to force some things like Edge in your installation. We are going to get rid that and install some apps by using CTT WinUtil.
   Simply type in PowerShell (as admin) this command:

   			irm christitus.com/win | iex

6. Install apps of your choice by using this utility.
(When you hit the "Start Install" button, another windows will pop up. You have to hit Install or Update (It is installing Winget))
7. I would recommend using some of the tweaks from this utility as long as you know what you are doing. (Only at your own risk!!!)
8. Thats it. Enjoy.

# Credits

All creds to Chris Titus for making this Utility as it is much more simple to operate with stripped down ISOs.
Thanks!
