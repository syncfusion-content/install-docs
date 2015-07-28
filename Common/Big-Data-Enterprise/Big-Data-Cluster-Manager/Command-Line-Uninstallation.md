---
layout: post
title: Command-Line-Uninstallation
description: command line uninstallation
platform: js
control: Essential Studio
documentation: ug
---

#### Command Line Uninstallation

Syncfusion Big Data ClusterManager supports uninstalling the setup through Command Line in Silent mode. The following steps help you uninstall the setup. 

1. When you do not have the extracted setup (SyncfusionBigDataClusterManager_(version).exe) follow the steps from 2 to 7.
1.  Double-click the Syncfusion Big Data Cluster Manager Setup file. The Self-ExtractorWizard opens and extracts the package automatically.
2.  The SyncfusionBigDataClusterManager_(version).exe file gets extracted into the Temp folder.
3. Run %temp%. The Temp folder opens. The SyncfusionBigDataClusterManager_(version).exe file is available in one of the folders.
4. Copy the SyncfusionBigDataClusterManager_(version).exe file in the local drive. Example: D:\temp
5. Cancel the wizard.
6. Open the Command Prompt in the Administrator mode and pass the following arguments: 

         “Setup file path\SyncfusionBigDataClusterManager_(version).exe” /uninstall silent

        Example: “D:\Temp\SyncfusionBigDataClusterManager_2.1.0.70.exe" /uninstall silent

7. Setup is uninstalled.
