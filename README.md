Forked From ChrisTitusTech (Thank You Chris!) 
Link : https://github.com/ChrisTitusTech/win10script

# Custom win10script
This is the Ultimate Windows 10 Script from a creation from multiple debloat scripts and gists from github. I also added Chocolatey and other tools to the script that I install on every machine.

## My Additions (Remains Original)

- Dark Mode
- One Command to launch and run
- Chocolatey Install
- O&O Shutup10 CFG and Run
- Added Install Programs
- Added Debloat Microsoft Store Apps

## Modifications (Some Changes)
Some Few Changes

- Uninstalling OneDrive (This is on in my script)
- Installing Adobe, Chocolatey, Notepad++, VLC, and 7-Zip
- Enable Defender (for some reason)

Comment any thing you don't want out... Example:

```
########## NOTE THE # SIGNS! These disable lines This example shows UACLow being set and Disabling SMB1
### Security Tweaks ###
	"SetUACLow",                  # "SetUACHigh",
	"DisableSMB1",                # "EnableSMB1",

########## NOW LETS SWAP THESE VALUES AND ENABLE SMB1 and Set UAC to HIGH
### Security Tweaks ###
	"SetUACHigh",
	"EnableSMB1",
```
