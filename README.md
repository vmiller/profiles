profiles
========

Here are some profiles that I am using, and perhaps others will find them useful.  

**8021xDisable.mobileconfig** - Unchecks the "Enable automatic connection" checkbox for 802.1X in Network Preferences.  This was built by grabbing the plist and using Tim Sutton's [mcxToProfile](https://github.com/timsutton/mcxToProfile "mcxToProfile") tool

**DisableScreenSaverPassword.mobileconfig** - Disables the "require password" on resume from screensaver.

**Office2011Prefs.mobileconfig** - Disables first run splash screens for Offce 2011 apps.  Based on plists from [William Smith](http://talkingmoose.net/2014/07/12/posting-my-psu-macadmins-conference-presentation/ "talkingmoose") and converted with Tim Sutton's [mcxToProfile](https://github.com/timsutton/mcxToProfile "mcxToProfile") tool.  You will probably want to change the User and Company information on lines 198 and 200.

**MouseRightClick.mobileconfig** - sets the mouse right click to "Secondary Button" for a mighty mouse.  Thanks to Patrick Fergus for this one.