# DeactivateWindowsAV

```
https://woshub.com/disable-windows-defender-antivirus/

Deactivate AV prot - everything under antiwvirus GUI

cmd - admin - resmon
Open Resource Monitor (type resmon.exe in the search box)
Overview
Find MsMpEng.exe in the list
Right-click > Suspend Process

go to gpo
disable

Open Local Group Policy Editor (type gpedit in the search box).
Go to Computer Configuration > Administrative Templates > Windows Components > Microsoft Defender Antivirus > Real-time Protection.
Enable "Turn off real-time protection".
Reboot.
```
