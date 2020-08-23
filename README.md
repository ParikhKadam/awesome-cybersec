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

https://gowsundar.gitbook.io/book-of-bugbounty-tips/

### Getting started
1. Learning path - https://medium.com/hackcura/learning-path-for-bug-bounty-6173557662a7

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
4. How does and intermediate HTTPS proxy work - https://security.stackexchange.com/questions/191759/how-is-intercepting-my-own-https-traffic-possible
5. Explicit vs. Transparent proxy - https://leonelson.com/2016/01/07/explicit-vs-transparent-proxy/

### Sockets
1. Socket - A unique tuple -> (protocol, source address, source port, destination address, destination port)
2. Understanding of TIME_WAIT and SO_REUSEADDR - https://hea-www.harvard.edu/~fine/Tech/addrinuse.html
3. IPv6 basics - https://www.cisco.com/c/en/us/td/docs/interfaces_modules/services_modules/ace/vA5_1_0/configuration/rtg_brdg/guide/rtbrgdgd/ipv6.html

## Web Security

### URL
1. URL Obfuscation - https://blog.malwarebytes.com/cybercrime/2015/09/obfuscated-urls-where-is-that-link-taking-you/
2. URL fragments and SEO (Google Bot) - https://blog.httpwatch.com/2011/03/01/6-things-you-should-know-about-fragment-urls/

### HTTP and Web Browsers
#### Headers
1. Header field information - https://www.w3.org/Protocols/rfc2616/rfc2616-sec14.html
2. Purpose of `accept` and it's interpretability - https://stackoverflow.com/questions/10496570/what-is-the-purpose-of-the-q-values-in-the-http-accept-request-header
3. Purpose of `X-Frame-Options` - https://developer.mozilla.org/en-US/docs/Web/HTTP/Headers/X-Frame-Options

#### Methods
1. `GET` vs. `CONNECT` - https://stackoverflow.com/questions/11697943/when-should-one-use-connect-and-get-http-methods-at-http-proxy-server/40329026

### SSL/TLS
#### Certificates
1. SSL certificate, intermediate certificate and root certificate basics and the chain of trust - https://knowledge.digicert.com/solution/SO16297
2. Difference between root and intermediate certificates - https://www.ssldragon.com/blog/what-is-the-difference-between-root-certificates-and-intermediate-certificates/
3. Advanced understanding of why intermediate certificates - https://www.thesslstore.com/blog/root-certificates-intermediate/

### OAuth 1 and 2
#### Tutorials
1. Understanding OAuth 2 - https://www.digitalocean.com/community/tutorials/an-introduction-to-oauth-2
2. OAuth 1 vs 2 - https://www.synopsys.com/blogs/software-security/oauth-2-0-vs-oauth-1-0/
3. How is OAuth 2 different from OAuth 1 - https://stackoverflow.com/questions/4113934/how-is-oauth-2-different-from-oauth-1
4. Attacks on OAtuh with better understanding of OAuth itself - http://www.bubblecode.net/en/2016/01/22/understanding-oauth2/
5. Attacking OAuth (a better version) - https://dhavalkapil.com/blogs/Attacking-the-OAuth-Protocol/
6. Broadly cover and improve OAuth - https://sakurity.com/oauth
7. OAuth and Phishing attack on it - https://www.youtube.com/watch?v=aU9RsE4fcRM
8. Attacks on OAuth 2 (covers email address based account takeover) - https://medium.com/a-bugz-life/the-wondeful-world-of-oauth-bug-bounty-edition-af3073b354c1
9. Complete guide to OAuth 2 and it's security implications - https://tools.ietf.org/html/rfc6749
10. OAuth vs. OpenID - https://www.gluu.org/blog/oauth-vs-openid-whats-the-difference/
11. OAuth 2.0 vs OpenID Connect vs SAML - https://www.okta.com/identity-101/whats-the-difference-between-oauth-openid-connect-and-saml/
12. PKCE vs. Implicit Grant in OAuth - https://blog.postman.com/pkce-oauth-how-to/

### Exploiting Cross Origin Resource Sharing
#### Tutorials
1. Basics (**Note that the 1st hack shown is misleading, read the comments**) - https://www.we45.com/blog/3-ways-to-exploit-misconfigured-cross-origin-resource-sharing-cors?fbclid=IwAR3CH_41UQgrrgC5ZHJxlGihSgw2QXNlPHjqWsqdEXQMS8lTZEPGQ4ISghU
2. Understanding Cross Origin Resource Sharing - https://developer.mozilla.org/en-US/docs/Web/HTTP/CORS#Requests_with_credentials.

#### Response Codes
1. 429 response code - https://stackoverflow.com/questions/22786068/how-to-avoid-http-error-429-too-many-requests-python

### Cross Site Scripting (XSS)
https://github.com/s0md3v/AwesomeXSS

#### Tutorials
1. How does XSS work? - https://security.stackexchange.com/questions/1368/how-does-xss-work
2. Why is it named XSS - https://security.stackexchange.com/questions/135545/why-is-it-called-cross-site-scripting-xss?newreg=77dc88218a21435bb7ffd26246b2653b
3. Local file read via XSS - https://echopwn.com/local-file-read-via-xss-using-pdf-generate-functionality/
4. Same origin policy - https://en.wikipedia.org/wiki/Same-origin_policy
5. Same origin policy in deep - https://developer.mozilla.org/en-US/docs/Web/Security/Same-origin_policy
6. XSS and same origin policy - https://stackoverflow.com/questions/7012435/cross-site-scripting-attacks-and-same-origin-policy

#### Tools
1. XSStrike - https://github.com/ParikhKadam/XSStrike

#### Labs
1. XSS Practice Labs - http://leettime.net/xsslab1/chalg1.php
2. Learn XSS by practice - http://prompt.ml/
3. XSS Game - https://xss-game.appspot.com/

### Cross Site Request Forgery (CSRF)
Similar to XSS in a way. XSS can further be extended to CSRF.

#### Tutorials
1. What is CSRF? What measures should and should not be taken to precent it? - https://owasp.org/www-community/attacks/csrf 

### Insecure Direct Object References (IDOR)

#### Tutorials
1. Live example of IDOR - https://medium.com/bugbountywriteup/all-about-getting-first-bounty-with-idor-849db2828c8

### Clickjacking
#### Tutorials
1. X-Frame-Options - https://developer.mozilla.org/en-US/docs/Web/HTTP/Headers/X-Frame-Options

### APIs

#### API Discovery
1. Websites for API discovery - https://nordicapis.com/api-discovery-15-ways-to-find-apis/

## Linux Security

### Privilege Escalation

#### Tutorials
1. Basic - https://payatu.com/guide-linux-privilege-escalation
2. Detailed - https://blog.g0tmi1k.com/2011/08/basic-linux-privilege-escalation/

## Mobile App Security
https://github.com/jdonsec/AllThingsAndroid

### Others
1. Top 5 mobile app security flaws - https://www.allysonomalley.com/2020/06/23/the-top-5-most-common-mobile-app-security-flaws/

