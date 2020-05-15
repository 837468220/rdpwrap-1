# Additional offstes for the RDP Wrapper Library by Stas'M


## Information:
This repository contains more offsets for the RDP Wrapper Library, which aren't supported natively.
As soon as a build has been added to the official repo, it will be removed here.

Just add support by adding the offsets from the text file (in this repo) corresponding to the file version "RDPConf" shows at the end of your rdpwrap.ini.
Do NOT forget to add a blank line (aka "CR LF") to the end of the ini to prevent RDPWrap from malfunctioning.

It will only contain non-Insider versions I'm able to get from the Microsoft Update Catalog or Microsoft Download Center.


## Screenshot (Windows 8.1 x64 2018-09):
![Screenshot](/RDPWrapper_Demo_w63_19093.png "Screenshot of Windows 8.1 with all updates up to 2018-09")


## Version info:
Currently this repo contains additional offsets (up to Windows 10 1803) for rdpwrap.ini with last change from 2018-10-10.

Last update: 2020-04-24

Includes versions up to 2020-02-xx

If you've got a version not supported by RDP Wrapper and not posted here, feel free to open an issue with file version and download link to the msu/cab-file containing the version.
Issues containing a termsrv.dll file will be deleted.

Remember, that I won't determine offsets for Insider builds or preview updates. (Builds I know, which are missing are listed in the following section)

Also remember, that I won't have enough free time to immediately determine offsets. Please be patient.

## Responsibility:
I don't take any responsibility for correctness of the offsets or potential damage caused by RDP Wrapper itself or the offsets published here.

## Missing offsets:

### Windows Vista
- 6.0.6000.20723
- 6.0.6001.22392
- 6.0.6001.22565
- 6.0.6001.22635
- 6.0.6002.22269
- 6.0.6002.22340

### Windows 7
- 6.1.7600.20661
- 6.1.7600.21085
- 6.1.7601.21855
- 6.1.7601.22477

### Windows 8
none

### Windows 8.1
none

### Windows 10 (10240)
none

### Windows 10 (10586)
none

### Windows 10 (14393)
none

### Windows 10 (15063)
none

### Windows 10 (16299)
none

### Windows 10 (17134)
none

### Windows 10 (17763)
none
I have no possibilty to check, if these patches actually work.
I cannot support versions just supported by Enterprise or Server editions as I cannot produce the files I need.

### Windows 10 (18362/18363)
none
I have no possibilty to check, if these patches actually work.
I cannot support versions just supported by Enterprise or Server editions as I cannot produce the files I need.
