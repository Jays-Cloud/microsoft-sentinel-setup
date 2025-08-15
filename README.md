# Microsoft Sentinel – Whizlabs Lab: Configuring the Environment

Type: Lab Project — AZ-500 Studies  
Skills: Azure Portal, Log Analytics, Microsoft Sentinel, Watchlists, Threat Intelligence, Log Retention

* * *

## Overview

I completed Whizlabs’ **Configuring Microsoft Sentinel Environment** lab to practice the core setup tasks for a fresh Sentinel environment.

Lab link: https://www.whizlabs.com/labs/configuring-microsoft-sentinel-environment

* * *

## Objectives

- Sign in to the **Azure Portal**
- Create a **Log Analytics Workspace**
- Create/enable the **Microsoft Sentinel workspace** (attach Sentinel to the LAW)
- Create a **Watchlist**
- Create a **Threat Indicator**
- Configure **log retention** for the workspace

* * *

## What I Did

### 1) Sign in to Azure Portal
- Signed in at https://portal.azure.com with the provided lab credentials.

### 2) Create a Log Analytics Workspace
- Created a new **Log Analytics Workspace** in the target subscription/resource group.
- Verified region and access.

### 3) Create Microsoft Sentinel Workspace
- Opened **Microsoft Sentinel** and attached it to the newly created workspace.
- Confirmed Sentinel provisioning completed and the workspace appears in Sentinel.

### 4) Create a Watchlist
- Navigated to **Watchlists** in Sentinel and created a new watchlist via CSV file.
- Verified ingestion/availability of the watchlist.

### 5) Create a Threat Indicator
- Opened **Threat intelligence** in Sentinel.
- Added a new **Threat Indicator (TI)** entry and confirmed it was saved and visible.

### 6) Configure Log Retention
- In the **Log Analytics Workspace** settings, configured data **retention** according to lab requirements.
- Confirmed the retention policy was applied.

* * *

## Screenshots

- Log Analytics Workspace created (`screenshots/rgoverview.png`)  
- Sentinel workspace enabled/attached (`screenshots/sentineloverview.png`)  
- Watchlist created (`screenshots/sentinelwatchlist.png`)  
- Threat Indicator added (`screenshots/threatindicatorlog.png`)  
- Log retention configured (`screenshots/logrentention.png`)

* * *

## Next Steps (outside this lab)

- Connect additional data sources (e.g., Azure Activity, Microsoft 365)  
- Explore analytics rules and basic hunting queries  
- Consider SOAR playbooks for notifications or enrichment

* * *

## References

- [Whizlabs – *Configuring Microsoft Sentinel Environment*](https://www.whizlabs.com/labs/configuring-microsoft-sentinel-environment)  
- [Microsoft Docs – *Onboard to Microsoft Sentinel*](https://learn.microsoft.com/en-us/azure/sentinel/quickstart-onboard)
