# Backing Up Dev Machine

## Filezilla
[Filezilla]
- File -> Export
- check Site Manager

## mRemoteNG
[mRemoteNG]
- File -> Export to File

## Notepad++
[Notepad++]
- copy %appdata%\notepad++

## Putty
[Putty]
- regedit /e "%USERPROFILE%\Desktop\putty.reg" HKEY_CURRENT_USER\Software\SimonTatham

## SSH Config
- copy %userprofile%\.ssh\config

contents of config
```
# the_desc
Host the_name
    HostName the_host_address
    User the_userame
    Port the_port
    IdentityFile the_cert
```
