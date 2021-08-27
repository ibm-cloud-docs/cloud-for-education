---

copyright:
  years: 2021
lastupdated: "2021-08-19"

keywords: pricing, plan, metering, concurrent user

subcollection: cloud-for-education

---

{:shortdesc: .shortdesc}
{:new_window: target="_blank"}
{:codeblock: .codeblock}
{:tip: .tip}


# Pricing
{: #pricing}

IBM Cloud for Education has four pricing plans: Lite, Base, Base Flex and Premium.

- This page contains pricing information in USD. To view pricing information in your local currency, see the [IBM Cloud for Education](https://{DomainName}/catalog/education) page in the {{site.data.keyword.cloud}} catalog.
- VSI: Virutal Server Instance
{: tip}

## Lite
{: #lite}

The Lite plan is free for users who are looking to try out IBM Cloud for Education or build a proof-of-concept.

**Pricing**
- Free one reservation with standard configuration size of: 2 vCPU, 8GB RAM, 100GB Disk

## Base
{: #base}

This plan offers charge based on the maximum number of virutal server (also known as Concurrent User) provisioned at any moment of the given month. 

The total capacity offered are:
- A regular VSI configuration size: 2 vCPU, 8GB RAM, 100GB Disk
- Total number of vCPU cores = 2 Cores x the number of concurrent virtual server instance(concurrent user)
- Total memory size = 8 GB x the number of concurrent virutal server instance(concurrent user)
- Total disk size = 200 GB x the number of concurrent virtual server instance concurrent user)

**Pricing** (billed monthly)
- Tier 1: $75/concurrent VSI for the first 1-49 virtual servers
- Tier 2: $71.25/concurrent VSI for 50-99 virtual servers
- Tier 3: $67.50/concurrent VSI for 100-199 virtual servers
- Tier 4: $63.75/concurrent VSI for 200-499 virtual servers
- Tier 5: $60/concurrent VSI for 500-999 virtual servers
- Tier 6: $58.50/concurrent VSI for 1000-1,499 virtual servers
- Tier 7: $56.25/concurrent VSI for 1500-2,999 virtual servers
- Tier 8: $52.50/concurrent VSI for additional virtual servers passing 3,000

**Additional Persistent Storage** 
- $4 per 10 GB per user per month 

## Base Flex (Per User)
{: #baseflexPerUser}

This plan offers charge based on the total number of active user registred in system for the month. it offers each user VSI with standard configuration(2 vCPU, 8GB RAM, 100GB Disk) including OS license for 240 VSI hours each month. If any one user needs to expand the VSI configuration, we will count as additional user based on the expanded VSI configuration. 

**Pricing** (billed monthly)
- Tier 1: $20/user/month for 1-250 users
- Tier 2: $19/user/month for 251-500 users
- Tier 3: $18/user/month for 501-1000 users
- Tier 4: $17/user/month for 1001-2000 users
- Tier 5: $16/user/month for 2001-4000 users
- Tier 6: $15/user/month for over 4000 users

## Base Flex (Per VSI Hour)
{: #baseflexPerVSIHour}
This plan offers charge based on the total number of VSI running hours for your institution/user per month. It offers VSI with standard configuration(2 vCPU, 8GB RAM, 100GB Disk) including OS license. 

**Pricing** (billed monthly)
- $0.45 per hour 

## Premium
{: #premium}

A plan that offers a vGPU support for VSI reservation and charge based on the maximum number of virutal server (also known as Concurrent User) provisioned at any moment of the given month. 

The total capacity offered is:
- A vGPU VSI configuration: 4 vCPU, 16GB RAM, vGPU: 1GB GPU memory, 100GB Disk

**Pricing** (billed monthly)
- Tier 1: $150/concurrent VSI for the first 1-49 virutal servers
- Tier 2: $142.50/concurrent VSI for 50-99 virutal servers
- Tier 3: $135.00/concurrent VSI for 100-199 virutal servers
- Tier 4: $127.50/concurrent VSI for 200-499 virutal servers
- Tier 5: $120/concurrent VSI for 500-999 virutal servers
- Tier 6: $117/concurrent VSI for 1000-1,499 virutal servers
- Tier 7: $112.50/concurrent VSI for 1500-2,999 virutal servers
- Tier 8: $105.00/concurrent VSI for additional virutal servers passing 3,000

**Additional Persistent Storage** 
- $2 per 10 GB per user per month 

