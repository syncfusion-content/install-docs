---
layout: post
title: Command-Line-Installation
description: command line installation
platform: common
control: Essential Studio
documentation: ug
---

## Command Line Installation

Follow the given steps to install through Command Line in Silent mode.

1. Double-click the Syncfusion Big Data ClusterManagerSetup file. The Self-ExtractorWizard opens and extracts the package automatically.
2. The SyncfusionBigDataClusterManager_(version).exe file is extracted into the Temp folder. 
3. Run %temp%. The Temp folder opens. The SyncfusionBigDataClusterManager_(version).exe file is available in one of the folders.
4. Copy the SyncfusionBigDataClusterManager_(version).exe file in local drive. Example: D:\temp
5. Cancel the wizard.
6. Open Command Prompt in the Administrator mode and pass the following arguments:

   “Setup file path\SyncfusionBigDataClusterManager_(version).exe” /log “{Log file path}” /Install silent /InstallPath:{Location to install}

   Example: “D:\Temp\SyncfusionBigDataClusterManager_2.1.0.70.exe” /log “C:\Temp\BigDataClusterManager.log” /Install silent /InstallPath:C:\Syncfusion\x.x.x.x

7. Setup is installed.

   > Note: x.x.x.x needs to be replaced with the Big Data version installed on your machine.