# Incident Report

> **Code:** IR-TEAM-9999 *(Divided in three sections - IR: incident report, TEAM: a code for the team, 9999: incremental number)*  
> **Title:** *Title of the incident. Summarizes the problem from a business perspective whenever possible*   
> **Start Date:** *Date that the problem started to happen (may not be equal to the date when it has been evidenced)*  
> **End Date:** *Date that the problem stopped to happen (i.e. the root cause was deployed, the data was fixed, etc)*  
> **Owner:** *Person responsible to build this report (i.e. describe the incident, resolution, discuss future preventions, etc.). **It must not be confused with any sort of blaming***
> **Participants:** *People that have helped to build this report*  
> **Teams:** *Teams responsible for deploying the all needed fixings and future preventions*
> **Status:** *Status of the incident:*
>  - IN PROGRESS: the incident is already known but is still occurring
>  - MONITORING: the incident has been mitigated, its root cause has beent fixed
>  - RESOLVED: after the fixing has been validated and monitored to make sure it solved the incident, it can be marked as “resolved” (future preventions ideally are already implemented by now)

---  

## Summary
> This section aims to give a broad picture of what happened, how it was caught, how the business was impacted, what was done to fix it, and what will be done to prevent this same incident to happen in the future.  
> Think of this section as a TL;DR  

## Business Impact
> This section aims to give in details how the business was impacted by this incident.
Examples (but not limited to): cancelled orders, systems downtime, data loss.  
> It can also be a purely technical impact (eg. broken deployment pipelines). In this case, try to specify what processes were impacted (e.g. deploys of system XPTO were stuck during N minutes, Y builds failed, etc).  
> Try to be more detailed as possible - if needed, have all the affected data on a external spreadsheet and link it here (but include here the top cases, or just the total number).  

## Incident Description
> In this section, describe what caused the incident, why it happened, and its symptoms, wrapping it up with a summary of the impact (as it has already been described in the previous section)  
> Except for the impact, try to be more detailed as possible. Include timestamps of any sort of event (e.g. a faulty deploy was done at YYYY-MM-DD H:i:s, Team X was alerted at YYYY-MM-DD H:i:s), links for opened tickets, graphs, log records, etc. The goal is to give an in-depth view to help the reader understand what happened.  
> **IMPORTANT: describe the incident without blaming anyone, including yourself, and without any bias. The goal here is to make the opportunities of improvement clear.**

## Resolution
> In this section, describe what steps have been taken to mitigate and solve the incident. It can be built as a timeline. 

## Root Cause Analysis
> The goal of this section is to describe what in fact caused this incident and prevented an earlier resolution. Try to go deeper in the analysis. The [“5 whys”](https://en.wikipedia.org/wiki/Five_whys) technique can be helpful.  
> For example, if a bug caused the incident, try to think why it wasn’t detected before going to production and why it took some time to notice it.

## Future Prevention
| Action                                                                                                                                                                                                                                                         | Responsible                                            | Status                | Due date                                               | Notes                                                           |
|----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|--------------------------------------------------------|-----------------------|--------------------------------------------------------|-----------------------------------------------------------------|
| What will be done in order to prevent another incident like this one to happen again? Examples (but not limited to): develop or refactor something new in the system, write tests for a specific scenario, include more logs, change or create a process, etc. | The person responsible to have this action implemented | Status of this action | Expected due date for this action be fully implemented | Include here links to Jira cards, describe the new process, etc |
|                                                                                                                                                                                                                                                                |                                                        |                       |                                                        |                                                                 |
