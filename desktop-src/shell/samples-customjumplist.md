---
Description: Demonstrates how to create a custom Jump List for an application, including adding a custom category and tasks.
title: Custom Jump List Sample
ms.topic: article
ms.date: 05/31/2018
ms.assetid: 60DEDB01-8F8F-4c25-8FCC-8EAC461A99B7
api_name: 
api_type: 
api_location: 
topic_type: 
 - kbArticle

---

# Custom Jump List Sample

Demonstrates how to create a custom Jump List for an application, including adding a custom category and tasks.

This topic contains the following sections.

-   [Requirements](#requirements)
-   [Downloading the Sample](#downloading-the-sample)
-   [Building the Sample](#building-the-sample)
-   [Running the Sample](#running-the-sample)
-   [Related topics](#related-topics)

## Requirements



| Product                                | Minimum Product Version |
|----------------------------------------|-------------------------|
| Windows                                | Windows 7               |
| Windows Software Development Kit (SDK) | 7.0                     |



 

## Downloading the Sample

This sample is available in the following locations.



| Location      | Path URL                                                                                             |
|---------------|------------------------------------------------------------------------------------------------------|
| Code Gallery  | [Windows Shell Integration Samples on Code Gallery](https://code.msdn.microsoft.com/shellintegration) |
| Windows 7 SDK | [Download Windows 7 SDK](https://msdn.microsoft.com/windowsvista/bb980924.aspx)                            |



 

In the case of the Windows SDK, once you have downloaded and installed it, you will find the samples in the installed directory. For example, use of the default installation path for the Windows 7 SDK results in the samples being placed under `C:\Program Files\Microsoft SDKs\Windows\v7.0\Samples\`.

## Building the Sample

To build the sample from the command prompt:

1.  Open the command prompt window and navigate to the **CustomJumpList** project directory.
2.  Enter `msbuild CustomJumpListSample.sln`.

To build the sample using Microsoft Visual Studio (preferred):

1.  Open Windows Explorer and navigate to the **CustomJumpList** project directory.
2.  Double-click the icon for the CustomJumpListSample.sln file to open the project in Visual Studio.
3.  From the **Build** menu, select **Build Solution**.

## Running the Sample

1.  Navigate to the directory that contains the new executable, using the command prompt or Windows Explorer.
2.  At the command line, enter `CustomJumpListSample.exe`. Alternatively, from Windows Explorer double-click the icon for CustomJumpListSample.exe.
3.  This sample must be run as an administrator the first time it is run so that it can install the necessary file type registrations. After the file types have been registered, the sample can run as a standard user.
4.  Select options from the menu in the sample application to see how they affect the application's Jump List in the taskbar.

## Related topics

<dl> <dt>

[Application User Model IDs (AppUserModelIDs)](appids.md)
</dt> </dl>

 

 



