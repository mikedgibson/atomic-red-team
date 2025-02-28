# macOS Atomic Tests by ATT&CK Tactic & Technique
# persistence
- [T1156 .bash_profile and .bashrc](./T1156/T1156.md)
  - Atomic Test #1: Add command to .bash_profile [macos, linux]
  - Atomic Test #2: Add command to .bashrc [macos, linux]
- [T1176 Browser Extensions](./T1176/T1176.md)
  - Atomic Test #1: Chrome (Developer Mode) [linux, windows, macos]
  - Atomic Test #2: Chrome (Chrome Web Store) [linux, windows, macos]
  - Atomic Test #3: Firefox [linux, windows, macos]
- [T1136 Create Account](./T1136/T1136.md)
  - Atomic Test #2: Create a user account on a MacOS system [macos]
- T1157 Dylib Hijacking [CONTRIBUTE A TEST](https://atomicredteam.io/contributing)
- [T1158 Hidden Files and Directories](./T1158/T1158.md)
  - Atomic Test #1: Create a hidden file in a hidden directory [linux, macos]
  - Atomic Test #2: Mac Hidden file [macos]
  - Atomic Test #3: Hidden file [macos, linux]
  - Atomic Test #6: Hidden files [macos]
  - Atomic Test #7: Hide a Directory [macos]
  - Atomic Test #8: Show all hidden files [macos]
  - Atomic Test #9: Create Visible Directories [macos, linux]
  - Atomic Test #10: Create hidden directories and files [macos, linux]
- [T1215 Kernel Modules and Extensions](./T1215/T1215.md)
- T1161 LC_LOAD_DYLIB Addition [CONTRIBUTE A TEST](https://atomicredteam.io/contributing)
- [T1159 Launch Agent](./T1159/T1159.md)
  - Atomic Test #1: Launch Agent [macos]
- [T1160 Launch Daemon](./T1160/T1160.md)
  - Atomic Test #1: Launch Daemon [macos]
- [T1152 Launchctl](./T1152/T1152.md)
  - Atomic Test #1: Launchctl [macos]
- [T1168 Local Job Scheduling](./T1168/T1168.md)
  - Atomic Test #1: Cron - Replace crontab with referenced file [macos, centos, ubuntu, linux]
  - Atomic Test #2: Cron - Add script to cron folder [macos, centos, ubuntu, linux]
  - Atomic Test #3: Event Monitor Daemon Persistence [macos, centos, ubuntu, linux]
- T1162 Login Item [CONTRIBUTE A TEST](https://atomicredteam.io/contributing)
- [T1037 Logon Scripts](./T1037/T1037.md)
  - Atomic Test #2: Logon Scripts - Mac [macos]
- [T1150 Plist Modification](./T1150/T1150.md)
  - Atomic Test #1: Plist Modification [macos]
- T1205 Port Knocking [CONTRIBUTE A TEST](https://atomicredteam.io/contributing)
- [T1163 Rc.common](./T1163/T1163.md)
  - Atomic Test #1: rc.common [macos]
- [T1164 Re-opened Applications](./T1164/T1164.md)
  - Atomic Test #1: Re-Opened Applications [macos]
  - Atomic Test #2: Re-Opened Applications [macos]
- T1108 Redundant Access [CONTRIBUTE A TEST](https://atomicredteam.io/contributing)
- [T1166 Setuid and Setgid](./T1166/T1166.md)
  - Atomic Test #1: Setuid and Setgid [macos, centos, ubuntu, linux]
  - Atomic Test #2: Set a SetUID flag on file [macos, centos, ubuntu, linux]
  - Atomic Test #3: Set a SetGID flag on file [macos, centos, ubuntu, linux]
- [T1165 Startup Items](./T1165/T1165.md)
  - Atomic Test #1: Startup Items [macos]
  - Atomic Test #2: Startup Items (emond rule) [macos]
- [T1154 Trap](./T1154/T1154.md)
  - Atomic Test #1: Trap [macos, centos, ubuntu, linux]
- T1078 Valid Accounts [CONTRIBUTE A TEST](https://atomicredteam.io/contributing)
- [T1100 Web Shell](./T1100/T1100.md)

# discovery
- [T1087 Account Discovery](./T1087/T1087.md)
  - Atomic Test #1: Enumerate all accounts [linux, macos]
  - Atomic Test #2: View sudoers access [linux, macos]
  - Atomic Test #3: View accounts with UID 0 [linux, macos]
  - Atomic Test #4: List opened files by user [linux, macos]
  - Atomic Test #5: Show if a user account has ever logger in remotely [linux, macos]
  - Atomic Test #6: Enumerate users and groups [linux, macos]
  - Atomic Test #7: Enumerate users and groups [macos]
- [T1010 Application Window Discovery](./T1010/T1010.md)
- [T1217 Browser Bookmark Discovery](./T1217/T1217.md)
  - Atomic Test #2: List Mozilla Firefox Bookmark Database Files on macOS [macos]
  - Atomic Test #3: List Google Chrome Bookmark JSON Files on macOS [macos]
- [T1083 File and Directory Discovery](./T1083/T1083.md)
  - Atomic Test #3: Nix File and Diectory Discovery [macos, linux]
  - Atomic Test #4: Nix File and Directory Discovery [macos, linux]
- [T1046 Network Service Scanning](./T1046/T1046.md)
  - Atomic Test #1: Port Scan [linux, macos]
  - Atomic Test #2: Port Scan Nmap [linux, macos]
- [T1135 Network Share Discovery](./T1135/T1135.md)
  - Atomic Test #1: Network Share Discovery [macos, linux]
- [T1040 Network Sniffing](./T1040/T1040.md)
  - Atomic Test #2: Packet Capture MacOS [macos]
- [T1201 Password Policy Discovery](./T1201/T1201.md)
  - Atomic Test #7: Examine password policy - macOS [macos]
- [T1069 Permission Groups Discovery](./T1069/T1069.md)
- [T1057 Process Discovery](./T1057/T1057.md)
  - Atomic Test #1: Process Discovery - ps [macos, centos, ubuntu, linux]
- [T1018 Remote System Discovery](./T1018/T1018.md)
  - Atomic Test #4: Remote System Discovery - arp nix [linux, macos]
  - Atomic Test #5: Remote System Discovery - sweep [linux, macos]
- [T1063 Security Software Discovery](./T1063/T1063.md)
  - Atomic Test #3: Security Software Discovery - ps [linux, macos]
- [T1082 System Information Discovery](./T1082/T1082.md)
  - Atomic Test #2: System Information Discovery [linux, macos]
  - Atomic Test #3: List OS Information [linux, macos]
- [T1016 System Network Configuration Discovery](./T1016/T1016.md)
  - Atomic Test #2: System Network Configuration Discovery [macos, linux]
- [T1049 System Network Connections Discovery](./T1049/T1049.md)
  - Atomic Test #3: System Network Connections Discovery Linux & MacOS [linux, macos]
- [T1033 System Owner/User Discovery](./T1033/T1033.md)
  - Atomic Test #2: System Owner/User Discovery [linux, macos]

# execution
- [T1155 AppleScript](./T1155/T1155.md)
  - Atomic Test #1: AppleScript [macos]
- [T1059 Command-Line Interface](./T1059/T1059.md)
  - Atomic Test #1: Command-Line Interface [macos, centos, ubuntu, linux]
- T1203 Exploitation for Client Execution [CONTRIBUTE A TEST](https://atomicredteam.io/contributing)
- T1061 Graphical User Interface [CONTRIBUTE A TEST](https://atomicredteam.io/contributing)
- [T1152 Launchctl](./T1152/T1152.md)
  - Atomic Test #1: Launchctl [macos]
- [T1168 Local Job Scheduling](./T1168/T1168.md)
  - Atomic Test #1: Cron - Replace crontab with referenced file [macos, centos, ubuntu, linux]
  - Atomic Test #2: Cron - Add script to cron folder [macos, centos, ubuntu, linux]
  - Atomic Test #3: Event Monitor Daemon Persistence [macos, centos, ubuntu, linux]
- [T1064 Scripting](./T1064/T1064.md)
  - Atomic Test #1: Create and Execute Bash Shell Script [macos, linux]
- [T1153 Source](./T1153/T1153.md)
  - Atomic Test #1: Execute Script using Source [macos, linux]
  - Atomic Test #2: Execute Script using Source Alias [macos, linux]
- [T1151 Space after Filename](./T1151/T1151.md)
  - Atomic Test #1: Space After Filename [macos]
- T1072 Third-party Software [CONTRIBUTE A TEST](https://atomicredteam.io/contributing)
- [T1154 Trap](./T1154/T1154.md)
  - Atomic Test #1: Trap [macos, centos, ubuntu, linux]
- T1204 User Execution [CONTRIBUTE A TEST](https://atomicredteam.io/contributing)

# lateral-movement
- [T1155 AppleScript](./T1155/T1155.md)
  - Atomic Test #1: AppleScript [macos]
- T1017 Application Deployment Software [CONTRIBUTE A TEST](https://atomicredteam.io/contributing)
- T1210 Exploitation of Remote Services [CONTRIBUTE A TEST](https://atomicredteam.io/contributing)
- [T1037 Logon Scripts](./T1037/T1037.md)
  - Atomic Test #2: Logon Scripts - Mac [macos]
- [T1105 Remote File Copy](./T1105/T1105.md)
  - Atomic Test #1: rsync remote file copy (push) [linux, macos]
  - Atomic Test #2: rsync remote file copy (pull) [linux, macos]
  - Atomic Test #3: scp remote file copy (push) [linux, macos]
  - Atomic Test #4: scp remote file copy (pull) [linux, macos]
  - Atomic Test #5: sftp remote file copy (push) [linux, macos]
  - Atomic Test #6: sftp remote file copy (pull) [linux, macos]
- T1021 Remote Services [CONTRIBUTE A TEST](https://atomicredteam.io/contributing)
- T1184 SSH Hijacking [CONTRIBUTE A TEST](https://atomicredteam.io/contributing)
- T1072 Third-party Software [CONTRIBUTE A TEST](https://atomicredteam.io/contributing)

# collection
- [T1123 Audio Capture](./T1123/T1123.md)
- [T1119 Automated Collection](./T1119/T1119.md)
- [T1115 Clipboard Data](./T1115/T1115.md)
- [T1074 Data Staged](./T1074/T1074.md)
  - Atomic Test #2: Stage data from Discovery.sh [linux, macos]
- T1213 Data from Information Repositories [CONTRIBUTE A TEST](https://atomicredteam.io/contributing)
- [T1005 Data from Local System](./T1005/T1005.md)
  - Atomic Test #1: Search macOS Safari Cookies [macos]
- T1039 Data from Network Shared Drive [CONTRIBUTE A TEST](https://atomicredteam.io/contributing)
- T1025 Data from Removable Media [CONTRIBUTE A TEST](https://atomicredteam.io/contributing)
- [T1056 Input Capture](./T1056/T1056.md)
- [T1113 Screen Capture](./T1113/T1113.md)
  - Atomic Test #1: Screencapture [macos]
  - Atomic Test #2: Screencapture (silent) [macos]
- T1125 Video Capture [CONTRIBUTE A TEST](https://atomicredteam.io/contributing)

# exfiltration
- T1020 Automated Exfiltration [CONTRIBUTE A TEST](https://atomicredteam.io/contributing)
- [T1002 Data Compressed](./T1002/T1002.md)
  - Atomic Test #3: Data Compressed - nix - zip [linux, macos]
  - Atomic Test #4: Data Compressed - nix - gzip Single File [linux, macos]
  - Atomic Test #5: Data Compressed - nix - tar Folder or File [linux, macos]
- [T1022 Data Encrypted](./T1022/T1022.md)
  - Atomic Test #1: Data Encrypted with zip and gpg [macos, centos, ubuntu, linux]
- [T1030 Data Transfer Size Limits](./T1030/T1030.md)
  - Atomic Test #1: Data Transfer Size Limits [macos, centos, ubuntu, linux]
- [T1048 Exfiltration Over Alternative Protocol](./T1048/T1048.md)
  - Atomic Test #1: Exfiltration Over Alternative Protocol - SSH [macos, centos, ubuntu, linux]
  - Atomic Test #2: Exfiltration Over Alternative Protocol - SSH [macos, centos, ubuntu, linux]
  - Atomic Test #3: Exfiltration Over Alternative Protocol - HTTP [macos, centos, ubuntu, linux]
- T1041 Exfiltration Over Command and Control Channel [CONTRIBUTE A TEST](https://atomicredteam.io/contributing)
- T1011 Exfiltration Over Other Network Medium [CONTRIBUTE A TEST](https://atomicredteam.io/contributing)
- T1052 Exfiltration Over Physical Medium [CONTRIBUTE A TEST](https://atomicredteam.io/contributing)
- T1029 Scheduled Transfer [CONTRIBUTE A TEST](https://atomicredteam.io/contributing)

# credential-access
- [T1139 Bash History](./T1139/T1139.md)
  - Atomic Test #1: Search Through Bash History [linux, macos]
- [T1110 Brute Force](./T1110/T1110.md)
- [T1003 Credential Dumping](./T1003/T1003.md)
- [T1081 Credentials in Files](./T1081/T1081.md)
  - Atomic Test #1: Extract Browser and System credentials with LaZagne [macos]
  - Atomic Test #2: Extract passwords with grep [macos, linux]
- T1212 Exploitation for Credential Access [CONTRIBUTE A TEST](https://atomicredteam.io/contributing)
- [T1056 Input Capture](./T1056/T1056.md)
- [T1141 Input Prompt](./T1141/T1141.md)
  - Atomic Test #1: AppleScript - Prompt User for Password [macos]
- [T1142 Keychain](./T1142/T1142.md)
  - Atomic Test #1: Keychain [macos]
- [T1040 Network Sniffing](./T1040/T1040.md)
  - Atomic Test #2: Packet Capture MacOS [macos]
- [T1145 Private Keys](./T1145/T1145.md)
  - Atomic Test #2: Discover Private SSH Keys [macos, linux]
  - Atomic Test #4: Copy Private SSH Keys with rsync [macos, linux]
- T1167 Securityd Memory [CONTRIBUTE A TEST](https://atomicredteam.io/contributing)
- T1111 Two-Factor Authentication Interception [CONTRIBUTE A TEST](https://atomicredteam.io/contributing)

# defense-evasion
- [T1009 Binary Padding](./T1009/T1009.md)
  - Atomic Test #1: Pad Binary to Change Hash - Linux/macOS dd [macos, linux]
- [T1146 Clear Command History](./T1146/T1146.md)
  - Atomic Test #1: Clear Bash history (rm) [linux, macos]
  - Atomic Test #2: Clear Bash history (echo) [linux, macos]
  - Atomic Test #3: Clear Bash history (cat dev/null) [linux, macos]
  - Atomic Test #4: Clear Bash history (ln dev/null) [linux, macos]
  - Atomic Test #6: Clear history of a bunch of shells [linux, macos]
- T1116 Code Signing [CONTRIBUTE A TEST](https://atomicredteam.io/contributing)
- T1500 Compile After Delivery [CONTRIBUTE A TEST](https://atomicredteam.io/contributing)
- [T1089 Disabling Security Tools](./T1089/T1089.md)
  - Atomic Test #5: Disable Carbon Black Response [macos]
  - Atomic Test #6: Disable LittleSnitch [macos]
  - Atomic Test #7: Disable OpenDNS Umbrella [macos]
- T1480 Execution Guardrails [CONTRIBUTE A TEST](https://atomicredteam.io/contributing)
- T1211 Exploitation for Defense Evasion [CONTRIBUTE A TEST](https://atomicredteam.io/contributing)
- [T1107 File Deletion](./T1107/T1107.md)
  - Atomic Test #1: Delete a single file - Linux/macOS [linux, macos]
  - Atomic Test #2: Delete an entire folder - Linux/macOS [linux, macos]
- [T1222 File Permissions Modification](./T1222/T1222.md)
  - Atomic Test #8: chmod - Change file or folder mode (numeric mode) [macos, linux]
  - Atomic Test #9: chmod - Change file or folder mode (symbolic mode) [macos, linux]
  - Atomic Test #10: chmod - Change file or folder mode (numeric mode) recursively [macos, linux]
  - Atomic Test #11: chmod - Change file or folder mode (symbolic mode) recursively [macos, linux]
  - Atomic Test #12: chown - Change file or folder ownership and group [macos, linux]
  - Atomic Test #13: chown - Change file or folder ownership and group recursively [macos, linux]
  - Atomic Test #14: chown - Change file or folder mode ownership only [macos, linux]
  - Atomic Test #15: chown - Change file or folder ownership recursively [macos, linux]
  - Atomic Test #16: chattr - Remove immutable file attribute [macos, linux]
- [T1144 Gatekeeper Bypass](./T1144/T1144.md)
  - Atomic Test #1: Gatekeeper Bypass [macos]
- [T1148 HISTCONTROL](./T1148/T1148.md)
  - Atomic Test #1: Disable history collection [linux, macos]
  - Atomic Test #2: Mac HISTCONTROL [macos, linux]
- [T1158 Hidden Files and Directories](./T1158/T1158.md)
  - Atomic Test #1: Create a hidden file in a hidden directory [linux, macos]
  - Atomic Test #2: Mac Hidden file [macos]
  - Atomic Test #3: Hidden file [macos, linux]
  - Atomic Test #6: Hidden files [macos]
  - Atomic Test #7: Hide a Directory [macos]
  - Atomic Test #8: Show all hidden files [macos]
  - Atomic Test #9: Create Visible Directories [macos, linux]
  - Atomic Test #10: Create hidden directories and files [macos, linux]
- [T1147 Hidden Users](./T1147/T1147.md)
  - Atomic Test #1: Hidden Users [macos]
- T1143 Hidden Window [CONTRIBUTE A TEST](https://atomicredteam.io/contributing)
- T1066 Indicator Removal from Tools [CONTRIBUTE A TEST](https://atomicredteam.io/contributing)
- [T1070 Indicator Removal on Host](./T1070/T1070.md)
  - Atomic Test #3: rm -rf [macos, linux]
- [T1130 Install Root Certificate](./T1130/T1130.md)
- T1149 LC_MAIN Hijacking [CONTRIBUTE A TEST](https://atomicredteam.io/contributing)
- [T1152 Launchctl](./T1152/T1152.md)
  - Atomic Test #1: Launchctl [macos]
- [T1036 Masquerading](./T1036/T1036.md)
- [T1027 Obfuscated Files or Information](./T1027/T1027.md)
  - Atomic Test #1: Decode base64 Data into Script [macos, linux]
- [T1150 Plist Modification](./T1150/T1150.md)
  - Atomic Test #1: Plist Modification [macos]
- T1205 Port Knocking [CONTRIBUTE A TEST](https://atomicredteam.io/contributing)
- [T1055 Process Injection](./T1055/T1055.md)
- T1108 Redundant Access [CONTRIBUTE A TEST](https://atomicredteam.io/contributing)
- [T1014 Rootkit](./T1014/T1014.md)
- [T1064 Scripting](./T1064/T1064.md)
  - Atomic Test #1: Create and Execute Bash Shell Script [macos, linux]
- [T1151 Space after Filename](./T1151/T1151.md)
  - Atomic Test #1: Space After Filename [macos]
- T1078 Valid Accounts [CONTRIBUTE A TEST](https://atomicredteam.io/contributing)
- T1102 Web Service [CONTRIBUTE A TEST](https://atomicredteam.io/contributing)

# command-and-control
- T1043 Commonly Used Port [CONTRIBUTE A TEST](https://atomicredteam.io/contributing)
- T1092 Communication Through Removable Media [CONTRIBUTE A TEST](https://atomicredteam.io/contributing)
- [T1090 Connection Proxy](./T1090/T1090.md)
  - Atomic Test #1: Connection Proxy [macos, linux]
- T1094 Custom Command and Control Protocol [CONTRIBUTE A TEST](https://atomicredteam.io/contributing)
- T1024 Custom Cryptographic Protocol [CONTRIBUTE A TEST](https://atomicredteam.io/contributing)
- [T1132 Data Encoding](./T1132/T1132.md)
  - Atomic Test #1: Base64 Encoded data. [macos, linux]
- T1001 Data Obfuscation [CONTRIBUTE A TEST](https://atomicredteam.io/contributing)
- T1172 Domain Fronting [CONTRIBUTE A TEST](https://atomicredteam.io/contributing)
- T1483 Domain Generation Algorithms [CONTRIBUTE A TEST](https://atomicredteam.io/contributing)
- T1008 Fallback Channels [CONTRIBUTE A TEST](https://atomicredteam.io/contributing)
- T1104 Multi-Stage Channels [CONTRIBUTE A TEST](https://atomicredteam.io/contributing)
- T1188 Multi-hop Proxy [CONTRIBUTE A TEST](https://atomicredteam.io/contributing)
- T1026 Multiband Communication [CONTRIBUTE A TEST](https://atomicredteam.io/contributing)
- T1079 Multilayer Encryption [CONTRIBUTE A TEST](https://atomicredteam.io/contributing)
- T1205 Port Knocking [CONTRIBUTE A TEST](https://atomicredteam.io/contributing)
- T1219 Remote Access Tools [CONTRIBUTE A TEST](https://atomicredteam.io/contributing)
- [T1105 Remote File Copy](./T1105/T1105.md)
  - Atomic Test #1: rsync remote file copy (push) [linux, macos]
  - Atomic Test #2: rsync remote file copy (pull) [linux, macos]
  - Atomic Test #3: scp remote file copy (push) [linux, macos]
  - Atomic Test #4: scp remote file copy (pull) [linux, macos]
  - Atomic Test #5: sftp remote file copy (push) [linux, macos]
  - Atomic Test #6: sftp remote file copy (pull) [linux, macos]
- [T1071 Standard Application Layer Protocol](./T1071/T1071.md)
  - Atomic Test #2: Malicious User Agents - Nix [linux, macos]
- T1032 Standard Cryptographic Protocol [CONTRIBUTE A TEST](https://atomicredteam.io/contributing)
- T1095 Standard Non-Application Layer Protocol [CONTRIBUTE A TEST](https://atomicredteam.io/contributing)
- [T1065 Uncommonly Used Port](./T1065/T1065.md)
  - Atomic Test #2: Testing usage of uncommonly used port [linux, macos]
- T1102 Web Service [CONTRIBUTE A TEST](https://atomicredteam.io/contributing)

# impact
- [T1485 Data Destruction](./T1485/T1485.md)
  - Atomic Test #5: macOS/Linux - Overwrite file with DD [centos, linux, macos, ubuntu]
- T1486 Data Encrypted for Impact [CONTRIBUTE A TEST](https://atomicredteam.io/contributing)
- T1491 Defacement [CONTRIBUTE A TEST](https://atomicredteam.io/contributing)
- T1488 Disk Content Wipe [CONTRIBUTE A TEST](https://atomicredteam.io/contributing)
- T1487 Disk Structure Wipe [CONTRIBUTE A TEST](https://atomicredteam.io/contributing)
- T1499 Endpoint Denial of Service [CONTRIBUTE A TEST](https://atomicredteam.io/contributing)
- T1495 Firmware Corruption [CONTRIBUTE A TEST](https://atomicredteam.io/contributing)
- [T1490 Inhibit System Recovery](./T1490/T1490.md)
- T1498 Network Denial of Service [CONTRIBUTE A TEST](https://atomicredteam.io/contributing)
- [T1496 Resource Hijacking](./T1496/T1496.md)
  - Atomic Test #1: macOS/Linux - Simulate CPU Load with Yes [macos, centos, ubuntu, linux]
- T1494 Runtime Data Manipulation [CONTRIBUTE A TEST](https://atomicredteam.io/contributing)
- T1492 Stored Data Manipulation [CONTRIBUTE A TEST](https://atomicredteam.io/contributing)
- T1493 Transmitted Data Manipulation [CONTRIBUTE A TEST](https://atomicredteam.io/contributing)

# initial-access
- T1189 Drive-by Compromise [CONTRIBUTE A TEST](https://atomicredteam.io/contributing)
- T1190 Exploit Public-Facing Application [CONTRIBUTE A TEST](https://atomicredteam.io/contributing)
- T1200 Hardware Additions [CONTRIBUTE A TEST](https://atomicredteam.io/contributing)
- [T1193 Spearphishing Attachment](./T1193/T1193.md)
- T1192 Spearphishing Link [CONTRIBUTE A TEST](https://atomicredteam.io/contributing)
- T1194 Spearphishing via Service [CONTRIBUTE A TEST](https://atomicredteam.io/contributing)
- T1195 Supply Chain Compromise [CONTRIBUTE A TEST](https://atomicredteam.io/contributing)
- T1199 Trusted Relationship [CONTRIBUTE A TEST](https://atomicredteam.io/contributing)
- T1078 Valid Accounts [CONTRIBUTE A TEST](https://atomicredteam.io/contributing)

# privilege-escalation
- T1157 Dylib Hijacking [CONTRIBUTE A TEST](https://atomicredteam.io/contributing)
- T1068 Exploitation for Privilege Escalation [CONTRIBUTE A TEST](https://atomicredteam.io/contributing)
- [T1160 Launch Daemon](./T1160/T1160.md)
  - Atomic Test #1: Launch Daemon [macos]
- [T1150 Plist Modification](./T1150/T1150.md)
  - Atomic Test #1: Plist Modification [macos]
- [T1055 Process Injection](./T1055/T1055.md)
- [T1166 Setuid and Setgid](./T1166/T1166.md)
  - Atomic Test #1: Setuid and Setgid [macos, centos, ubuntu, linux]
  - Atomic Test #2: Set a SetUID flag on file [macos, centos, ubuntu, linux]
  - Atomic Test #3: Set a SetGID flag on file [macos, centos, ubuntu, linux]
- [T1165 Startup Items](./T1165/T1165.md)
  - Atomic Test #1: Startup Items [macos]
  - Atomic Test #2: Startup Items (emond rule) [macos]
- [T1169 Sudo](./T1169/T1169.md)
  - Atomic Test #1: Sudo usage [macos, linux]
- [T1206 Sudo Caching](./T1206/T1206.md)
  - Atomic Test #1: Unlimited sudo cache timeout [macos, linux]
  - Atomic Test #2: Disable tty_tickets for sudo caching [macos, linux]
- T1078 Valid Accounts [CONTRIBUTE A TEST](https://atomicredteam.io/contributing)
- [T1100 Web Shell](./T1100/T1100.md)

