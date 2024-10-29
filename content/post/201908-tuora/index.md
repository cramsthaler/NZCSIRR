---
title: "Cyber security breach at Tū Ora Compass Health"
description: 
date: 2019-08-05
image: 
math: 
license: 
hidden: false
comments: false
draft: false
tags: 
    - Tū Ora Compass Health

categories:
    - Data Leak
    - Web Defacement
    - Vulnerability
    - Private Sector
---
**Impacted Agency:**
* Tū Ora Compass Health

**Impact:**
* Health data for approx 1 Million New Zealander exposed
* Web Defacement

**References:**
* Report Health NZ: [https://www.health.govt.nz/system/files/documents/pages/weekly_report_item_16_august_2018_-_tu_ora_compass_health_incident_redacted.pdf](https://www.health.govt.nz/system/files/documents/pages/weekly_report_item_16_august_2018_-_tu_ora_compass_health_incident_redacted.pdf) -  [Local Copy](HealthNZ_report.pdf) 
* Memorandum Health NZ: [https://www.health.govt.nz/system/files/documents/pages/memorandum_13_september_20191772_redacted.pdf](https://www.health.govt.nz/system/files/documents/pages/memorandum_13_september_20191772_redacted.pdf) - [Local Copy](HealthNZ_Memorandum.pdf)
* Video Press Conference: Ministry of Health responds to unauthorised digital intrusion at Tū Ora Compass Health: [https://www.youtube.com/watch?v=eIFJzc9msaI](https://www.youtube.com/watch?v=eIFJzc9msaI)
* Stuff NZ: [https://www.stuff.co.nz/dominion-post/news/116318497/up-to-1-million-new-zealand-patients-data-breached-in-criminal-cyber-hack](https://www.stuff.co.nz/dominion-post/news/116318497/up-to-1-million-new-zealand-patients-data-breached-in-criminal-cyber-hack) - [Local pdf copy](StuffNZ.pdf)
* RNZ: [https://www.rnz.co.nz/news/national/400337/pho-hack-more-data-breaches-found-involving-up-to-a-million-patients](https://www.rnz.co.nz/news/national/400337/pho-hack-more-data-breaches-found-involving-up-to-a-million-patients) - [Local pdf copy](RNZNews.pdf)

**Summary:**
* A high-level timeline of the incident is as follows:
  * a. 10 July 2019 - Tū Ora was directly contacted by the NCSC notifying them that their web server was exposed to a publicly known vulnerability from 2017. This was not actioned by Tū Ora or their IT service provider.
  * b. 5 August 2019 - Tū Ora web server was exploited by this method and the attacker ‘defaced’ their website, ultimately alerting Tū Ora that they had been attacked.
  * c. 6 August 2019 - Ministry of Health was notified by Tū Ora of the successful attack on their website. Tū Ora Compass Health took immediate steps to contain the incident, called in experts to start an investigation, and notified CERT NZ and the NCSC.
  * d. 8 August 2019 - The NCSC initiated a forensic investigation; this is continuing and is expected to take a further two to three weeks.
  * e. 15 August 2019 – Tū Ora issued a press release stating that is website had come under attack but did not disclose the likelihood that unencrypted personally identifiable information was also stored on that same server.
  * f. 15 August 2019 – NCSC provided an update that three further server exploits were found on the server. Based on the information available to date, the server was compromised twice in 2016, and twice in 2019.
* Additionally, access to Tū Ora’s environment would provide access to data held on over one million people that have lived within the geographic area of Capital and Coast, Wairarapa and Mid Central DHBs and registered with a GP over the last 17 years.
* Privacy Commissioner John Edwards said his office was notified of the breach in early September then had a full briefing on September 9.
  * "At the time I was briefed, it appeared that the vulnerability did not compromise detailed patient information such as consultation notes, however I was advised that there was a risk that enrolment records, including identifying information, diagnostic codes and lab results might have been able to be accessed by a third party.
  * "I was advised that it was not possible to say with certainty whether any of that identifiable data had been accessed and/or exfiltrated." 