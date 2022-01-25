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

## Demo

[![asciicast](https://asciinema.org/a/a7RMNVSXnJqx9GqbiMZ5yCsac.svg)](https://asciinema.org/a/a7RMNVSXnJqx9GqbiMZ5yCsac)



