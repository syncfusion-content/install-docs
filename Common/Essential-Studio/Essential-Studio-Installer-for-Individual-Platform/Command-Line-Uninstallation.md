---
layout: post
title: Command-Line-Uninstallation
description: command line uninstallation
platform: js
control: Essential Studio
documentation: ug
---

#### Command Line Uninstallation

Syncfusion Essential Studio supports uninstalling the setup through Command Line in Silent mode. The following steps illustrate this. 

1. When you do not have the extracted setup (SyncfusionEssentialStudio(platform)_(version).exe) then follow the steps from 2 to 7.
2. Double-click the Syncfusion Essential Studio platform Setup file. The Self-Extractor Wizard opens and extracts the package automatically.
3. The SyncfusionEssentialStudio(platform)_(version).exe file is extracted into the Temp folder.
4. Run %temp%. The Temp folder will open. The SyncfusionEssentialStudio(platform)_(version).exe file is available in one of the folders.
5. Copy the SyncfusionEssentialStudio(platform)_(version).exe file in local drive. Example: D:\temp
6. Cancel the Wizard.
7. Open the Command Prompt in administrator mode and pass the following arguments for corresponding version: 



_Essential Studio version 13.1 and earlier:_



“Setup file path\SyncfusionEssentialStudio(platform)_(version).exe” /uninstall true 

Example: “D:\Temp\SyncfusionEssentialStudio(platform)_12.1.0.43.exe" /uninstall true



_Essential Studio version 13.2 and later:_



“Setup file path\SyncfusionEssentialStudio(platform)_(version).exe” /uninstall silent 

Example: “D:\Temp\SyncfusionEssentialStudio(platform)_13.2.0.30.exe" /uninstall silent



8. Setup is uninstalled.



> ![http://help.syncfusion.com/ug/common/ImagesExt/image9_1.png](Command-Line-Uninstallation_images/Command-Line-Uninstallation_img1.png)
{:.image }
_Note: x.x.x.x needs to be replaced with the Essential Studio version installed in your machine and the Product Unlock Key needs to be replaced with the unlock key for that version. Platform should be replaced with asp.net, asp.netmvc, asp.netmvc-classic, silverlight, windowsforms, windowsphone, winrt, wpf, javascript, or lightswitch._

