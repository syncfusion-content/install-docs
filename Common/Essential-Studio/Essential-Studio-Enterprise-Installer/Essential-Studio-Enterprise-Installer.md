---
layout: post
title: Essential-Studio-Enterprise-Installer
description: essential studio enterprise installer
platform: common
control: Essential Studio
documentation: ug
---

# Essential Studio Enterprise Installer


## Overview

The Essential Studio Enterprise Installer includes all of the following platforms. There is also a separate installer for individual platforms. For more information refer to the Platform installer section.

* ASP.NET 
* ASP.NET (Classic)
* ASP.NET MVC 
* ASP.NET MVC (Classic)
* JavaScript
* LightSwitch HTML
* LightSwitch Silverlight 
* Silverlight
* Universal
* Windows Forms
* Windows Phone
* WinRT
* WPF


> Note: WinRT can only be installed from Windows 8.

You are provided with the separate installers for FileFormat, Android and Xamarin platforms. 

Also, you are provided iOS packages as zip file. It contains framework library of the controls and samples. 


## Step-by-Step Installation

The following procedure illustrates how to install Essential Studio setup. 

1.  Double-click the Syncfusion Essential Studio Setup file. The Self-ExtractorWizard opens and extracts the package automatically.
   
    ![](Step-by-Step-Installation_images/Step-by-Step-Installation_img1.png)


    > Note: The WinZip Self-Extractor extracts the syncfusionessentialstudio(version).exe dialog, displaying the unzip operation of the package.

    ![](Step-by-Step-Installation_images/Step-by-Step-Installation_img3.png)

2.  Enter your User Name, Organization, and Unlock Key in the corresponding text boxes provided.

3.  Click Next.

    > Note: The Unlock Key is validated and the License Agreement Screen opens.

    ![](Step-by-Step-Installation_images/Step-by-Step-Installation_img5.png)

4.  After reading the terms, click the I accept the terms and conditions check box.

5.  Click Next. Select the Installation and Samples Folder screen opens.


    ![](Step-by-Step-Installation_images/Step-by-Step-Installation_img6.png)

    > Note: You can also browse and choose a location by clicking Browse. When you have already installed any other version‘s setup, you cannot change the install path.

6.  To install in the displayed default location, click Next.

7.  Select the platforms to be installed.

    ![](Step-by-Step-Installation_images/Step-by-Step-Installation_img8.png)

    > Note: WinRT platforms will install only from Windows 8.

8.  Click Next. The Select Advanced Options screen opens.

    ![](Step-by-Step-Installation_images/Step-by-Step-Installation_img10.png)

    * Select the Install Syncfusion samples check box to install Syncfusion samples, or leave the check box clear, when you do not want to install Syncfusion samples.
    * Select the Register Syncfusion assemblies in GAC check box to install the latest Syncfusion assemblies in GAC, or clear this check box when you do not want to install the latest assemblies in GAC.
    * Select the Uninstall previously installed Syncfusion assemblies from GAC check box to uninstall the previously installed Syncfusion assemblies from GAC, or clear this check box to maintain the previously installed assemblies.
    * Select the Configure Syncfusion controls in Visual Studio Toolbox (if assemblies installed) check box to configure the Syncfusion controls in the Visual Studio toolbox, or clear this check box when you do not want to configure the Syncfusion controls in the Visual Studio toolbox during setup installation. Note that you must also select the Register Syncfusion assemblies in GAC check box when you select this check box.



9.  Click Install.

    ![](Step-by-Step-Installation_images/Step-by-Step-Installation_img11.png)


    > Note: The Completed screen is displayed once the selected platform is installed.



    ![](Step-by-Step-Installation_images/Step-by-Step-Installation_img13.png)

10. Select the Run Dashboard check box to launch the Dashboard after installing.

11. Click Finish. Essential Studio is installed in your system and Syncfusion Essential Studio Dashboard is launched automatically. For more information, refer to Brief Tour of Dashboard.

    > Note: The Completed screen is displayed once the selected platform is installed.

	
## Command Line 

Syncfusion Essential Studio supports installing the setup through Command Line Install and Uninstall. The following sections illustrate these options. 


### Command Line Installation

Follow the given steps to install through Command Line in Silent mode.

1. Double-click the Syncfusion Essential Studio Setup file. The Self-ExtractorWizard opens and extracts the package automatically.
2. The SyncfusionEssentialStudio_(version).exe file is extracted into the Temp folder. 
3. Run %temp%. The Temp folder opens. The SyncfusionEssentialStudio_(version).exe file is available in one of the folders.
4. Copy the SyncfusionEssentialStudio_(version).exe file in local drive. Example: D:\temp
5. Cancel the wizard.
6. Open Command Prompt in administrator mode and pass the following arguments for corresponding version:
   
   _Essential Studio version 13.1 and earlier:_



   “Setup file path\SyncfusionEssentialStudio_(version).exe” Install /PIDKEY:“(product unlock key)” [/log “{Log file path}”] [/InstallPath:{Location to install}] 

    > Note: [..] – Arguments inside the square brackets are optional.
 
    Example: “D:\Temp\SyncfusionEssentialStudio_12.1.0.43.exe” Install /PIDKEY:“product unlock key” /log “C:\Temp\EssentialStudio.log” /InstallPath:C:\Syncfusion\x.x.x.x



    _Essential Studio version 13.2 and later:_



    “Setup file path\SyncfusionEssentialStudio_(version).exe” /Install silent /PIDKEY:“(product unlock key)” [/log “{Log file path}”] [/InstallPath:{Location to install}] [/InstallSamples:{true/false}] [/InstallAssemblies:{true/false}] [/UninstallExistAssemblies:{true/false}] [/InstallToolbox:{true/false}]

    > Note: [..] – Arguments inside the square brackets are optional.



    Example: “D:\Temp\SyncfusionEssentialStudio_13.2.0.30.exe” /Install silent /PIDKEY:“product unlock key” /log “C:\Temp\EssentialStudio.log” /InstallPath:C:\Syncfusion\x.x.x.x /InstallSamples:true /InstallAssemblies:true /UninstallExistAssemblies:true /InstallToolbox:true


    > Note: We have provided Advanced Options in silent installation from Syncfusion Version 13.2.0.x.

7. Setup is installed.

   > Note: x.x.x.x needs to be replaced with the Essential Studio version installed on your machine, and product unlock key needs to be replaced with the Unlock Key for that version.

   
### Command Line Uninstallation

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
   > Note: x.x.x.x need to be replaced with the Essential studio version installed in your machine and the product unlock key needs to be replaced with the unlock key for that version.