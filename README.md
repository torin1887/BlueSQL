# BlueSQL
# Pen Testing Live Targets

Time spent: **X** hours spent in total

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

Description: Attacker can hack the web page by injecting SQL in the URL https://104.198.208.81/blue/public/staff/countries/show.php?id=1 to delete everything on the page and edit it to how they want with a POST.

GIF WALKTHROUGH: 
## RED

Vulnerability #1: IDOR( Insecure Direct Object Reference)

Description: The attacker can go to the Find Salesperson and change the ID= and look up others information
