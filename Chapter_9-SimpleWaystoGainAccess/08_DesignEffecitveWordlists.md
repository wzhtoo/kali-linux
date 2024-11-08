# 08_Design Effecitve Wordlists

[Design Effecitve Wordlists 👉VIDEO &#128279;](https://codered.eccouncil.org/courseVideo/Kali-for-Penetration-Testers?lessonId=65890dee-7e7c-49af-89cf-bfb0238164f8&finalAssessment=false)

- 👉 [WordLists_1 &#128279;](https://github.com/danielmiessler/SecLists/tree/master/Passwords)

- 👉 [WordLists_2 &#128279;](https://github.com/praetorian-inc/Hob0Rules/tree/master/wordlists)

- 👉 [WordLists_2 &#128279;](https://github.com//Mebus/cupp)

### Cupp

- cd cupp

  - python cupp.py -i

    - First Name: `john`
    - Surname: `scott`
    - Nickname: `johnny`
    - Birthdate (DDMMYYYY): `01031980`

    <hr>

    - Partners) name: `ryan`
    - Partners) nickname: `ray`
    - Partners) birthdate (DDMMYYYY): `02051985`

    <hr>

    - Child's name: `will`
    - Child's nickname: `willy`
    - Child's birthdate (DDMMYYYY): `05071999`

    <hr>

    - Pet's name: `tom`
    - company name: `inovate corp`

    <hr>

    - Do you want to add some key words about the victim? Y/[N]: `handsome, technology`
    - Do you want to add special chars at the end of words? Y/[N]: `Y`
    - Do you want to add some random number at the end of words? Y/[N]: `Y`
    - Leet mode? (i.e. leet = 1337) Y/[N]: `Y`

### Crunch

- crunch
  - `crunch 4 5 abcd123 -o mywordlist.txt`
  - crunch 4 4 abcd123
    - -t @(lowercase)
    - %(number)
    - ,(uppercase)
    - Z(EndLetterZ)
  - `crunch 4 4 abcd123 -t @%,Z -o permutations.txt`
  - `crunch 4 4 -f <file path> loweralpha-numeric -o rainbowl.txt -z gzip`
