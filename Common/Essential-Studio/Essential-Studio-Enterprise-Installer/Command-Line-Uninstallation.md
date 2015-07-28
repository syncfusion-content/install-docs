---
layout: post
title: Command-Line-Uninstallation
description: command line uninstallation
platform: js
control: Essential Studio
documentation: ug
---

#### Command Line Uninstallation

Syncfusion Essential Studio supports uninstalling the setup through Command Line in Silent mode. The following steps help you uninstall the setup. 

1. When you do not have the extracted setup (SyncfusionEssentialStudio_(version).exe) then follow the steps from 2 to 7.
2. Double-click the Syncfusion Essential Studio Setup file. The Self-ExtractorWizard opens and extracts the package automatically.
3. The SyncfusionEssentialStudio_(version).exe file gets extracted into the Temp folder.
4. Run %temp%. The Temp folder opens. The SyncfusionEssentialStudio_(version).exe file is available in one of the folders.
5. Copy the SyncfusionEssentialStudio_(version).exe file in local drive. Example: D:\temp
6. Cancel the wizard.
7. Open the Command Prompt in administrator mode and pass the following arguments for corresponding version: 



_Essential Studio version 13.1 and earlier:_



“Setup file path\SyncfusionEssentialStudio_(version).exe” /uninstall true 

Example: “D:\Temp\SyncfusionEssentialStudio_12.1.0.43.exe" /uninstall true



_Essential Studio version 13.2 and later:_



“Setup file path\SyncfusionEssentialStudio_(version).exe” /uninstall silent 

Example: “D:\Temp\SyncfusionEssentialStudio_13.2.0.30.exe" /uninstall silent



8. Setup is uninstalled.
> 
![http://help.syncfusion.com/ug/common/ImagesExt/image9_1.png](Command-Line-Uninstallation_images/Command-Line-Uninstallation_img1.png)
{:.image }
_Note: x.x.x.x need to be replaced with the Essential studio version installed in your machine and the product unlock key needs to be replaced with the unlock key for that version._

