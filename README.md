# macOS Screenshot Spammer | Flipper Zero BadUSB

Screenshot spammer is a script designed for the bad USB functionality of the [Flipper Zero](https://flipperzero.one/). 

The idea originates from the following observations about current versions of macOS:

- By default, every Mac allows taking screenshots using the Shift + Command + 3 shortcut.
- It is possible to take a screenshot in this way even when the Mac is locked.
- The size of such a screenshot is several MB (varies depending on the macOS version).

Screenshot spammer, therefore, is a very simple script that continuously triggers the above-mentioned shortcut potentially until it fills up the device's memory completely. A maximum limit of 60 screenshots to capture has been set, but this value can be easily adjusted directly in the code to suit specific needs.

Unlike other scripts that require using the terminal or opening applications to attack the device, Screenshot spammer does not need the victim Mac to be unlocked. Hence, to execute the attack, there is no need to know the unlock password. 

It is noted that from macOS Ventura onwards, MacBooks with Apple silicon require user authorization before a new USB accessory can be used. Regarding previous versions of macOS, no authorization is required for the Flipper to inject commands.

## Steps to use it:
- Download file Screenshot_spammer.txt from this repository.
- Connect the Flipper to your computer, open [qFlipper](https://docs.flipper.net/qflipper), and navigate to the 'badusb' folder on your SD card.
- Drag the recently downloaded file into this folder.
- Close the application and disconnect the Flipper.
Now you're ready to use the script!

## Important Notice

This script has been created exclusively for educational purposes. The author assumes no responsibility for any malicious use of the software or any damage caused to devices. It is strongly advised against using this script on unauthorized devices. Please use this script responsibly and legally.
