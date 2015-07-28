---
layout: post
title: Command-Line-Installation
description: command line installation
platform: js
control: Essential Studio
documentation: ug
---

##### Command Line Installation

Follow the given steps to install through Command Line in Silent mode.

1. Double-click the Syncfusion WebKit Installer Setup file. The Self-ExtractorWizard opens and extracts the package automatically.
2. The syncfusionessentialwebkit _(version).exe file is extracted into the Temp folder. 
3. Run %temp%. The Temp folder opens. The syncfusionessentialwebkit _(version).exe file is available in one of the folders.
4. Copy the syncfusionessentialwebkit _(version).exe file in local drive. Example: D:\temp
5. Cancel the wizard.
6. Open Command Prompt in administrator mode and pass the following arguments:

“Setup file path\syncfusionessentialwebkit _(version).exe” /Install silent [/log “{Log file path}”] [/InstallPath:{Location to install}]

> ![http://help.syncfusion.com/ug/common/ImagesExt/image9_1.png](Command-Line-Installation_images/Command-Line-Installation_img1.png)
{:.image }
_Note: [..] – Arguments inside the square brackets are optional._





Example: “D:\Temp\syncfusionessentialwebkit _13.2.0.30.exe” /Install silent /log “C:\Temp\EssentialWebkit.log” /InstallPath:C:\Syncfusion\x.x.x.x 

7. Setup is installed.
> 
![http://help.syncfusion.com/ug/common/ImagesExt/image9_1.png](Command-Line-Installation_images/Command-Line-Installation_img2.png)
{:.image }
_Note:_ 

> 1. _x.x.x.x needs to be replaced with the WebKit version installed on your machine._
> 2. _Above steps applicable from the version 13.2.0.x._
> 


