---

copyright:
  years:  2021
lastupdated: "2021-03-31"

keywords: IBM Blockchain Platform getting started

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

# IBM Blockchain for Education User Guide 
{: #ibp}


Each student will receive access to an instance of the IBM Blockchain Platform. 

The URL will be in the format:
`https://bda-2021-lsu-<000-032>-ibp-console-console.lsu-dev-0b8a4e8de101bcbaf4eafc441eda83b3-0000.us-south.containers.appdomain.cloud`


They will also receive access to a VM on the IBM Cloud for Education available through the URL: 
https://app.education.cloud.ibm.com


## Blockchain for maintaining Digital Assets

Code repository: https://github.com/IBM/Blockchain-for-maintaining-Digital-Assets

In this code pattern, we will be building a digital asset management application by creating and deploying a smart contract on a Hyperledger Fabric Network created on IBM Blockchain Platform. We will then interact with this application via a user interface created using VueJS.

Digital Asset Management Systems ensure that operations are only performed on a digital asset by individuals (or organizations) that have the right access rights and permissions for the asset. The digital asset is defined as the content (an image, a music file, a document, a video file, etc.) and its metadata. The metadata could be as simple as the name of the asset, the name of the owner of the asset and the date of creation of the asset, or it could be something more complex, such as extracted speech from a video (subtitles). In any Digital Asset Management system, there can be any number of users and these users can have the ability to perform various actions on the asset in the system based on the permissions they have. 

When you have completed this code pattern, you will understand how to:

* Package a blockchain smart contract using the IBM Blockchain Platform Extension for VS Code.
* Set up a Hyperledger Fabric network on IBM Blockchain Platform.
* Install and instantiate a smart contract package through IBM Blockchain Platform.
* Set up an instance of the IBM Cloud Object Storage service and connect it with the Node.js application.
* Test the blockchain network by executing a Node.js application with the Hyperledger Fabric SDK to interact with the deployed network by issuing transactions. 



## Watch the video - Introduction and Demo

**Note: Click on the image below to view the video on YouTube. For Google Chrome, press the Ctrl key + the left mouse button and say `Open link`.**

[![](https://user-images.githubusercontent.com/8854447/72086129-6eb48000-32d4-11ea-8869-d6362dd7556a.png)](https://youtu.be/tfnRfDFWHUc)

The code pattern is seperated into these sections: 
1. [Clone the repo](https://github.com/ibm-workshop/bda#1-clone-the-repo)
2. [Package the smart contract](https://github.com/ibm-workshop/bda#2-package-the-smart-contract)
3. [Create the Mailtrap server](https://github.com/ibm-workshop/bda#3-create-the-mailtrap-server)
4. [Build a network](https://github.com/ibm-workshop/bda#4-build-a-network)
5. [Deploy Blockchain for maintaining Digital Assets Smart Contract on the network](https://github.com/ibm-workshop/bda#5-deploy-blockchain-for-maintaining-digital-assets-smart-contract-on-the-network)
6. [Connect application to the network](https://github.com/ibm-workshop/bda#6-connect-application-to-the-network)
7. [Run the application](https://github.com/ibm-workshop/bda#7-run-the-application)

More background and information can be found within the Github repository.
