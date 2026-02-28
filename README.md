🖥️ Windows Troubleshooting Lab
🔹 Overview

This lab demonstrates my hands-on experience troubleshooting Windows 10/11 system issues including performance problems, BSOD errors, network failures, printer configuration, file sharing, and application crashes.

✅ 1. System Freezing & Slow Performance
Problem

Computer was slow, freezing, and taking long to boot.

Diagnosis

Checked resource usage and startup programs.

Tools Used
Task Manager
msconfig
Disk Cleanup
Actions Taken

Disabled unnecessary startup programs

Cleared temporary files

Performed disk cleanup

Scanned for malware

Result

System performance improved and freezing stopped.

✅ 2. Blue Screen (BSOD) Repair
Problem

System crashed with Blue Screen errors.

Commands Used
sfc /scannow
DISM /Online /Cleanup-Image /RestoreHealth
Result

Corrupted system files were repaired and system stability restored.

✅ 3. Network & Internet Connectivity Issues
Problem

Connected to WiFi/LAN but no internet access.

Commands Used
ipconfig /release
ipconfig /renew
ipconfig /flushdns
ping google.com
Additional Troubleshooting

Changed network profile from Public to Private

Enabled Network Discovery

Enabled File and Printer Sharing

Checked firewall settings

Updated network adapter drivers in Device Manager

Result

Internet and internal network connectivity restored.

✅ 4. Application / Software Crashes
Problem

Applications were freezing or closing unexpectedly.

Tools Used
Event Viewer
%temp%
Device Manager
Actions Taken

Checked Event Viewer logs

Cleared temporary files

Updated drivers

Reinstalled affected applications

Result

Applications functioned normally without crashes.

✅ 5. Printer & File Sharing Issues
Problem

Printer not printing or not visible on network.

Commands Used
net stop spooler
net start spooler
services.msc
Actions Taken

Restarted Print Spooler service

Reinstalled printer drivers

Enabled File & Printer Sharing

Adjusted firewall permissions

Result

Printer connectivity restored across internal network.
