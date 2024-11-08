# 04_Understand NETBIOS and SMB Attacks

[Understand NETBIOS and SMB Attacks 👉VIDEO &#128279;](https://codered.eccouncil.org/courseVideo/Kali-for-Penetration-Testers?lessonId=622069c2-ae5b-4379-a764-d73aa5f367ae&finalAssessment=false)

## Command

- `nbtscan -r 192.168.1.6`

| IP address  | NetBIOS Name | Server     | User        | MAC address       |
| ----------- | ------------ | ---------- | ----------- | ----------------- |
| 192.168.1.5 | WZHOTT       | `<Server>` | `<unknown>` | 00:11:22:33:55:66 |

- `enum4linux -a 192.168.1.6`
- `nmap -v -p 139,445 ---script=smb-os-discovery 192.168.1.6`
