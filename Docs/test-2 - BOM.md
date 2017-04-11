---
# Mandatory fields. See more on aka.ms/skyeye/meta.
title: Intent and product brand in a unique string of 43-59 chars including spaces and | Microsoft Docs 
description: 115-145 characters including spaces. Edit the intro para describing article intent to fit here. This abstract displays in the search result.
services: service-name-with-dashes-AZURE-ONLY 
keywords: Don’t add or edit keywords without consulting your SEO champ.
author: github-alias
ms.author: MSFT-alias-person-or-DL
ms.date: 04/05/2017
ms.topic: article-type-from-white-list
# Use only one of the following. Use ms.service for services, ms.prod for on-prem. Remove the # before the relevant field.
# ms.service: service-name-from-white-list
# product-name-from-white-list

# Optional fields. Don't forget to remove # if you need a field.
# ms.custom: can-be-multiple-comma-separated
# ms.devlang:devlang-from-white-list
# ms.suite: 
# ms.tgt_pltfrm:
# ms.reviewer:
# manager: MSFT-alias-manager-or-PM-counterpart
---
<!---
Definition of Quickstart: 
Fundamental, Day 1 instructions for new customers to use an Azure subscription to quickly use a specific product/service 
(zero to Wow in < 10 minutes).

Purpose of a QuickStart article: To help customers complete a basic task and try the service quickly. 
1. Include short, simple info and steps since customers may be new to service.
2. Don't include multiple ways to complete the task, just one.
-->

# Page heading (H1)
<!---
Unique, complements the page title, and 100 characters or fewer including spaces
-->

*H1 EXAMPLE*: 
Create a Linux virtual machine with the Azure portal

<!---
Intro paragraph: 
1. 1-2 sentences that explain what customers will do and why it is useful.
2. Include a simple image if it will help customers understand how components or a workflow fit together.
-->

*INTRO EXAMPLE 1*:
Learn how to create an Apache Spark cluster in HDInsight and then use a Jupyter notebook to run Spark SQL interactive queries on the Spark cluster.

*INTRO EXAMPLE 2*:
Azure virtual machines can be created through the Azure portal. This method provides a browser-based user interface for creating and configuring VMs and all related Azure resources.

## Prerequisites (optional section)

<!---
Create this section if your article has more than 2 prereqs. For 1-2 prereqs just use an inline statement. Include assumed expertise and required accounts and software. Replace the text below with your content. 
-->

*PREREQ EXAMPLE 1 (inline prereq statement)*:

Before you start, you need both a private and public SSH key. For detailed information on creating SSH keys for Azure, see [Create SSH keys for Azure](https://docs.microsoft.com/en-us/azure/virtual-machines/linux/mac-create-ssh-keys).

*PREREQ EXAMPLE 2* (Pre-reqs as part of 'Prerequisites' section):

## Prerequisites

Before you begin this QuickStart, have the following ready:

- Azure subscription. If you don't have a subscription, you can create a free trial account in just a couple of minutes. See the [Free Trial](https://azure.microsoft.com/en-us/?WT.srch=1&WT.mc_id=AID559320__SEM_81Yn5nkM&) article for details.
- Azure Storage Account. You use the blob storage as a source data store in this tutorial. if you don't have an Azure storage account, see the [Create a storage account](https://docs.microsoft.com/en-us/azure/storage/storage-create-storage-account) article for steps to create one.
- Azure SQL Database. You use an Azure SQL database as a destination data store in this tutorial. If you don't have an Azure SQL database that you can use in the tutorial, See How to create and configure an Azure SQL Database to create one.
- SQL Server 2012/2014 or Visual Studio 2013. You use SQL Server Management Studio or Visual Studio to create a sample database and to view the result data in the database.

<!---
The next set of H2s describes the steps. Each H2 tells users exactly what they will do ("Create a virtual machine", "Create a cluster," "Run Hive queries").
-->

*STEPS EXAMPLE 1*:

## Create a virtual machine

1. Sign in to the Azure portal at http://portal.azure.com.
2. Select the New button found on the upper left-hand corner of the Azure portal.
3. Select Compute from the Marketplace screen, select Ubuntu Server 16.04 LTS from the featured apps screen, and then click the Create button.
4. Fill out the virtual machine basics form. For Authentication type, SSH is recommended. When pasting in your SSH public key, take care to remove any leading or trailing white space. For Resource group, create a new one. A resource group is a logical container into which Azure resources are created and collectively managed.
5. Choose a size for the VM and click Select.
6. On the settings pane, select Yes under Use managed disks, keep the defaults for the rest of the settings, and click OK.
7. On the summary page, click Ok to start the virtual machine deployment.

<!---
For each step, evaluate if a screen shot adds value to the text and include per the following guidelines:
- Use default Public Portal colors
- Browser included in the first shot (especially) but all shots if possible
- Resize the browser to minimize white space
- Include complete blades in the screenshots
- Linux: Safari – consider context in images
- 1px thick boarder
- Border color is 195,195,195
- Red boxes where appropriate
-->

*STEPS EXAMPLE 2*:

## Assign licenses to users

1. Sign into the Azure classic portal as the global administrator of the directory you want to customize.
2. Select *Active Directory*, and then select the directory where you want to assign licenses.
3. Select the *Licenses* tab, select *Active Directory Premium* or *Enterprise Mobility Suite*, and then select *Assign*.

<!--- Screen shot per above guidelines --->

4. In the dialog box, select the users you want to assign licenses to, and then select the check mark icon to save the changes.

<!--- Screen shot per above guidelines --->

<!---
Other guidelines: 
Tip, note, important, warning: Use these extensions SPARINGLY to highlight info that broadens a user's knowledge. *Tip* is an easier way to do something, *Note* is "by the way" info, *Important* is info critical to completing a task, *Warning* is serious potential problem such as data loss.
-->

## Clean up resources

<!--
This section should explicitly remind users to delete or clean up what was created in the above steps so that they do incur losses such as unexpected billing charges. 
-->

*DELETE EXAMPLE:*
When no longer needed, delete the resource group, virtual machine, and all related resources. To do so, select the resource group from the virtual machine blade and click Delete.

Other quick starts in this collection build upon this quick start. If you plan to continue on to work with subsequent quick starts or with the tutorials, do not clean up the resources created in this quick start. If you do not plan to continue, use the following command to delete all resources created by this quick start.

## Next steps

<!---
1. Link to logical next steps. For example: A scenario that requires this task, A tutorial that is a superset of this QuickStart. 
2. Include no more than 3 next steps.
3. Each next step should have a brief description.  A simple list is ideal.
-->

*NEXT STEPS EXAMPLE:*
- Connect and query using SQL Server Management Studio, see [Connect and query with SSMS](sql-database-connect-query-ssms.md)
- Connect using Visual Studio, see [Connect and query with Visual Studio](sql-database-connect-query.md).
- Technical overview of SQL Database, see [About the SQL Database service](sql-database-technical-overview.md).