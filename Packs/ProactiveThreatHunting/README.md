
## What does this pack do?

The "Proactive Threat Hunting" pack for Cortex XSOAR enables users to initiate threat hunting sessions with the primary goal of identifying undetected threats within their environment. Hunting session summary will be displayed in the new "Threat Hunting" dashboard. This pack supports two distinct hunting methods:

- SDO Hunting: Users can build hypotheses around specific STIX Data Object (SDO) indicators such as Campaigns, Intrusion Sets, or Malware. The pack allows for the search of Indicators of Compromise (IOCs) related to the selected SDO indicator, as well as the identification of tools and tactics used in the corresponding attack pattern.
- Freestyle Hunt: This method empowers threat hunters to execute custom queries, upload their own IOCs, and conduct comprehensive searches and data enrichment on entities within the environment.
Additionally, both hunting methods in the pack offer the capability to take remediation actions directly from the hunting session layout. This includes the ability to block IOCs, isolate endpoints, block accounts, and quarantine files, providing a holistic approach to threat hunting and response.
Overall, the "Proactive Threat Hunting" pack enhances Cortex XSOAR's capabilities by allowing security teams to proactively explore and identify potential threats, providing a powerful toolset to enhance the organization's cybersecurity posture.
