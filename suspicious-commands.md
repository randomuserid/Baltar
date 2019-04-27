
Suspicious user commands:  these are commands uncommonly run by an ordinary knowledge worker and can be preparatory behavior by a rogue insider.

| Event Type              | Search Paramaters                                                                    |
|-------------------------|--------------------------------------------------------------------------------------|
| Process Create - Sysmon | ammyy.exe                                                                            |
| Process Create - Sysmon | arp –a                                                                               |
| Process Create - Sysmon | at                                                                                   |
| Process Create - Sysmon | auditpol.exe                                                                         |
| Process Create - Sysmon | bruter.exe                                                                           |
| Process Create - Sysmon | cachedump.exe                                                                        |
| Process Create - Sysmon | cmd /c dir "c:\docume~1\<CurrentUser>\desktop" /od                                   |
| Process Create - Sysmon | cmd /c dir “c:\docume~1\<CurrentUser>\recent” /od                                    |
| Process Create - Sysmon | cmd /c dir c:\docume~1\                                                              |
| Process Create - Sysmon | cmd /c dir c:\progra~1\                                                              |
| Process Create - Sysmon | cmd /c net start                                                                     |
| Process Create - Sysmon | cmd /c net use                                                                       |
| Process Create - Sysmon | cmd /c netstat –n                                                                    |
| Process Create - Sysmon | cmd.exe                                                                              |
| Process Create - Sysmon | csvde.exe                                                                            |
| Process Create - Sysmon | curl.exe                                                                             |
| Process Create - Sysmon | dir systemdrive\Users\*.*                                                            |
| Process Create - Sysmon | dir userprofile\AppData\Roaming\Microsoft\Windows\Recent\*.*                         |
| Process Create - Sysmon | dir userprofile\Desktop\*.*                                                          |
| Process Create - Sysmon | dumpel.exe                                                                           |
| Process Create - Sysmon | dumpsec.exe                                                                          |
| Process Create - Sysmon | find.exe                                                                             |
| Process Create - Sysmon | gpresult                                                                             |
| Process Create - Sysmon | gpresult /z                                                                          |
| Process Create - Sysmon | gpresult.exe                                                                         |
| Process Create - Sysmon | gsecdump.exe                                                                         |
| Process Create - Sysmon | hostname                                                                             |
| Process Create - Sysmon | ipconfig /all                                                                        |
| Process Create - Sysmon | ipconfig.exe                                                                         |
| Process Create - Sysmon | lazagne.exe                                                                          |
| Process Create - Sysmon | mimikatz.exe                                                                         |
| Process Create - Sysmon | msdtc [IP] [port]                                                                    |
| Process Create - Sysmon | nc.exe                                                                               |
| Process Create - Sysmon | net localgroup                                                                       |
| Process Create - Sysmon | net share                                                                            |
| Process Create - Sysmon | net start                                                                            |
| Process Create - Sysmon | net use                                                                              |
| Process Create - Sysmon | net user                                                                             |
| Process Create - Sysmon | net user /domain                                                                     |
| Process Create - Sysmon | net user administrator                                                               |
| Process Create - Sysmon | net user administrator /domain                                                       |
| Process Create - Sysmon | net view                                                                             |
| Process Create - Sysmon | net view /domain                                                                     |
| Process Create - Sysmon | net view /domain                                                                     |
| Process Create - Sysmon | net.exe                                                                              |
| Process Create - Sysmon | netcat.exe                                                                           |
| Process Create - Sysmon | netsh                                                                                |
| Process Create - Sysmon | netsh.exe                                                                            |
| Process Create - Sysmon | netstat -ano | find \TCP\                                                            |
| Process Create - Sysmon | netstat -nao                                                                         |
| Process Create - Sysmon | netstat.exe                                                                          |
| Process Create - Sysmon | ping $REMOTE_DEST_IP                                                                 |
| Process Create - Sysmon | powershell.exe                                                                       |
| Process Create - Sysmon | psexec.exe                                                                           |
| Process Create - Sysmon | pwdump                                                                               |
| Process Create - Sysmon | query user                                                                           |
| Process Create - Sysmon | query user                                                                           |
| Process Create - Sysmon | query.exe                                                                            |
| Process Create - Sysmon | quser                                                                                |
| Process Create - Sysmon | rar.exe                                                                              |
| Process Create - Sysmon | rdpclip.exe                                                                          |
| Process Create - Sysmon | regedit.exe                                                                          |
| Process Create - Sysmon | reg query \"HKCU\\SOFTWARE\\Microsoft\\Windows\\CurrentVersion\\Internet Settings\"  |
| Process Create - Sysmon | route                                                                                |
| Process Create - Sysmon | rundll32.exe                                                                         |
| Process Create - Sysmon | sc.exe                                                                               |
| Process Create - Sysmon | sdelete.exe                                                                          |
| Process Create - Sysmon | systeminfo.exe                                                                       |
| Process Create - Sysmon | tasklist                                                                             |
| Process Create - Sysmon | tasklist /fi                                                                         |
| Process Create - Sysmon | tasklist /svc                                                                        |
| Process Create - Sysmon | tasklist /v                                                                          |
| Process Create - Sysmon | tasklist.exe                                                                         |
| Process Create - Sysmon | teamviewer.exe                                                                       |
| Process Create - Sysmon | ver                                                                                  |
| Process Create - Sysmon | vnc                                                                                  |
| Process Create - Sysmon | wce.exe                                                                              |
| Process Create - Sysmon | wget.exe                                                                             |
| Process Create - Sysmon | whoami.exe                                                                           |
| Process Create - Sysmon | winscanx.exe                                                                         |
| Process Create - Sysmon | wmic.exe                                                                             |
