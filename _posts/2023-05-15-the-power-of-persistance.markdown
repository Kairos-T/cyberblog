---
layout: post
title: "The Power of Persistence: Detecting Adversaries Through Advanced Techniques"
date: 2023-05-15 0:0:0 +0800
categories: Malware
tags: Malware Cybersecurity 
img: https://cdn.pixabay.com/photo/2019/04/14/13/36/scam-4126798_1280.jpg
describe: Adversaries can sustain unauthorised access to infiltrated systems thanks to persistence mechanisms, but they also provide opportunities for detection. 
---

```"Persistence consists of techniques that adversaries use to keep access to systems across restarts, changed credentials, and other interruptions that could cut off their access." - MITRE ATT&CK ™
```

## Background:
One year ago, as I embarked on my exploration of various sectors within ICT, I stumbled upon a Red Canary webinar on persistence. At that point of time, the webinar's dense jargon left me feeling adrift in a sea of technical terms. However, now that I have a deeper understanding of cybersecurity, I found myself drawn back to the webinar that had previously eluded my grasp. Thus, this article is a complilation of the key insights I have gained (finally!) from this webinar.

## Introduction:
Adversaries can sustain unauthorised access to infiltrated systems thanks to persistence mechanisms, but they also provide opportunities for detection. In this article, we examine the importance of persistence in cybersecurity and how businesses can use detection techniques to effectively combat these attacks.

## Understanding Persistence and its Importance:
The ability of an attacker to be able to continue exploiting a compromised asset is referred to as persistence. They are able to carry on despite intermittent disruptions and regain access even after being found and ejected from a network because of it. To accomplish their objectives, which include data collection and lateral movement inside the compromised system, adversaries rely on persistence.

Common Persistence Mechanisms Explored in MITRE ATT&CK:
The MITRE ATT&CK framework lists a variety of persistence approaches to use in Windows, Linux, and macOS environments. Webshells, WMI event subscriptions, registry run keys, and the use of legitimate accounts are a few common techniques. Since adversaries frequently employ many persistence strategies concurrently, thorough coverage is essential for efficient detection.

## Detection Opportunities and Best Practices:
Detecting persistence requires a multi-faceted approach. Some recommended practices include:

1. PowerShell Logging: Makes it easier to spot suspicious activity and encoded commands, giving information on tasks related to persistence.

2. Sysmon and PowerShell CLI: Organisations can examine parent command lines and binary launches using Sysmon and PowerShell's CLI, assisting in the disccovery of persistence activities.
Sysinternals Autoruns: Sysinternals usage Administrators can use Autoruns to look for auto-run entries throughout the system, assisting in the discovery of malicious persistence techniques.

3. OSQuery: Utilising OSQuery's built-in WMI queries makes it easier to identify malicious WMI objects quickly, improving response times.
Anti Malware Scan Interface (AMSI): The detection and prevention of malicious activity within persistent scripts are made possible by AMSI integration with security systems.
Endpoint Detection and Response (EDR)The use of an EDR solution offers thorough visibility into persistence strategies, assisting in the monitoring and analysis of threats connected to persistence.
If that didn't make sense to you, here are some explanations on the jargon:
- Sysmon is a Windows system monitoring tool developed by Microsoft that provides detailed visibility into system activities and helps detect and analyse security-related events.
- Sysinternals Autoruns is a Windows utility that allows users to view and manage programs, processes, services, drivers, and other startup items to optimise system performance and troubleshoot issues.
OSQuery is an open-source, cross-platform framework that enables SQL-based querying of operating system and system-level data, providing a unified interface for monitoring, analysis, and security purposes.
- WMI (Windows Management Instrumentation) is a management infrastructure in Windows that allows administrators to gather information, perform system tasks, and automate management tasks on local and remote systems.
- Adapting to Cloud Environments and Knowledge Sharing:
Adapting detection strategies for persistence becomes increasingly important as businesses move to cloud settings. Comprehensive protection is ensured by using a flexible strategy and relying on security tools designed specifically for the cloud. Through webinars, conferences, and industry forums, the cybersecurity community can collaborate and share expertise to develop defense tactics against persistence-based attacks.

## Conclusion:
Although persistence strategies give attackers the upper hand, they also give room for discovery. Organisations can improve their ability to recognise threats and respond to them by using a variety of detection techniques and understanding common persistence mechanisms. Maintaining alertness, adjusting to new technologies, and promoting cooperation within the cybersecurity community are all components of an effective defence strategy. The capacity to recognise persistence strengthens the security of digital assets by exposing the actions of adversaries.

## References:
1. MITRE ATT&CK Deep Dive: Persistence - Red Canary