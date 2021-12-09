---

copyright:
  years: 2020
lastupdated: "2020-02-24"

keywords: data encryption in IBM Cloud for Education Applications Lab, data storage for IBM Cloud for Education Applications Lab, personal data in IBM Cloud for Education Applications Lab, data deletion for IBM Cloud for Education Applications Lab, data in IBM Cloud for Education Applications Lab, data security in IBM Cloud for Education Applications Lab

subcollection: _your-subcollection_

---

{:external: target="_blank" .external}
{:shortdesc: .shortdesc}
{:screen: .screen}
{:pre: .pre}
{:table: .aria-labeledby="caption"}
{:codeblock: .codeblock}
{:tip: .tip}

# Securing your data in IBM Cloud for Education Applications Lab
{: #mng-data}
<!-- The title of your H1 should be Securing your data in _service-name_, where _service-name_ is the non-trademarked short version conref, but the trademarked version is used in the first occurrence in this topic. Include your service name as a search keyword at the top of your Markdown file. See the example keywords above. -->

To ensure that you can securely manage your data when you use IBM Cloud for Education Applications Lab, it is important to know exactly what data is stored and encrypted and how you can delete any stored personal data. Data encryption by using IBM managed keys with IBM Cloud for Education Applications Lab.
{: shortdesc}

<!-- Work with your offering's SMEs to fill out the following sections as applicable to your offering. -->

## How your data is stored and encrypted in IBM Cloud for Education Applications Lab
{: #data-storage}

IBM Cloud for Education Applications Lab store data in IBM Cloud Object storage and block storage. Virtual machine images are stored in IBM Cloud Object Storage, and IBM managed key with AES256 is used for encryption. Personal persistent storage is running on IBM VPC Gen2 block storage, IBM managed key with AES256 is used for data encryption, and all data have three replicas in three [zones](/docs/overview?topic=overview-locations) in [MZR](/docs/overview?topic=overview-locations) to maintain high availability.

## Deleting your data in IBM Cloud for Education Applications Lab
{: #data-delete}

You can delete virtual machine images through IBM Cloud for Education Applications Lab website (app.education.cloud.ibm.com).

You can delete personal persistent data on persistent storage by following steps:
- Make an reservation of a virutal machine (VM).
- Delete data on mounted directory on the reserved VM.

### Deleting IBM Cloud for Education Applications Lab instances
{: #service-delete}

_Include information about whether deleting the service fully erases all data. If deleting the service doesn't remove all personal data, include information about how users can completely delete their data._

_Information about how long services keep data after instances are deleted is covered in the service description. Include the following reference for users to find their data retention period._

The _servicename_ data retention policy describes how long your data is stored after you delete the service. The data retention policy is included in the _service-name_ service description, which you can find in the [{{site.data.keyword.cloud_notm}} Terms and Notices](/docs/overview?topic=overview-terms).

