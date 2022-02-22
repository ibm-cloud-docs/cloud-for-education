---

copyright:
  years: 2021
lastupdated: "2021-03-18"

keywords: login, authentication

subcollection: cloud-for-education

content-type: tutorial
services: 
account-plan: lite
Completion-time: 10m

---
{:shortdesc: .shortdesc}
{:screen: .screen}  
{:codeblock: .codeblock}  
{:pre: .pre}
{:tip: .tip}
{:note: .note}
{:external: target="blank" .external}
{:step: data-tutorial-type='step'}


# Getting started with Cloud for Education Applications Lab
{: #getting-started-applications-lab}
{: toc-content-type="tutorial"} 
{: toc-services=""} 
{: toc-completion-time="10m"}


IBM Cloud for Education Applications Lab Provides a powerful customized portal for students & faculty members where applications images can be launched or accessed via a services catalogue on a single pane of glass. It is a public cloud service but able to integrate with academic institution's  private or on-premise lab environment as a hybrid compute model. Students and faculty members can access the virtual desktops and application from any place, any time and on any device. 

## Before you begin
{: #prereqs}
Capacity Planning - decide the number of maximum concurrent user to purcahse:

Planning for the  total number of vCPU and RAM required by defining the number of maximum concurrent users to purchase.


The number of maximum concurrent users usually depend on the total number of users, the number of concurrent classes, or the number of students in classes.
{: note}


Maximum Concurrent User per month: the highest number of VMs running at the same time during the given month.
{: note}

Following is the t-shirt size configuration for regular Virtual Machine which is available in the Base Plan:
- A regular VM size:  2 * vCPU, RAM: 8GB, Disk Size: 200 GB
- Total number of vCPU cores = 2 Cores x the number of concurrent users
- Total memory size = 8 GB x the number of concurrent users
- Total disk size = 200 GB x the number of concurrent users

If you like to have vGPU support, please choose the vGPU Virtual Machine which is available in the Premium Plan:
- A vGPU VM size:   4 * vCPU, RAM: 16GB , vGPU: 1GB GPU memory, Disk Size: 200 GB

If you like to use SPSS only image, please choose the SPSS Plan:
- A regular VM size:  2 * vCPU, RAM: 8GB, Disk Size: 200 GB
- Total number of vCPU cores = 2 Cores x the number of concurrent users
- Total memory size = 8 GB x the number of concurrent users
- Total disk size = 200 GB x the number of concurrent users

Additional Storage option are also available at t-shirt size (100GB/500GB/1000GB/2000GB)

The specific configuration of VM (e.g. vCPU cores, memory size, disk size) is flexible to change to meet your requirement. However the total concurrent resource consumption should be within total resource limitation.
{: note}

<!-- For each step in your tutorial, add an H2 section. The title should be task-oriented and descriptive. Recommendation is no more than 9 steps. -->

## How to order IBM Cloud for Education Applications Lab
{: #order}

<!-- Introduce each major step with a description of what it will accomplish. If there are sequential substeps, use an ordered list for each substep. Don't include the step number. -->

1. Log in to IBM Cloud.
2. Select "IBM Cloud for Education" tile.
3. Choose the plan.
4. Input "The number of concurrent user authorized" based on capacity planning.
5. Choose the capacity of persistent storage for your institution.


## Next steps
{: #next-step}

Activities to complete "Pending for Provisioning":

Our support engineer will reach out to client through email to confirm the authentication method to prepare client’s access to Applications Lab. Following is the activities included to complete the provision request.

1. Setup authentication method: client can request to integrate with client’s LDAP/Directory Server for faculties and students authentication.
2. Configure the access control policy for users.

The duration of the setup usually will take up to few hours for non-LDAP integration and for LDAP integration it may take up to a few days.
{: note}
