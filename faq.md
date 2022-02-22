---

copyright:
  years: 2021
lastupdated: "2021-03-18"

keywords: bug, problem, faqs, Frequently Asked Questions, question

subcollection: cloud-for-education

---

{:shortdesc: .shortdesc}
{:new_window: target="_blank"}
{:codeblock: .codeblock}
{:faq: data-hd-content-type='faq'}

# FAQs
{: #faq}

Review frequently asked questions for IBM Cloud for Educaiton in {{site.data.keyword.cloud}}. To find all FAQs for {{site.data.keyword.cloud_notm}}, see the [FAQ library](/docs/faqs){: new_window}.
{: shortdesc}

## What happens after I create my service instance?
{: #faq-create-instance}
{: faq}
After you create your service instance order for IBM Cloud For Education, your service instance should be shown on the Resource List and the status of your service instance is "Provision in progress". It means that your have submitted successfully your order and our backend engineer needs to review your order and we might need to reach out to you with some detail questions on your VM environment configuration so we can setup the VM image correctly. Following is the sample questions we'll need your input:

- The name of your institution
- How many potential users will use Applications Lab? (E.g. the size of your institution)
- What is the authentication method do you and your institution want to use to login Applications Lab? You can choose to use your institution federated system to authenticate your users, or IBMid, or customized local account.
- Which user group (on your institution federated system, or list of users) need to have the privilege to create/manage images? And which user group (on your institution federated system, or list of users) need to have the administrator privilege for your institution?
- Do you need to use Windows image? We can provide base Windows 10 Pro image, but you need to bring your own Windows VDA license for your organization. (Windows Server 2019 with license is provided.)
- Do you have any specific access control requirement? For instance, which user group (on your institution federated system, or list of users) need to access which image. You can always submit new request through “Help” on Applications Lab main page.

Once we gather all the information, our engineer will setup and configuration your instance env and once it is completed, the instance status will be set to "Active", and billing will start for that month based on the plan you ordered.  

## What information is required from client to setup Federated Single Sign-On?
{: #faq-setup-sso}
{: faq}
If clients choose to use federated ID authentication, clients need to provide following information:
    1. Download Cloud for Education metadata from https://fed.education.cloud.ibm.com/simplesaml/module.php/saml/sp/metadata.php/default-sp 
    2. Import the downloaded metadata to clients' federated server
    3. Export and email clients' federated server metadata to eduhelp@ibm.com
    4. Configure clinets' federated server to share the necessary attributes includes: email, first name, last name and user groups.

## What information is required from client to setup VPN?
{: #faq-setup-vpn}
{: faq}
If clients' VMs running on IBM Cloud for Education need to access resources on clients' internal network, such as clients' license servers, data etc, we can setup VPN to access clients' internal network, In order to setup VPN, clients need to provide following information to IBM:
    - VPN account
    - VPN connection information (e.g endpoint URL)
    - The name of the image requiring VPN access

## When I order "Base Flex Plan", it says each authorized user entitled for one VM, what if user needs to provision more than one VM? 
{: #faq-Base-Flex-Plan}
{: faq}
**Applications Lab Base Flex Plan** (a.k.a. per authorized user plan) allows maximum one reservation at a time. If you want to have multiple reservations at the same time, please use other plans or use mutiple accounts.

## What happens when I delete my service instance?
{: #faq-delete-instance}
{: faq}
The service instance will not appear on Resource List and billing of the instance stops from next month. IBM Cloud retains the service instance for 7 days and in case you need to restore the same instance back, please raise a support ticket for "IBM Cloud for Education" in 7 days upon deleting instance from IBM Cloud UI. After 7 days, the service instance will be deleted permanently and can no longer be restored. 

## Can't submit block allocation request?
{: #faq-BlockAllocation-Req}
{: faq}
Please make sure that "First Date of Usage" is later than the current time. The time zone by default is UTC. 

## Which model of GPU cards are installed on the servers?
{: #faq-GPU-Model-Supported}
{: faq}
Nvidia V100 is used. Customers cannot access GPU directly, and can only access virtual GPU virtualized from V100. 

## Do you support Operating Systems not shown in the image library, like Ubuntu 20 etc?
{: #faq-OS-Supported}
{: faq}
Yes. We are able to support the most popular Operating Systems in the market, please submit a ticket or click on the help to send us the configuration detail. 
