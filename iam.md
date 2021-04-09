---

copyright:
  years:  2021
lastupdated: "2021-03-31"

keywords: IAM access for IBM Cloud for Education, permissions for IBM Cloud for Education, identity and access management for IBM Cloud for Education, roles for IBM Cloud for Education, actions for IBM Cloud for Education, assigning access for IBM Cloud for Education

subcollection: _your-subcollection_

---

{:new_window: target="_blank"}
{:shortdesc: .shortdesc}
{:screen: .screen}
{:pre: .pre}
{:table: .aria-labeledby="caption"}
{:codeblock: .codeblock}
{:tip: .tip}
{:download: .download}
{:important: .important}

_Include this file in the **How to** nav group of your toc file_

# Managing IAM access for IBM Cloud for Education
{: #iam}

Access to `IBM Cloud for Education` service instances for users in your account is controlled by {{site.data.keyword.cloud}} Identity and Access Management (IAM). Every user that accesses the `IBM Cloud for Education` service in your account must be assigned an access policy with an IAM role. Review the following roles, actions, and more to help determine the best way to assign access to `IBM Cloud for Education`. 
{: shortdesc}

The access policy that you assign users in your account determines what actions a user can perform within the context of the service or specific instance that you select. The allowable actions are customized and defined by the `IBM Cloud for Education` as operations that are allowed to be performed on the service. Each actions is mapped to an IAM platform or service role that you can assign to a user.

If a specific role and its actions don't fit the use case that you're looking to address, you can [create a custom role](/docs/account?topic=account-custom-roles#custom-access-roles) and pick the actions to include.
{: tip}

IAM access policies enable access to be granted at different levels. Some of the options include the following: 

* Access across all instances of the service in your account
* Access to an individual service instance in your account <!-- if this applies -->
* Access to a specific resource within an instance, such as the number concurrent users and network file storage.

Review the following tables that outline what types of tasks each role allows for when you're working with the `IBM Cloud for Education` service.

The following table describes the types of tasks that can be completed with each platform management role assigned. Platform management roles enable users to perform tasks on service resources at the platform level, for example, assign user access to the service, create or delete instances, and bind instances to applications.

<!-- IMPORTANT TO ADD: This link should go directly to your service's heading in https://cloud.ibm.com/docs/account?topic=account-iam-service-roles-actions, for example [`service-name`](/docs/account?topic=account-iam-service-roles-actions#certificate-manager) -->
For information about the exact actions mapped to each role, see [`IBM Cloud for Education`](_YourSubHeadingLink_).
{: tip}

<!-- This is a high level view of what the platform roles allow users to do. Use a plain language description about what kind of tasks can be completed or the common jobs to be done that users can expect to accomplish when having each role assigned. -->

| Platform role | Description of actions | 
|--------------------------|------------------------|
| Viewer                   | The viewer can view the service instance.        |
| Administrator            | The administrator can view, edit, delete the service instance.            |
{: row-headers}
{: caption="Table 1. IAM platform roles" caption-side="top"}
{: summary="The rows are read from left to right. The first column is the platform management role. The second column is a description of the actions in the service that the platform management role permits."}




For information about the steps to assign IAM access, see [Managing access to resources](/docs/account?topic=account-assign-access-resources).


