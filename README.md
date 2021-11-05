# IST5930
# Project 8 - Pentesting Live Targets

Time spent: **6** hours spent in total

> Objective: Identify vulnerabilities in three different versions of the Globitek website: blue, green, and red.

The six possible exploits are:

* Username Enumeration
* Insecure Direct Object Reference (IDOR)
* SQL Injection (SQLi)
* Cross-Site Scripting (XSS)
* Cross-Site Request Forgery (CSRF)
* Session Hijacking/Fixation

Each color is vulnerable to only 2 of the 6 possible exploits. First discover which color has the specific vulnerability, then write a short description of how to exploit it, and finally demonstrate it using screenshots compiled into a GIF.

## Blue

Vulnerability #1: SQL Injection


![blue-vuln1](https://user-images.githubusercontent.com/79621826/140460894-4a3856df-4a99-4024-b7d9-1ec7e1756a0e.gif)

Description: I added a ' at the end of the URL and the page doesn't redirect it says database query failed. This shows that an SQL vulnerability exists.


## Green

Vulnerability #1: User enumeration
![green-vuln1](https://user-images.githubusercontent.com/79621826/140461211-486e61a1-7c52-40db-8220-1412a4ba466b.gif)

Description: When I inputted a username and random password that didn't exist "Log in was unsuccessful" is displayed, but once I used the jmonroe99 username and password "Log in was unsuccessful" is displayed again but in bold because that user does exist.



## Red

Vulnerability #1: Insecure direct object reference
![red-vuln1](https://user-images.githubusercontent.com/79621826/140461512-1bb3c971-9003-4ee1-a2bf-769a2ec7a973.gif)

Description: We are able to access the private salesperson database by typing in 10 and 11 into "id=" I was able to see private information and a reasoning for someone being fired.


Vulnerability #2: Cross site request forgery
![red-vuln2](https://user-images.githubusercontent.com/79621826/140461929-cdbbed43-2905-4a4b-9c90-02e05c1853ab.gif)

Description: I was able to make changes to the user database and the site accepts post requests from a different source that contains a hidden form. 



## Notes

Describe any challenges encountered while doing the work
