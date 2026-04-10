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
#2️⃣Tools: nslookup
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
#3️⃣ Tools: shodan


