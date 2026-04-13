# Footprint-Reconnaissance-using-puclic-tools

## 🎯Objective
- Understand the difference between Footprinting and Reconnaissance
- Perform passive footprinting using OSINT tools
- Identify potential information leakage

## 🧠Introduction
This lab focuses on Footprinting and Reconnaissance, which are the first phases of ethical hacking.
- Reconnaissance: Gathering general information about a target
- Footprinting: Collecting detailed data to identify potential entry points

## 🛠️Target used:
- apple.com

## 🛠️Tools Used
- whois
- nslookup
- shodan
- mxtoolbox
- sublister
- wappalyzer

## 1️⃣ Tools: whois
Whois is an Internet protocol that is used to query databases to obtain information about the registration of a domain name

Run this command to see the results:
```
whois apple.com
```
```
EXAMPLE OUTPUT-

Domain Name : apple.com
Registry Domain ID: 1225976_DOMAIN_COM-VRSN
Registrar WHOIS Server: whois.comlaude.com
Registrar URL: http://www.comlaude.com
Updated Date: 2026-02-09T15:4153Z
Creation Date: 1987-02-1905:00:00Z
Registrar Registration Expiration Date: 2027-02-20T05:00:00Z
Registrar: Nom-iq Ltd. dba COM LAUDE
```

## 2️⃣Tools: nslookup
nslookup is used to query DNS servers to find IP addresses, domain records, and troubleshoot network connectivity

Run this command to see the results:
```
nskooup apple.com
```
```
expected output:-
Server:         192.168.100.1
Address:        192.168.100.1#53

Non-authoritative answer:
Name:  apple.com
Address: 17.253.144.10
Name: apple.com
Address: 2620:149:af0:10
```

## 3️⃣ Tools: shodan
Shodan is a search engine for internet‑connected devices that indexes service “banners” HTTP headers, and other metadata from IPv4 address space to reveal exposed systems and configuration risks

Links: https://www.shodan.io/

In search engine insert domain name:
```
apple.com
```
The result will show up all the details.

## 4️⃣ Tools: mxtoolbox

Mxtoolbox is used to diagnose, monitor, and troubleshoot infrastructure issues which is allows you to run multiple network diagnostic tests from a single interface.

Links: https://mxtoolbox.com/

In search engine insert domain name:
```
apple.com
```
The result will show up all the details.

## 5️⃣ Tools: Sublist3r
Sublist3r is designed to enumerate subdomains of websites using OSINT

Run this command to see the results:
```
sublist3r -d apple.com
```
```
Findings:-
www.apple.com
aatcportal.apple.com
abcweb-server.apple.com
account.apple.com
acmdm.apple.com
activate.apple.com
ads.apple.com
agreements.apple.com
agreementsales.apple.com
al-support.apple.com
albert.apple.com
aoschat.apple.com
app-ads.apple.com
appclip.apple.com
appldnld.apple.com
apple-pay.apple.com
appleconnect.apple.com
applegiftcard.apple.com
appleid.apple.com
applenews.apple.com
applepaydemo.apple.com
appleseed.apple.com
appleseeddownload.apple.com
apps.apple.com
appstoreconnect.apple.com
api.appstoreconnect.apple.com
```

## 6️⃣ Tools: Wappalyzer
Wappalyzer is a technology profiler and browser extension that identifies the software, frameworks, CMS, analytics, and tools powering websites

Links: https://www.wappalyzer.com/

In search engine insert domain name:
```
apple.com
```
The result will show up all the details.

## 7️⃣ Tools: Wappalyzer
Wappalyzer is a technology profiler and browser extension that identifies the software, frameworks, CMS, analytics, and tools powering websites

Links: https://www.wappalyzer.com/

In search engine insert domain name:
```
apple.com
```
The result will show up all the details.

## 8️⃣ Tools: netcraft
Netcraft used to discover and explore websites and subdomains associated with a specific domain

Links: https://searchdns.netcraft.com/

In search engine insert domain name:
```
apple.com
```
The result will show up all the details.

## 8️⃣ Tools: Pentest Tools
Pentest Tools is a cloud-based platform that provides an all-in-one toolkit for penetration testing and vulnerability assessment

Links: https://pentest-tools.com/

In search engine insert domain name:
```
apple.com
```
The result will show up all the details.

## 9️ Reverse Image Search
# 9️⃣ Tools: Google Image
Reverse image search will let us know:

Find where an image appears online
Identify the source of the image
Discover related images or info
Links: https://www.google.com/imghp?hl=EN

Just insert or drag the photo that have saved and click the search button.

Findings:

Image found on multiple websites
Possible source identified
Related images discovered
