# jnc-downloader
A bash script to download ebooks from your j-novel.club library.

## Dependencies
The script requires `jq` and `curl` > 7.22

## Limitations
This script was written and tested on a Linux distribution. It may or may not work on MacOS or the Windows Subsystem for Linux, feel free to try!

It will also only work if you have an account directly with J-Novel.club. If you log in using Google/Facebook, this script will not work.

## How to use
Just adjust the values in the config area denoted at the top of the jnc.sh file and execute the script.

## Security considerations
Since you need to put your E-Mail and Password into the script file, you are essentially storing your JNC credentials in plain text on disk.
This means any program running as root or with your user will be, in principle, able to access those credentials. Whether or not you are comfortable with this is up to you.
