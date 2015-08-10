---
layout: post
title: Command-Line-Installation
description: command line installation
platform: common
control: Essential Studio
documentation: ug
---

#### Command Line Installation

Follow the given steps to install through Command Line in Silent mode.

1. Double-click the Syncfusion Essential Studio Setup file. The Self-ExtractorWizard opens and extracts the package automatically.
2. The SyncfusionEssentialStudio_(version).exe file is extracted into the Temp folder. 
3. Run %temp%. The Temp folder opens. The SyncfusionEssentialStudio_(version).exe file is available in one of the folders.
4. Copy the SyncfusionEssentialStudio_(version).exe file in local drive. Example: D:\temp
5. Cancel the wizard.
6. Open Command Prompt in administrator mode and pass the following arguments for corresponding version:
  
  _Essential Studio version 13.1 and earlier:_
  “Setup file path\SyncfusionEssentialStudio_(version).exe” Install /PIDKEY:“(product unlock key)” [/log “{Log file path}”] [/InstallPath:{Location to install}] 
  
  _Note: [..] – Arguments inside the square brackets are optional._
   
   Example: “D:\Temp\SyncfusionEssentialStudio_12.1.0.43.exe” Install /PIDKEY:“product unlock key” /log “C:\Temp\EssentialStudio.log” /InstallPath:C:\Syncfusion\x.x.x.x
  
  _Essential Studio version 13.2 and later:_

  “Setup file path\SyncfusionEssentialStudio_(version).exe” /Install silent /PIDKEY:“(product unlock key)” [/log “{Log file path}”] [/InstallPath:{Location to install}] [/InstallSamples:{true/false}] [/InstallAssemblies:{true/false}] [/UninstallExistAssemblies:{true/false}] [/InstallToolbox:{true/false}]
  
  _Note: [..] – Arguments inside the square brackets are optional._
   
   Example: “D:\Temp\SyncfusionEssentialStudio_13.2.0.30.exe” /Install silent /PIDKEY:“product unlock key” /log “C:\Temp\EssentialStudio.log” /InstallPath:C:\Syncfusion\x.x.x.x /InstallSamples:true /InstallAssemblies:true /UninstallExistAssemblies:true /InstallToolbox:true
  
  _Note: We have provided Advanced Options in silent installation from Syncfusion Version 13.2.0.x.._



7. Setup is installed.
   
   _Note: x.x.x.x needs to be replaced with the Essential Studio version installed on your machine, and product unlock key needs to be replaced with the Unlock Key for that version._

