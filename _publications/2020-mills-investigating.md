---
title: "Investigating Anti-Evasion Malware Triggers Using Automated Sandbox Reconfiguration Techniques"
collection: publications
permalink: /publications/2020-mills-investigating
date: 2020-11-20
venue: 'Journal of Cybersecurity and Privacy'
author: 'Alan Mills and Phil Legg'
paperurl: 'https://www.mdpi.com/2624-800X/1/1/3'
---

Malware analysis is fundamental for defending against prevalent cyber security threats and requires a means to deploy and study behavioural software traits as more sophisticated malware is developed. Traditionally, virtual machines are used to provide an environment that is isolated from production systems so as to not cause any adverse impact on existing infrastructure. Malware developers are fully aware of this and so will often develop evasion techniques to avoid detection within sandbox environments. In this paper, we conduct an investigation of anti-evasion malware triggers for uncovering malware that may attempt to conceal itself when deployed in a traditional sandbox environment. To facilitate our investigation, we developed a tool called MORRIGU that couples together both automated and human-driven analysis for systematic testing of anti-evasion methods using dynamic sandbox reconfiguration techniques. This is further supported by visualisation methods for performing comparative analysis of system activity when malware is deployed under different sandbox configurations. Our study reveals a variety of anti-evasion traits that are shared amongst different malware families, such as sandbox “wear-and-tear”, and Reverse Turing Tests (RTT), as well as more sophisticated malware samples that require multiple anti-evasion checks to be deployed. We also perform a comparative study using Cuckoo sandbox to demonstrate the limitations of adopting only automated analysis tools, to justify the exploratory analysis provided by MORRIGU. By adopting a clearer systematic process for uncovering anti-evasion malware triggers, as supported by tools like MORRIGU, this study helps to further the research of evasive malware analysis so that we can better defend against such future attacks.
