# Arachni Vulnerablity Scanner Installation on Window
Installation of Arachni Vulnerability Scanner in Window OS

**STEP 1 : Download Arachni Window Package**

[Download Arachni Executable File](http://www.arachni-scanner.com/download/)

**STEP 2 : Run cmd.exe as Administrator**

![alter text](https://github.com/ye-hbone-myat/arachni/blob/f8a46d815e3e8aa81b3713f3a91d88f6ee3eedce/images/image-893-1024x554.png)

**STEP 3 : Navigate to directory where arachni package was downloaded**

```console
cd C:\Users\yourusername\Desktop
```
Note : Change path according to your file.

**STEP 4 : Run downloaded arachni file using command line**

```console
arachni-1.4-0.5.10-windows-x86_64.exe
```
This will extract files to directory **C:\Users\yourusername\Desktop\arachni-1.4-0.5.10-windows-x86_64**

**STEP 5 : Navigate to arachni bin directory**

```console
cd C:\Users\yourusername\Desktop\arachni-1.4-0.5.10-windows-x86_64\bin
```
**STEP 6 : Run Arachni Scanner**

```console
arachni_web.bat
```
This should generate local web access point to arachni web interface.

**STEP 7 : Access Arachni Web UI**

Go to url http://localhost:9292/ and login.

**STEP 8 : Check account credentials and other details**

Check default login details in the following path.
```console
C:\Users\yourusername\Desktop\arachni-1.4-0.5.10-windows-x86_64\README.txt
```
Arachni Scanner Scanning Types
----------
1. New Scan
2. Schedule Scan
