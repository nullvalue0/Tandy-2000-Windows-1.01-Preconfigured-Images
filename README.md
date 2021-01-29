# Tandy-2000-Windows-1.01-Preconfigured-Images
Pre-configured Tandy 2000 Startup &amp; System disks for Microsoft Windows 1.01. Set for color display and Digi-Mouse support enabled.  

These disks were built using the images found here: https://github.com/Tandy2K/Tandy2000/tree/master/Software/Windows%201.01. The process is convoluted and error-prone. This is the result of multiple days attempting to build a good disk set.

It consists of a "Startup Disk" which goes is your A: (bottom bay), and a "System Disk" which goes in B: (top bay). The Startup disk is bootable. At the DOS prompt, just type "win" and Windows will load.  

These disks have been set up to take advantage of the 720k format supported on the Tandy 2000. This means all of the distributed applications, fonts and printer drivers are are on just these 2 disks.  

I recommend using ImageDisk 1.18 to write these disks. If you use a 1.2MB 5.25" floppy disk drive, make sure that you use DD (not HD) disks. In the Settings, turn Double Step Off, and change 250 kbps -> 300 kbps.
