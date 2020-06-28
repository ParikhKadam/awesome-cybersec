# awesome-cybersec
Resources realted to cyber security

## Terminology
1. IoC (Indicator of Compromise) - https://en.wikipedia.org/wiki/Indicator_of_compromise

## Reverse Engineering

### Assembly
1. Assembly obfuscation - https://reverseengineering.stackexchange.com/questions/12507/how-to-obfuscate-x86-assembly-code
2. More details on obfuscation - https://en.wikibooks.org/wiki/X86_Disassembly/Code_Obfuscation

### Compilers and Linkers
1. What is Incremental Linking - https://stackoverflow.com/questions/3349521/what-is-incremental-linking

### Others
1. Tools for .so (shared object) files - https://reverseengineering.stackexchange.com/questions/4624/how-do-i-reverse-engineer-so-files-found-in-android-apks?newreg=c5fdcf661f3d401d944b066853af1d10
2. `hexadecimal` and `base64` encoding of a windows executable - https://stackoverflow.com/questions/36796744/convert-exe-to-hex-to-be-run-by-python

## Cryptography
1. Why `xor` encryption - https://stackoverflow.com/questions/1379952/why-is-xor-used-in-cryptography

## Bug Bounty and PoC
https://github.com/devanshbatham/Awesome-Bugbounty-Writeups

### Bug hunts and its understanding
1. Safari hack to access webcam - https://www.ryanpickren.com/webcam-hacking
2. Stored XSS in Amazon book reads - https://drwetter.eu/amazon/storedXSS-vuln.at.amazon.html

### Reporting
1. How to write bug bounty reports - https://www.hackerone.com/blog/how-bug-bounty-reports-work
2. Example report 1 - https://hackerone.com/reports/128085
3. Example report 2 - https://hackerone.com/reports/115748

## Networking

### Proxies and VPNs
1. No proxy, HTTP proxy and SSL/TLS proxy - https://security.stackexchange.com/questions/61334/does-an-https-proxy-encrypt-traffic-between-proxy-client-and-server-for-http-req/61336#61336
2. Encrypted proxy vs VPN - https://security.stackexchange.com/questions/215231/a-proxy-that-encrypts-your-data-is-the-same-thing-as-a-vpn
3. VPN vs SSL to communicate between machine over internet - https://security.stackexchange.com/questions/1476/what-is-the-difference-in-security-between-a-vpn-and-a-ssl-connection

## Web Security

### URL
1. URL Obfuscation - https://blog.malwarebytes.com/cybercrime/2015/09/obfuscated-urls-where-is-that-link-taking-you/
2. URL fragments and SEO (Google Bot) - https://blog.httpwatch.com/2011/03/01/6-things-you-should-know-about-fragment-urls/

### HTTP
#### Headers
1. Header field information - https://www.w3.org/Protocols/rfc2616/rfc2616-sec14.html
2. Purpose of `accept` and it's interpretability - https://stackoverflow.com/questions/10496570/what-is-the-purpose-of-the-q-values-in-the-http-accept-request-header

#### Response Codes
1. 429 response code - https://stackoverflow.com/questions/22786068/how-to-avoid-http-error-429-too-many-requests-python

### Cross Site Scripting (XSS)
https://github.com/s0md3v/AwesomeXSS

#### Tutorials
1. How does XSS work? - https://security.stackexchange.com/questions/1368/how-does-xss-work
2. Why is it named XSS - https://security.stackexchange.com/questions/135545/why-is-it-called-cross-site-scripting-xss?newreg=77dc88218a21435bb7ffd26246b2653b

#### Tools
1. XSStrike - https://github.com/ParikhKadam/XSStrike

#### Labs
1. XSS Practice Labs - http://leettime.net/xsslab1/chalg1.php
2. Learn XSS by practice - http://prompt.ml/
3. XSS Game - https://xss-game.appspot.com/


### Insecure Direct Object References (IDOR)

#### Tutorials
1. Live example of IDOR - https://medium.com/bugbountywriteup/all-about-getting-first-bounty-with-idor-849db2828c8

### Bypassing Cross Origin Resource Sharing

#### Tutorials
1. Basics (**Note that the 1st hack shown is misleading, read the comments**) - https://www.we45.com/blog/3-ways-to-exploit-misconfigured-cross-origin-resource-sharing-cors?fbclid=IwAR3CH_41UQgrrgC5ZHJxlGihSgw2QXNlPHjqWsqdEXQMS8lTZEPGQ4ISghU
2. Understanding Cross Origin Resource Sharing - https://developer.mozilla.org/en-US/docs/Web/HTTP/CORS#Requests_with_credentials.

## Linux Security

### Privilege Escalation

#### Tutorials
1. Basic - https://payatu.com/guide-linux-privilege-escalation
2. Detailed - https://blog.g0tmi1k.com/2011/08/basic-linux-privilege-escalation/

## Mobile App Security
https://github.com/jdonsec/AllThingsAndroid

### Others
1. Top 5 mobile app security flaws - https://www.allysonomalley.com/2020/06/23/the-top-5-most-common-mobile-app-security-flaws/

