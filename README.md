```
  ____ _                                 _ 
 / ___| |__   ___  _ __  _ __   ___ _ __| |
| |   | '_ \ / _ \| '_ \| '_ \ / _ \ '__| |
| |___| | | | (_) | |_) | |_) |  __/ |  |_|
 \____|_| |_|\___/| .__/| .__/ \___|_|  (_)
                  |_|   |_|                

```
<h4 align="center">Chopper - An Automated Security Headers Analyzer</h4>

Chopper is a python script to scrape HTTP Headers from the requests. All you need is to supply a valid domain name. Chopper will automatically check for security related headers, thus saving much of your time.

Currently Chopper is able to check the following headers and flags.

1. Content-Security-Policy 
2. X-XSS-Protection
3. X-Frame-Headers
4. X-Content-Type
5. Strict-Transport-Security
6. Referrer-Policy
7. Feature-Policy
8. Cache-Control Policy
9. Access-Control-Allow-Origin
10. Access-Control-Allow-Credentials
11. HttpOnly Flag
12. Secure Flag

Chopper also provides with the complete list of headers. Thus, providing a better view of all the headers. 

## Required Packages
```
1. Python3
2. Colorama
3. Validators
4. Requests
```
## Installing Dependencies

- pip install -r requirements.txt
- python -m pip install -r requirements.txt

## Flying The Chopper
> python3 Chopper.py http://testphp.vulnweb.com/login.php

```
  ____ _                                 _ 
 / ___| |__   ___  _ __  _ __   ___ _ __| |
| |   | '_ \ / _ \| '_ \| '_ \ / _ \ '__| |
| |___| | | | (_) | |_) | |_) |  __/ |  |_|
 \____|_| |_|\___/| .__/| .__/ \___|_|  (_)
                  |_|   |_|                

 An Automated Security Headers Analyzer
 ------------------------------
 Coded by Kamran Saifullah - Frog Man
 Twitter: https://twitter.com/deFr0ggy 
 GitHub: https://github.com/deFr0ggy 
 LinkedIn: https://linkedin.com/in/kamransaifullah 

 Usage: ./Chopper.py <http|https://example.com>


Domain: http://testphp.vulnweb.com/login.php

[-] Content-Security-Policy is not in place!
[-] X-XSS-Protection - XSS Protection is not in place!
[-] X-Frame-Headers - ClickJacking Protection is not in place!
[-] X-Content-Type - MIME Sniffing Protection is not in place!
[-] Strict-Transport-Security - Protection is not in place!
[-] Referrer-Policy is not in place!
[-] Feature-Policy is not in place!
[-] Cache-Control Policy is not in place!
[-] Access-Control-Allow-* - CORS Policy is not in place!
[-] HttpOnly Flag is not in place!
[-] Secure Flag is not in place!


[-] Check These Headers Out! 


Server:  nginx/1.19.0
Date:  Sun, 19 Dec 2021 09:15:46 GMT
Content-Type:  text/html; charset=UTF-8
Transfer-Encoding:  chunked
Connection:  keep-alive
X-Powered-By:  PHP/5.6.40-38+ubuntu20.04.1+deb.sury.org+1
Content-Encoding:  gzip

```

