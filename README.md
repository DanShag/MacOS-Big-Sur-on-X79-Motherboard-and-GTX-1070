# MacOS-Big-Sur-on-X79-Motherboard-and-GTX-1070

Hello everyone, I think everyone knows that on the GTX 1070 you can install a maximum of Mac OS Sierra or High Sierra, especially on the old X79. However, with this EFI you can now run Big Sur, up to the latest version.

![MacOS Big Sur](https://github.com/DanShag/tdworld.github.io/blob/main/images/20241103_180846.jpg)

> _WARNING: SO FAR I CANNOT RUN ANYTHING HIGHER THAN MAC OS BIG SUR, FOR EXAMPLE MAC OS MONTEREY, I HAVE NOT YET FOUND A SOLUTION FOR THIS CONFIGURATION, BECAUSE EVERYTHING FALLS INTO KERNEL PANIC. I WILL POST A NEW REPOSITORY IF SOMETHING IS UPDATED_

Tested on hardware:
Machinist X79 (2.82H, C602 chipset, for someone this may be important)
Xeon E5-2650V2
GTX 1070 (Pascal, may also run on lower video cards, for example Maxwell)

## Installation instructions that I used for this EFI:
1. Run BDUTillity.exe, which is in the archive
2. Insert a flash drive, I recommend at least 16 or 32 gigabytes
3. Format your flash drive through the program
4. Go to the newly created "BDU" partition, delete everything that is there (this is not useful)
5. Move my EFI to the BDU partition, move back to the program and select PART2, click the Restore button and select your MacOS (HFS is needed file)
6. Wait for the operation to complete and boot from your flash drive.
7. Select the MacOS installer and install the system.

At this point, you should have successfully installed MacOS Big Sur.
If something went wrong, the installer freezes, or Kernel Panic occurs, you can contact me on Telegram: https://t.me/danyashag

Help in cleaning EFI from garbage, help in rebuilding EFI: https://github.com/dima-lq
