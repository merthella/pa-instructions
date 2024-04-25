# pa-instructions
Hai mate!
I will teach you how to install pa on your OnePlus 9 & 9Pro
The main requirements are a personal computer, little patience and a cup of coffee.
Note: please feel free to ask for help in the telegram group we wont blame we are family <3


-How to unlock locked bootloader (you can skip this if you have an unlocked bootloader)

-[Already unlocked bootloader can follow directly step 2]

Step 1; 
Identify which region your device is from via going to device info

LE2XX0 = China

LE2XX1 = India

LE2XX3 = Europe

LE2XX5 = North America

LE2XX7 = T-mobile

Except for t-mobile, you need to open the developer settings 
Settings > Device info > Version > Tap 3 times build number and voila the developer settings are open congratulations! 
Now go to additional settings > developer settings, turn on the oem unlock option and confirm (if your device is grayed out, it's probably either a t-mobile device or you never connected it to the internet)

[Chapter 1.2]
-> Download and extract platform-tools: https://developer.android.com/tools/releases/platform-tools
-> Install Google Bootloader Interface driver via this link: https://developer.android.com/studio/run/win-usb (right click inf and press install.)
-> Reboot to bootloader a.k.a fastboot via pressing all buttons when device is turned off. 
-> Checkout device manager and if needed manually select driver to unknown device > Android > Android Bootloader Interface.
-> Open command prompt in platform-tools folder and type: fastboot oem unlock [ this sould showing up screen on your device press yes. WARNING! THIS WILL EREASE YOUR DATA AND THERE IS NO COMING BACK!]

#T-Mobile (this damm thing is little bit complicated feel free to ask help on group chat)
Without risk + unlocked sim [waiting 40 days blah blah.] maybe they dont unlock idk, you can follow this guide: https://xdaforums.com/t/how-to-unlock-the-t-mobile-bootloader.4256319/ <3

With risk [changing region via modded msm tool]: 9 - https://xdaforums.com/t/convert-t-mobile-oneplus-9-to-global-or-other-firmware.4277169/page-3#post-85143501 
9Pro - https://xdaforums.com/t/convert-your-t-mobile-le2127-to-eu-via-msm-no-unlock-bin-needed.4272837/
And follow the same thing as [Chapter 1.2]  <3



Step 2;
[I assume you have already downloaded the pa image it self the .zip one] 
Now I will ask you to update to oxygenos 13 via ota or 14 would be healthier :) regardless of the intermediate version.
Then download the firmware suitable for your device in the #firmware-flasher note in the group. and reboot to bootloader, ie fastboot again.
Extract the downloaded firmware to the desktop, open it as a folder, you will find many files, find and run the Update-firmware.bat file and update your modem via typing yes, unless necessary (t-mobile & china) it will do some magic and automaticly reboots bootloader.
Then open command prompt in platform-tools folder, type fastboot update [drag and drop pa image] and press enter.

-> While pa installing on your device you can take a sip from your coffe <3
And when done, the phone will reboot a few times and ask you to format data, and press confirm

Voila you should have pa logo in your phone <3

Mert <3 Made with love.
