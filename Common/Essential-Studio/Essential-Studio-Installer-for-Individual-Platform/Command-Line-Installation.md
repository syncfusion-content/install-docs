---
layout: post
title: Command-Line-Installation
description: command line installation
platform: js
control: Essential Studio
documentation: ug
---

#### Command Line Installation

Follow the steps below to install through Command Line in Silent mode.

1. Double-click the Syncfusion Essential Studio platform Setup file. The Self-ExtractorWizard opens and extracts the package automatically.
2. The SyncfusionEssentialStudio(platform)_(version).exe file is extracted into the Temp folder.
3. Run %temp%. The Temp folder will open. The SyncfusionEssentialStudio(platform)_(version).exe file is available in one of the folders.
4. Copy the SyncfusionEssentialStudio_(version).exe file in local drive. Example: D:\temp
5. Cancel the Wizard.
6. Open the Command Prompt in administrator mode and pass the following arguments for corresponding version:



_Essential Studio version 13.1 and earlier:_



“Setup file path\SyncfusionEssentialStudio(platform)_(version).exe” Install /PIDKEY:“(product unlock key)” [/log “{Log file path}”] [/InstallPath: {Location to install}] 

> ![http://help.syncfusion.com/ug/common/ImagesExt/image9_1.png](Command-Line-Installation_images/Command-Line-Installation_img1.png)
{:.image }
_Note: [..] – Arguments inside the square brackets are optional._



Example: “D:\Temp\SyncfusionEssentialStudio(platform)_12.1.0.43.exe” Install /PIDKEY:“product unlock key” /log “C:\Temp\EssentialStudio_Platform.log” /InstallPath:C:\Syncfusion\x.x.x.x 



_Essential Studio version 13.2 and later:_



“Setup file path\SyncfusionEssentialStudio(platform)_(version).exe” /Install silent /PIDKEY:“(product unlock key)” [/log “{Log file path}”] [/InstallPath:{Location to install}] [/InstallSamples:{true/false}] [/InstallAssemblies:{true/false}] [/UninstallExistAssemblies:{true/false}] [/InstallToolbox:{true/false}]

> ![http://help.syncfusion.com/ug/common/ImagesExt/image9_1.png](Command-Line-Installation_images/Command-Line-Installation_img2.png)
{:.image }
_Note: [..] – Arguments inside the square brackets are optional._



Example: “D:\Temp\SyncfusionEssentialStudio(platform)_13.2.0.30.exe” /Install silent /PIDKEY:“product unlock key” /log “C:\Temp\EssentialStudio_Platform.log” /InstallPath:C:\Syncfusion\x.x.x.x /InstallSamples:true /InstallAssemblies:true /UninstallExistAssemblies:true /InstallToolbox:true

> ![http://help.syncfusion.com/ug/common/ImagesExt/image9_1.png](Command-Line-Installation_images/Command-Line-Installation_img3.png)
{:.image }
_Note: We have provided Advanced Options in silent installation from 13.2.0.x._



7. Setup is installed.
> 
![http://help.syncfusion.com/ug/common/ImagesExt/image9_1.png](Command-Line-Installation_images/Command-Line-Installation_img4.png)
{:.image }
_Note: x.x.x.x needs to be replaced with the Essential Studio version installed in your machine and the Product Unlock Key needs to be replaced with the Unlock Key for that version. The platform should be replaced with asp.net, asp.netmvc, asp.netmvc-classic, silverlight, windowsforms, windowsphone, winrt, wpf, javascript, or lightswitch._

