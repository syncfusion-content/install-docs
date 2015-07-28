---
layout: post
title: Command-Line-Uninstallation
description: command line uninstallation
platform: js
control: Essential Studio
documentation: ug
---

#### Command Line Uninstallation

Syncfusion Big Data supports uninstalling the setup through Command Line in Silent mode. The following steps help you uninstall the setup. 

1. When you do not have the extracted setup (SyncfusionBigData_(version).exe), follow the steps from 2 to 7.
2. Double-click the Syncfusion Big Data Setup file. The Self-ExtractorWizard opens and extracts the package automatically.
3. The SyncfusionBigData_(version).exe file gets extracted into the Temp folder.
4. Run %temp%. The Temp folder opens. The SyncfusionBigData_(version).exe file is available in one of the folders.
5. Copy the SyncfusionBigData_(version).exe file in local drive. Example: D:\temp
6. Cancel the wizard.
7. Open the Command Prompt in Administrator mode and pass the following arguments: 

   “Setup file path\SyncfusionBigData_(version).exe” /uninstall silent

   Example: “D:\Temp\SyncfusionBigData_2.1.0.70.exe" /uninstall silent

8. Setup is uninstalled.
