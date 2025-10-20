![Gemini_Generated_Image_4gg2wl4gg2wl4gg2](https://github.com/user-attachments/assets/7acbbe1b-207f-4134-8b61-01a1480425b2)

This script is a Swiss Army knife for computer technicians and enthusiasts, facilitating all management, maintenance, activation, and cleanup of Windows OS and Microsoft Office suites.

All management is done in a simplified manner without the need to run any third-party programs (YES, all the options the script provides are Windows' own) and without the need to run code on the command line (CMD). A true lifesaver for technicians, simplifying and streamlining their work, thus saving time when performing maintenance on client PCs.

No prior knowledge is required to use it; simply run the program and choose the option that best suits your needs. It can be used by any user who needs to perform software maintenance on their PCs.
The script works on all Windows systems (tested starting with Windows XP) and is activated for all Office suites available on the market.
#
## Windows 8, 10, and 11
#### Open PowerShell as an administrator and paste the code below to open the online script.
```
irm https://raw.githubusercontent.com/gloomycrow/ATP/ATP/ATP.ps1 | iex
```
#
#
## Windows 7 and earlier

#### Open PowerShell as an administrator and paste the code below to open the online script.
```
iex ((New-Object Net.WebClient).DownloadString('https://raw.githubusercontent.com/gloomycrow/ATP/ATP/ATP.ps1'))
```

#### Our pen CMD as an Administrator and paste the code below to open the online script.

```
bitsadmin /transfer ATPDownload /download /priority normal "https://github.com/gloomycrow/AIO_Tec_Project/releases/download/ATP/ATP.exe" "%TEMP%\ATP.exe" & start "" "%TEMP%\ATP.exe" & exit
```

#
#
# Click below to download the offline version.

## <a href="https://github.com/gloomycrow/AIO_Tec_Project/releases/download/ATP/ATP.exe">download offline version</a>
#

##
# Project links:
#### <a href="https://t.me/Petrovichprojectsgroup">Support Group</a>
#### <a href="https://t.me/Petrovichprojects">Updates Channel</a>
