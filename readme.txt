How to run MacOS on Windows using VMware Guide
==============================================

Please follow all the steps:

1: Download VMware for Windows from the following link:
https://www.vmware.com/latam/products/workstation-pro/workstation-pro-evaluation.html

2: Download MacOS Catalina (or any version you want) from the following link:
You can choose between Mediafire or Mega to download from.

Mediafire: https://www.mediafire.com/file/9n6uypybj8cl3k8/macOS+Catalina+ISO+10.15.7+by+techrechard.com.iso/file
Mega: https://mega.nz/file/Lu5WyKCY#NwiMf2xPhYqCKMLpBU6y9Eew-6BaCs0vGHdIEyJ4Vnc

3: Download VMware Unlocked:
https://github.com/paolo-projects/unlocker

4: Download Python for Windows:
https://www.python.org/downloads/release/python-370/

5: After download all files, Install VMware first.

6: Install Python with default settings

7: Unzip VMware Unlocker and open its folder. Goto "win-install.cmd" file and run it as administrator.

8: Wait till it finish processing

9: Follow the processes in the video.


VMX Code for AMD
================

smc.version = "0"
cpuid.0.eax = "0000:0000:0000:0000:0000:0000:0000:1011"
cpuid.0.ebx = "0111:0101:0110:1110:0110:0101:0100:0111"
cpuid.0.ecx = "0110:1100:0110:0101:0111:0100:0110:1110"
cpuid.0.edx = "0100:1001:0110:0101:0110:1110:0110:1001"
cpuid.1.eax = "0000:0000:0000:0001:0000:0110:0111:0001"
cpuid.1.ebx = "0000:0010:0000:0001:0000:1000:0000:0000"
cpuid.1.ecx = "1000:0010:1001:1000:0010:0010:0000:0011"
cpuid.1.edx = "0000:1111:1010:1011:1111:1011:1111:1111"
featureCompat.enable = "FALSE"


VMX Code for Intel
==================

smc.version = "0"
