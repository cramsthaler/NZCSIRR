---
title: "NZ Treasury - Unauthorised access to Budget information"
description: 
date: 2019-05-30
image: 
math: 
license: 
hidden: false
comments: false
draft: false
tags: 
    - Misconfiguration
    - Public Sector
categories:
    - Data Leak
---
**Impacted Agency:**
* NZ Treasury

**Impact:**
* Embargoed Government Budget data leaked

**References:**
* Treasury News page: [https://www.treasury.govt.nz/news-and-events/news/unauthorised-access-budget-information](https://www.treasury.govt.nz/news-and-events/news/unauthorised-access-budget-information) - [Local pdf copy][def] 
* Secondary source:[https://portswigger.net/daily-swig/new-zealand-govt-finds-sufficient-evidence-it-was-hacked](https://portswigger.net/daily-swig/new-zealand-govt-finds-sufficient-evidence-it-was-hacked) - [Local pdf copy][def1]

**Summary:**
* An unknown person exploited a feature in the Treasury's website search tool, but this was not deemed unlawful by the Police, so no further action is planned.
* The Treasury and National Cyber Security Centre are investigating the incident, revealing that a clone of the Treasury website, intended for Budget 2019, contained indexed content that was accessible via specific search terms.
* Approximately 2,000 search terms were used to extract small amounts of information from the 2019/20 Estimates documents, using phrases from the 2018 Budget followed by “Summary” of each Vote.
* The searches were systematic and persistent, involving three IP addresses belonging to the Parliamentary Service, 2degrees, and Vocus.
* The incident led to unauthorized access to limited content from the 2019/20 Estimates documents, intended to be confidential until Budget Day.
* Treasury Secretary Gabriel Makhlouf acknowledged the breach and announced a review to enhance security and prevent future incidents, with the State Services Commissioner asked to conduct an inquiry.

[def]: TheTreasuryNewZealand.pdf
[def1]: TheDailySwig.pdf