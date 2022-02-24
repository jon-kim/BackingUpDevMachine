# Backing Up Dev Machine

## Filezilla
[Filezilla](https://filezilla-project.org/)
- File -> Export
- check Site Manager

## mRemoteNG
[mRemoteNG](https://mremoteng.org/)
- File -> Export to File

## Notepad++
[Notepad++](https://notepad-plus-plus.org/)
- copy %appdata%\notepad++

## Putty
[Putty](https://www.putty.org/)
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
