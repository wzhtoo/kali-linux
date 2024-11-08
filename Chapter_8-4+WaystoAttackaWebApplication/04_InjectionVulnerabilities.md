# 04_Injection Vulnerabilities

[Injection Vulnerabilities 👉VIDEO &#128279;](https://codered.eccouncil.org/courseVideo/Kali-for-Penetration-Testers?lessonId=4a60015b-a64d-4b75-ba41-0b6c8fd6daad&finalAssessment=false)

### A1-Injectino

- Injection flaws, particularly SQL injection, are common in web applications
- Injection occurs when user-supplied data is sent to an interpreter (server side) as part of a command or query
- The attacker's hostile data tricks teh inerpreter into executing unitended commands or changing data
- This way, an attacker can control the database from the apllication
- It occurs when a web application asks a user fro input

## What is inject?

- SQL queries
- PHP queries
- LDAP queries
- OS queries (Using system calls to in turn make calls to the operating system)

Any Web application that relies on the use of an interpreter has the potential to fall victim to this type of flaw.

## A!-Injection Example

### Query behind the Search button:

- `txtUserId = getRequestString("UserId");`
- `txtSQL="SELECT*FROM Users WHERE UserId="+txtUserId`

### SQL injections:

**105;DROP TABLE Learners**

- SELECT\*FROM Users WHERE UserId=105;DROP TABLE Learners;

**105 OR 1=1**

- SELECT\*FROM Users WHERE UserId=105 OR 1=1;

### A1-Injection Protection

- Perform **design and code reviews** on the reusable libraries to ensure security
- **Input/Data validatin** (Whitelisting approach to ensure input isn't malicious code)
- Use of **safe APIs** and parametrized queries
- Run commands with very minimal privileges
