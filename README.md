# shell_scripts

Collection of cool shell scripts, A way for me to learn shell programming. :laughing: :fire:

* **ytb_video**:

This one finds the video playing on chrome (youtube) and downloads it in the directory which fired up the script or you can give path to the directory as command line argument. This is kind of dependent on third part package "youtube-dl" for downloading, If you are using apt as your package manager don't worry this scripts covers you up if you do not have the package, If you are using some other distro, Download the package before running the script.

**PS**: This is kind of noobs task, But it helped be learn something new. :smile:

* **alarm**:

This script lets you set a notification alarm after a certain timeout,

Usage:
alarm <time> <unit> <msg>

<time> = "Any Interger"
<unit> = (sec or min or hr)
<msg>  = "Any string enclosed within quotes" (optional)

Packages needed to run the script:
1) Zenity (For dialog display)
2) wmctrl (Placement of the dialog in foreground)