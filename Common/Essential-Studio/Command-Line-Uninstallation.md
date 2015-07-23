---
layout: post
title: Command-Line-Uninstallation
description: command line uninstallation
platform: js
control: Control Name undefined
documentation: ug
---

### Command Line Uninstallation

Syncfusion WebKit Installer supports uninstalling the setup through Command Line inSilent mode. The following steps help you uninstall the setup. 

1. When you do not have the extracted setup (syncfusionessentialwebkit _(version).exe) then follow the steps from 2 to 7.
2. Double-click the Syncfusion Essential Studio Setup file. The Self-ExtractorWizard opens and extracts the package automatically.
3. The syncfusionessentialwebkit _(version).exe file gets extracted into the Temp folder.
4. Run %temp%. The Temp folder opens. The syncfusionessentialwebkit _(version).exe file is available in one of the folders.
5. Copy the syncfusionessentialwebkit _(version).exe file in local drive. Example: D:\temp
6. Cancel the wizard.
7. Open the Command Prompt in administrator mode and pass the following arguments: 

“Setup file path\ syncfusionessentialwebkit _(version).exe” /uninstall silent 

Example: “D:\Temp\ syncfusionessentialwebkit _13.2.0.30.exe" /uninstall silent

8. Setup is uninstalled.
> 
![http://help.syncfusion.com/ug/common/ImagesExt/image9_1.png](Command-Line-Uninstallation_images/Command-Line-Uninstallation_img1.png)
{:.image }
_Note:_ 

> 1. _x.x.x.x need to be replaced with the Webkit version installed in your machine._
> 2. _Above steps applicable from the version 13.2.0.x._



