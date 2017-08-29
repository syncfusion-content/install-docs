---
layout: post
title: Essential Studio Installer for Individual Platform | common | Syncfusion
description: essential studio installer for individual platforms
platform: common
control: Essential Studio
documentation: ug
---

# Essential Studio Installer for Individual Platforms

## Overview

Separate platform setups are provided from version 11.1.0.21. There are 20 platforms. You can download the latest version platforms Installer [here](https://www.syncfusion.com/downloads/latest-version) .

* ASP.NET (from 12.2.0.36 and later)
* ASP.NET (Classic)
* ASP.NET Core (from 14.3.0.49)
* ASP.NET MVC (from 12.1.0.43 and later)
* ASP.NET MVC (Classic) 
* JavaScript (from 11.2.0.63 and later)
* JSP (from v14.4.0.15)
* LightSwitch HTML (from 12.4.0.24 and later)
* PHP (from 14.3.0.49)
* Universal Windows Platform (from 13.2.0.34 and later)
* Windows Forms
* WinRT (only for Microsoft Windows 8 and later)
* WPF
* Xamarin
* FileFormats
* Android
* iOS 
* Silverlight 
* Windows Phone (only for Windows Phone SDK 8 and later )
* LightSwitch Silverlight (from 11.3.0.30 and later)
* Sample Creator (from 12.1.0.43 and later)

Essential Studio Sample Creator is provided from version 12.1.0.43. For more information refer to [Sample Creator](http://www.syncfusion.com/kb/2350).

The LightSwitch platform has been marked as LightSwitch Silverlight from version 12.3.0.26 and later.

WinRT and Windows Phone platform setup can be installed in Windows version 8 and later. Universal Windows Platform setup can be installed in Windows 10.

We are providing the iOS packages as a .pkg file which is developed in MAC OS. It contains Framework library of the controls and samples.

Essential Studio for ASP.NET MVC has been marked as "Classic" from version 12.1.0.43.

Essential Studio for ASP.NET has been marked as "Classic" from version 12.2.0.36.

## Step-by-Step Installation

The following procedure illustrates how to install Essential Studio. 

1. Double-click the Syncfusion Essential Studio Platform Setup file. The Setup Wizard opens and extracts the package automatically.

   ![](ES-Installer-for-Individual-Platform_images/Step-by-Step-Installation_img1.png)

   N> The Setup wizard extracts the syncfusionessentialstudio_(version).exe dialog, displaying the unzip operation of the package.

2. From the 2016 Vol 3 release(v14.3.0.49), you are provided with two options to unlock the Syncfusion setup.

   
   **Install with login ID**
   
   
   **Install with product key**
   
   N> While installing the Syncfusion setup, by default Login Validation screen will be displayed. You can provide the registered Syncfusion email ID and password for unlocking the Syncfusion setup and your license will be configured. For unlocking the setup with License Key, you can select the **Install with product key** in the Installer and you will be prompt to enter the license key.
   
   
   **Install with login ID**

   ![](ES-Installer-for-Individual-Platform_images/Step-by-Step-Installation_img2.png)

   N> You should enter your Syncfusion Direct-Trac login credentials. If you don't have Syncfusion Direct-Trac login credentials, then you can click on Sign Up to a create new account. Else if you forgot your password, click on Reset Password to create new password. Here Email address and Password is validated and the Platform Selection window opens.


   **Install with product key**

   ![](ES-Installer-for-Individual-Platform_images/Step-by-Step-Installation_img3.png)

   N> The Unlock key is validated and the Path Selection window opens.


3. After reading the terms by clicking the **License Terms and Conditions** link, check the I accept the terms and conditions check box.


4. Click Next. Select the Installation, Samples Folder and Advanced Options screen opens. 


    ![](ES-Installer-for-Individual-Platform_images/Step-by-Step-Installation_img4.png)


   N> To install in the displayed default location, click Install. You can also browse and choose a location by clicking Browse. When you have already installed any other same version‘s setup, you cannot change the install and samples path.

   * Select the Install Syncfusion samples check box to install Syncfusion samples, or leave the check box clear, when you do not want to install Syncfusion samples.
   * Select the Register Syncfusion assemblies in GAC check box to install the latest Syncfusion assemblies in GAC, or clear this check box when you do not want to install the latest assemblies in GAC.
   * Select the Uninstall previously installed Syncfusion assemblies from GAC check box to uninstall the previously installed Syncfusion assemblies from GAC, or clear this check box to maintain the previously installed assemblies.
   * Select the Configure Syncfusion controls in Visual Studio Toolbox (if assemblies installed) check box to configure the Syncfusion controls in the Visual Studio toolbox, or clear this check box when you do not want to configure the Syncfusion controls in the Visual Studio toolbox during setup installation. Note that you must also select the Register Syncfusion assemblies in GAC check box when you select this check box.


5.  Click Install.


    ![](ES-Installer-for-Individual-Platform_images/Step-by-Step-Installation_img5.png)

     N> The Completed screen is displayed once the package is installed.

    ![](ES-Installer-for-Individual-Platform_images/Step-by-Step-Installation_img6.png)


6. Select the Run Syncfusion Control Panel check box to launch the Syncfusion Control Panel after installing.


7. Click Finish. Essential Studio is installed in your system and the Syncfusion Essential Studio [Syncfusion Control Panel](http://help.syncfusion.com/common/essential-studio/utilities#dashboard ) is launched automatically.


## Command Line 

The Syncfusion Essential Studio Platform Installer supports installing the setup through Command Line Install and Uninstall. The following sections illustrate this ability. 

### Command Line Installation

Follow the steps below to install through Command Line in Silent mode.

1. Double-click the Syncfusion Essential Studio platform Setup file. The Setup Wizard opens and extracts the package automatically.
2. The SyncfusionEssentialStudio(platform)_(version).exe file is extracted into the Temp folder.
3. Run %temp%. The Temp folder will open. The SyncfusionEssentialStudio(platform)_(version).exe file is available in one of the folders.
4. Copy the SyncfusionEssentialStudio_(version).exe file in local drive. Example: D:\temp
5. Cancel the Wizard.
6. Open the Command Prompt in administrator mode and pass the following arguments for corresponding version:

   Essential Studio version from 11.1 to 13.1:

   “Setup file path\SyncfusionEssentialStudio(platform)_(version).exe” Install /PIDKEY:“(product unlock key)” [/log “{Log file path}”] [/InstallPath: {Location to install}] 

   N> [..] – Arguments inside the square brackets are optional.

   Example: “D:\Temp\SyncfusionEssentialStudio(platform)_12.1.0.43.exe” Install /PIDKEY:“product unlock key” /log “C:\Temp\EssentialStudio_Platform.log” /InstallPath:C:\Syncfusion\x.x.x.x 

   Essential Studio version 13.2 and later:

   “Setup file path\SyncfusionEssentialStudio(platform)_(version).exe” /Install silent /PIDKEY:“(product unlock key)” [/log “{Log file path}”] [/InstallPath:{Location to install}] [/InstallSamples:{true/false}] [/InstallAssemblies:{true/false}] [/UninstallExistAssemblies:{true/false}] [/InstallToolbox:{true/false}]


   N> [..] – Arguments inside the square brackets are optional.

   Example: “D:\Temp\SyncfusionEssentialStudio(platform)_13.2.0.30.exe” /Install silent /PIDKEY:“product unlock key” /log “C:\Temp\EssentialStudio_Platform.log” /InstallPath:C:\Syncfusion\x.x.x.x /InstallSamples:true /InstallAssemblies:true /UninstallExistAssemblies:true /InstallToolbox:true


   N> We have provided Advanced Options in silent installation from 13.2.0.x.

	
7. Setup is installed.

   N> x.x.x.x needs to be replaced with the Essential Studio version installed in your machine and the Product Unlock Key needs to be replaced with the Unlock Key for that version. The platform should be replaced with ASP.NET, ASP.NET MVC, ASP.NET MVC Classic, Silverlight, Windows Forms, Windows Phone, WinRT, WPF, JavaScript, or LightSwitch.
   

### Command Line Uninstallation

Syncfusion Essential Studio supports uninstalling the setup through Command Line in Silent mode. The following steps illustrate this. 

1. When you do not have the extracted setup (SyncfusionEssentialStudio(platform)_(version).exe) then follow the steps from 2 to 7.
2. Double-click the Syncfusion Essential Studio platform Setup file. The Setup Wizard opens and extracts the package automatically.
3. The SyncfusionEssentialStudio(platform)_(version).exe file is extracted into the Temp folder.
4. Run %temp%. The Temp folder will open. The SyncfusionEssentialStudio(platform)_(version).exe file is available in one of the folders.
5. Copy the SyncfusionEssentialStudio(platform)_(version).exe file in local drive. Example: D:\temp
6. Cancel the Wizard.
7. Open the Command Prompt in administrator mode and pass the following arguments for corresponding version: 

   Essential Studio version from 11.1 to 13.1:

   “Setup file path\SyncfusionEssentialStudio(platform)_(version).exe” /uninstall true 

   Example: “D:\Temp\SyncfusionEssentialStudio(platform)_12.1.0.43.exe" /uninstall true
    
   Essential Studio version 13.2 and later:

   “Setup file path\SyncfusionEssentialStudio(platform)_(version).exe” /uninstall silent 

   Example: “D:\Temp\SyncfusionEssentialStudio(platform)_13.2.0.30.exe" /uninstall silent


8. Setup is uninstalled.

   N> x.x.x.x needs to be replaced with the Essential Studio version installed in your machine and the Product Unlock Key needs to be replaced with the unlock key for that version. Platform should be replaced with ASP.NET, ASP.NET MVC, ASP.NET MVC Classic, Silverlight, Windows Forms, Windows Phone, WinRT, WPF, JavaScript, or LightSwitch.

