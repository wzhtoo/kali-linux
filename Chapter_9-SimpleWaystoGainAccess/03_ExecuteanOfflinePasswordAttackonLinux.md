# 03_Execute an Offline Password Attack on Linux

[Execute an Offline Password Attack on Linux 👉VIDEO &#128279;](https://codered.eccouncil.org/courseVideo/Kali-for-Penetration-Testers?lessonId=0a731165-f59a-463f-a08c-b40c5995fd3b&finalAssessment=false)

### Application and tools

- hashcat
- hash-identifier

**Coomand**

- `hashcat -m 1800 -a 0 -o cracked.txt hackedhash.lst wordlist.txt --force`
