# Level 1

## Task 1
**Hash:** 48bb6e862e54f2a795ffc4e541caed4d

**Method:** Paste into crackstation

**Type:** md5

**Flag:** easy

## Task 2
**Hash:** CBFDAC6008F9CAB4083784CBD1874F76618D2A97 

**Method:** /

**Type:** sha1

**Flag:** password123

## Task 3
**Hash:** 1C8BFE8F801D79745C4631D09FFF36C82AA37FC4CCE4FC946683D7B336B63032

**Method:** /

**Type:** sha256

**Flag:**letmein

## Task 4
**Hash:** $2y$12$Dwt1BZj6pcyc3Dy1FWZ5ieeUznr71EeNkJkUlypTsgbX1H68wsRom

**Method:**  

- Use hashcat 'hashcat.exe -b'
- '$2y$' indicates it is a bcrypt hash
- use command: hashcat -m 3200 -a 0 Hash/hash.txt Dict/rockyou.txt

**Flag:** bleh

## Task 5
**Hash:** 279412f945939ba78ce0758d3fd83daa 

**Method:** use command: hashcat -m 900 -a 0 Hash/hash.txt Dict/rockyou.txt

**Type:** md4

**Flag:** bleh

# Level 2

## Task 1
**Hash:**  F09EDCB1FCEFC6DFB23DC3505A882655FF77375ED8AA2D1C13F640FCCC2D0C85

**Method:**hashcat -m 1400 -a 0 Hash/hash.txt Dict/rockyou.txt

**Type:** sha256

**Flag:** paule

## Task 2
**Hash:** 1DFECA0C002AE40B8619ECF94819CC1B

**Method:** use command: hashcat -m 1000 -a 0 Hash/hash.txt Dict/rockyou.txt

**Type:** NTLM

**Flag:** n63umy8lkf4i

## Task 3
**Hash:**  $6$aReallyHardSalt$6WKUTqzq.UQQmrm0p/T7MPpMbGNnzXPMAXi4bJMl9be.cfi3/qxIf hsGpS41BqMhSrHVXgMpdjS6xeKZAs02

**Salt:**  aReallyHardSalt

**Method:** use command: hashcat -m 1800 -a 0 Hash/hash.txt Dict/rockyou.txt

**Flag:** waka99

## Task 4
**Hash:** e5d8870e5bdd26602cab8dbe07a942c8669e56d6

**Salt:** tryhackme

**Method:** use command: hashcat -m 110 -a 0 Hash/hash.txt Dict/rockyou.txt

**Flag:** 481616481616