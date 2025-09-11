This is a repository about the RMA Shim exploit called SH1mmer






What is SH1mmer: SH1mmer (Shady Hacking 1nstrument Makes Machine Enrollment Retreat) is an RMA Shim exploit used to un-enroll school chromebooks.




Sh1mmer is a exploit to bybass google's verified boot to make payloads to the device, like removing chrome extensions, and de-enrolling the computer. It is primarly used with students to unblock websites and gain admin access.



Materials: A managed chromebook, A computer with admin access (Like Windows or mac), and a 6 GB USB.



How do I use SH1mmer? : 






First, you need to download the raw RMA shims.





On your chromebook look up chrome://version. Next to "stable-channel" it shows your version. 








Now on your PC (Personal Computer) go to https://sh1mmer.neocities.org//. Find your RMA shim in the list and download it.






If your version isn't on the list, you will have to source them yourself somehow (I.E demand them from your admins, though unlikely that they will give them to you)








Now look up Sh1mmer raw file builder and find one, paste your RMA shim, download the injected file from it.








Download the chrome extensions chrome recovery utility then open it and use local image. Download the new file you get from it and insert it into your 6 GB or higher usb.






Now, back on your school chromebook click ESC-refresh-power (or the side button for newer chromebooks).





This will open a chrome recovery utilty (used for rebooting computer after a brick from something like a virus), press CTRL-D (which is the keyboard shortcut for developer mode).






It will have two screens (screenshots in the image/help folder), click enter to enter developer mode (which is most definitly blocked, if it isnt then dont even bother doing this process)






It will probaly say "Developer mode is blocked" or "Returning to safe mode", for most versions you will want to click the same buttons to enter recovery mode and stick your usb in while the screen is black. 





This should bypass google's verified boot and open the beautiful world shim.



There are many payloads including remove chrome extensions, de-enroll computer, etc. Mess around with the payloads and pick one.




The one that this repo is based on is de-enroll computer, after clicking de-enroll you are going to want to set up a new account with a home or personal email.





Any questions or problems please contact me at drexelking@icloud.com, Thank you




Credits:
MercuryWorkshop: for making this wonderful exploit
Github: For making this amazing sharing sharing platform
Programiz: For helping me learn to code (Not adverstising)
Many github repos: For helping me and contributing along the way
