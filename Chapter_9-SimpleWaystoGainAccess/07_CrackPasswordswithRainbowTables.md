# 07_Crack Passwords with Rainbow Tables

[Crack Passwords with Rainbow Tables 👉VIDEO &#128279;](https://codered.eccouncil.org/courseVideo/Kali-for-Penetration-Testers?lessonId=3399d798-a76b-48dc-8969-a04a9969ce47&finalAssessment=false)

**Command**

- rtgen
  - rtgen md5 numeric 1 8 0 1000 1000 0
    - cd /usr/share/rainbowcrack
      - rtsort .
      - rcrack . -h <"hash string">
