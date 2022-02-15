
---

copyright:
  years: 2020
lastupdated: "2020-09-25"

subcollection: education

keywords: HA for eduction, DR for eduction, high availability for eduction, disaster recovery for eduction, failover for eduction

---

{:new_window: target="_blank"}
{:shortdesc: .shortdesc}
{:screen: .screen}
{:pre: .pre}
{:table: .aria-labeledby="caption"}
{:codeblock: .codeblock}
{:tip: .tip}
{:download: .download}

# Understanding high availability for {{site.data.keyword.cloud_notm}} for Education
{: #ha-dr}

 {{site.data.keyword.cloud}} for Education is a managed cloud infrastructure service that is run over IBM Cloud environment. The Apache Virtual Computing Lab (VCL) based management server, storage, and supporting infrastructure all run in IBM Cloud.

{{site.data.keyword.cloud}} for Education is deployed in US South multi-zone region. In multi-zone regions, nodes are distributed across different data centers, or zones. The Management System of this service is deployed in a highly-available configuration. That is, data is replicated by each node onto one or more servers making the data highly available during normal operations.

## Virtual Machine Base Image level High-Availability

Because {{site.data.keyword.cloud}} for Education is a managed service, regular updates and maintenance occurs as part of normal operations. This can occasionally cause short intervals where your service is unavailable.

The base images offered as part of the service or the ones created by the faculty are stored in IBM Cloud object storage. They are pulled to the bare metal server and run locally for each user session. Students can backup their data to the network storage or local directories. 

## Persist Network File Storage High-Availability

In the case of a single zone failure in a multi-zone region or a hardware failure in any region, virtual software images (base image) and data stored in Network File Storage are still accessible as it is replicated onto other zones.

## BareMetal Server High-Availability

The BareMetal servers hosting the virtual machine instances are deployed over three different zones (data centers) in an IBM Cloud region. If one or two zones go down the VM provision service is still resilient and is available. 


## Disaster recovery

{{site.data.keyword.cloud}} for Education provides in-region High Availability and Diaster Recovery Support with minimum Recovery Time Objective (RTO) and Recovery Point Objective (RPO), This offering doesn't support cross-region Disaster Recovery. 

## Client Responsibilities for Backup

Client is responsible for their own backups of their sofware/application data in Virual Machine as well as their data in the persist Nework File Stroage. 

## Data Recovery

Client is resposible for their own data backup, and in the case data is deleted by client's error, {{site.data.keyword.cloud}} for Education support team will help to recover the data on best efforts basis. 
 
