---
title: Manage automation file uploads
description: Enable content analysis and configure the file extension and email attachment extensions that will be sumitted for analysis
keywords: automation, file, uploads, content, analysis, file, extension, email, attachment
search.product: eADQiWindows 10XVcnh
ms.prod: w10
ms.mktglfcycl: deploy
ms.sitesec: library
ms.pagetype: security
ms.author: macapara
author: mjcaparas
ms.localizationpriority: high
ms.date: 04/24/2018
---

# Manage automation file uploads

**Applies to:**

- Windows 10 Enterprise
- Windows 10 Education
- Windows 10 Pro
- Windows 10 Pro Education
- Windows Defender Advanced Threat Protection (Windows Defender ATP)

[!include[Prerelease information](prerelease.md)]

>Want to experience Windows Defender ATP? [Sign up for a free trial.](https://www.microsoft.com/en-us/WindowsForBusiness/windows-atp?ocid=docs-wdatp-automationefileuploads-abovefoldlink)

Enable the content analysis capability so that certain files and email attachments can automatically be uploaded to the cloud for additional inspection in Automated investigation.

Identify the files and email attachments by specifying the file extension names and email attachment extension names. 

For example, if you add *exe* and *bat* as file or attachment extension names, then all files or attachments with those extensions will automatically be sent to the cloud for additional inspection during Automated investigation. 

## Add file extension names and attachment extension names.

1. In the navigation pane, select **Settings** > **Rules** > **Automation file uploads**. 

2. Toggle the content analysis setting between **On** and **Off**.

3. Configure the following extension names and separate extension names with a comma:
   - **File extension names** -  Suspicious files except email attachments will be submitted for additional inspection
   - **Attachment extension names** - Suspicious email attachments with these extension names will be submitted for additional inspection



## Related topics
- [Manage automation allowed/blocked lists](manage-automation-allowed-blocked-list-windows-defender-advanced-threat-protection.md)
- [Manage automation folder exclusions](manage-automation-folder-exclusions-windows-defender-advanced-threat-protection.md)