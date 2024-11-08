# 05_NMAP and ZENMAP Simplified

[NMAP and ZENMAP Simplified 👉VIDEO &#128279;](https://codered.eccouncil.org/courseVideo/Kali-for-Penetration-Testers?lessonId=a83e2407-59c6-4950-a875-8d1613ab4fec&finalAssessment=false)

**Command**

- `nmap 192.168.1.1`
- `nmap abc.com`
- `namep -p abc.com`
- `namep -p 1-100 abc.com`
- `namep -F abc.com`
- `namep -p- 1-65535 -T4 _A -v abc.com`
- `namep -sS abc.com`
- `namep -sU -p 123,161,162 abc.com`
- `namep -A abc.com`
- `namep -sV --version-intensity 0 abc.com`
- `namep -T4 -A -Pn -v abc.com`
- `namep -sn abc.com`
- `namep -oG testoutput.txt abc.com`

**Find script**

- `/usr/share/nmap/script`
- `nmap -v -p 139,445 --script-smb-os-discovery abc.com`
