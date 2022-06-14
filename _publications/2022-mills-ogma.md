---
title: "OGMA: Visualisation for Software Container Security Analysis and Automated Remediation"
collection: publications
permalink: /publication/2022-mills-ogma
date: 2022-06-01
venue: 'IEEE Conference on Cyber Security and Resilience'
author: 'Alan Mills, Jon White, Phil Legg'
paperurl: 'https://www.ieee-csr.org/'
---

The use of software containerisation has rapidly increased in academia and industry which has lead to the production of several container security scanning tools for assessing the security posture and threat of a container image. The variability between tools often differ on the coverage of vulnerabilities, their assessed severity and their output formats. It is also common to find duplicate Common Vulnerabilities and Exposures (CVEs) in their reporting which can often skew the risk assessment of a container. These issues along with the lack of automated solutions for maintaining up-to-date patching of container images are currently open issues identified by the research community that we address in this paper. We present \textit{OGMA}, a visualisation tool for improved analysis and assessment of container security issues across multiple, often conflicting, scanning tools. In addition to severity, our approach helps to examine attack vector and exploit availability, while also removing duplicated CVEs, therefore providing a clearer picture for risk analysts to understand the threat posed by container deployment. Furthermore, we couple this with a novel remediation scheme for updating vulnerable containers whilst ensuring that functionality is preserved, and show how our visualisation system can highlight the improved security posture of the fixed container. Our results highlight the existing security issues in pre-built container images and the inconsistencies between scanning tools, whilst our proposed approach helps to identify and mitigate such threats to improve container security as part of the wider challenges of software supply chain security.
