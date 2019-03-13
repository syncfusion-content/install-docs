---
layout: post
title: Install Essential Studio Offline | common | Syncfusion
description: information about syncfusion offline installer and steps for installation
platform: common
control: Essential Studio
documentation: ug
---

# Essential Studio Offline Installer


## Overview

Syncfusion started providing the Offline Essential Studio setup only for Licensed customers from 2018 Volume 2 release. The Essential Studio Enterprise Edition Installer includes the following platforms. You can download the latest version Essential Studio Installer [here](https://www.syncfusion.com/downloads/latest-version) . 

I> You can install the Essential Studio Offline Installer using Login and Unlock key.

**Web (Essential JS 2)**

* ASP.NET MVC
* ASP.NET Core
* JavaScript

**Mobile**

* Xamarin

**Desktop**

* Windows Forms
* WPF
* Universal Windows Platform

**Web (Essential JS 1)**

* ASP.NET Web Forms
* ASP.NET MVC
* ASP.NET Core
* JavaScript
* PHP
* JSP
 
 
The following procedure illustrates how to install Essential Studio Offline Installer setup. 

1.  Double-click the Syncfusion Essential Studio Offline Installer setup file. The Setup Wizard opens and extracts the package automatically.

    ![Setup extraction wizard](Offline-ES/Step-by-Step-Installation_img1.png)

    
    N> The Setup wizard extracts the syncfusionessentialstudiowebinstaller_{version}.exe dialog, displaying the unzip operation of the package.
    
2. Welcome wizard of the Syncfusion Offline Installer will be displayed. Click Proceed.

   ![Welcome wizard](Offline-ES/Step-by-Step-Installation_img2.png)

  
3.  Platform Selection wizard will be displayed. Here you can select the required platforms to be installed. Click Next.

    ![Platform Selection wizard](Offline-ES/Step-by-Step-Installation_img3.png)
	
	I> If the required software of the selected platform was not already installed, **Additional Software Required** alert will be displayed.
	
	![Additional Software Required alert](Offline-ES/Step-by-Step-Installation_img4.png)
	
	N> You can check the Estimated size of the Download and Installation by clicking the **Download Size and Installation Size** link.
	
	![ES download and installation size](Offline-ES/Step-by-Step-Installation_img5.png)

4.  Configuration wizard will be displayed. Here you can change the Install and samples location. Also, you can change the Additional settings for the individual platform. To install using the default configuration, click Next.

    ![Configuration wizard](Offline-ES/Step-by-Step-Installation_img6.png)
	
   
    N> From the 2018 Volume 2 release, Syncfusion has changed the install and samples location 
	   **Default Install location:** {ProgramFilesFolder}\Syncfusion\{Platform}\{version}
	   **Default Samples location:** C:\Users\Public\Documents\Syncfusion\{platform}\{version}
	   However, you can change the locations by clicking browse button.

	
	
    * Select the **Install Demos** check box to install Syncfusion samples, or leave the check box clear, when you do not want to install Syncfusion samples.
    * Select the **Register Syncfusion Assemblies in GAC** check box to install the latest Syncfusion assemblies in GAC, or clear this check box when you do not want to install the latest assemblies in GAC.
    * Select the **Configure Syncfusion controls in Visual Studio** check box to configure the Syncfusion controls in the Visual Studio toolbox, or clear this check box when you do not want to configure the Syncfusion controls in the Visual Studio toolbox during setup installation. Note that you must also select the Register Syncfusion assemblies in GAC check box when you select this check box.
    * Select the **Configure Syncfusion Extensions in Visual Studio** checkbox to configure the Syncfusion Extensions in Visual Studio or clear this check box when you do not want to configure the Syncfusion Extensions in Visual Studio.


5.  After reading the License Terms and Conditions, check the **I agree to the License Terms and Privacy Policy** check box. Click Next.

6. Login wizard will be displayed. You should enter your Syncfusion Direct-Trac login credentials. If you don't have Syncfusion Direct-Trac login credentials, then you can click on **Create an Account**. Else if you forgot your password, click on **Forgot Password** to create new password. Click Install.

    ![Login wizard](Offline-ES/Step-by-Step-Installation_img7.png)

7. Download and Installation progress will be displayed.

    ![Download and Installation progress](Offline-ES/Step-by-Step-Installation_img8.PNG)

8. Once the Installation is complete, **Installation Summary** wizard will be displayed. Here you can check the list of platforms which are installed successfully and failed. Click Finish to exit the Installation Summary wizard. 

    ![ES Installation Summary](Offline-ES/Step-by-Step-Installation_img9.png)
	
	* Click **Getting Started** link to goto the UG documentation of the corresponding platform.
	
	* Click **Launch Control Panel** to open the Syncfusion Control Panel.

