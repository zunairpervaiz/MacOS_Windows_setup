How to run MacOS on Windows using VMware Guide
==============================================

Please follow all the steps:

1: Download MacOS Catalina from the following link:

Single Link Download:
-----------------------------------------------------------------------
https://www.mediafire.com/file/cgvvab76xbbdroi/macOS+Catalina+10.15.6+Package.rar/file
-----------------------------------------------------------------------
1GB Parts : 
-----------------------------------------------------------------------
Part 1 : https://mega.nz/file/ragRyBqb#sUpacIuH6zhTDRvtg3Jma57k7cHVKVqzRTKbGVC87TA
Part 2 : https://mega.nz/file/LXwjCDCK#x-APIyYUUGwDmyjB3iaNKqD3c-CZAFeZh_WixrAtDdc
Part 3 : https://mega.nz/file/PCg3SDBY#42ZkKUeMVl6sKFlzfDa1JbygAWUBJOiiQOOGdFjrhRA
Part 4 : https://mega.nz/file/3GgXxJJQ#YnEDPyIsC61TfANNZLX0d-tAh7muI2DeMEQNKYKxzqY
Part 5 : https://mega.nz/file/XaxBnJjC#gT1DeJhdF5RlVDz5xUPR3hh0AayDmxlg82Ffvsl5Qro
Part 6 : https://mega.nz/file/jeoBiThQ#WuF1BSBJlwncsYIi86qEL_LHgSNEgEHEcCpFTNGVnvk
Part 7 : https://mega.nz/file/LS5xUTQT#JpRIDqUG0N0uicB5AG91FesPLf7Tv2iDQ3ChwnII2P4
Part 8 : https://mega.nz/file/2D5VGRLA#SM8suI-58n6txA4GjQDpX8R_T_dZtxvUHTwqHs31_fs

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
