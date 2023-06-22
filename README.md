# Patch-Recovery
This CI service patches recovery images of Samsung to enable Fastbootd. Based on Phh's [script](https://github.com/phhusson/samsung-galaxy-a51-gsi-boot)

# How to use:
- Fork this repo
- Upload recovery.img/recovery.img.lz4 to any host who provide direct download access (Like Github Releases)
- Once uploaded copy the URL.
- Head over to Actions tab. Click on RECOVERY -> Run workflow. Insert the copied URL in the RECOVERY URL field and Start the workflow
- Github Releases URL Example: https://github.com/ChonDoit/Patch-Recovery/releases/download/A33-5G_A13-BIN5/recovery.img.lz4

- The Patching process will start
- A Patched-Recovery.zip will be uploaded at the end of the process.

Download it and extract your patched recovery image. The Image will already also be repacked to .tar for flashing directly through Odin
![](https://s3.bmp.ovh/imgs/2022/04/19/91ef3a3ee9255e9c.png)

# Credits
- [Phhusson](https://github.com/phhusson) Without his script nothing would be possible at the first place
- [James Nguyen](https://github.com/thongass000) Helping me in simplifying the scripts and tweaking it
