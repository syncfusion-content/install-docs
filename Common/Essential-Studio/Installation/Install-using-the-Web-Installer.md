---
layout: post
title: Install and deploy – Using Web Installer | Syncfusion
description: Learn more some information about installation and deployment of Syncfusion Essential studio using Web Installer.
platform: common
control: Essential Studio
documentation: ug
---

# Install using the Web installer

You can refer to the [Download](https://help.syncfusion.com/common/essential-studio/download) section to learn how to get the trial or licensed installer

### Overview

Syncfusion provides Web Installer for Essential Studio products. This installer alleviates the burden of downloading a larger installer. You can simply download and run the online installer, which will be smaller in size and will download and install the Essential Studio products you have chosen. You can get the most recent version of Essential Studio Web Installer [here](https://www.syncfusion.com/downloads/latest-version).

Syncfusion Web Installer also allows both installation and uninstallation of the products for that specific version.
	
**Web**

* ASP.NET MVC
* ASP.NET Core
* JavaScript
* Blazor

**Mobile**

* Xamarin
* Flutter

**Desktop**

* Windows Forms
* WPF
* Universal Windows Platform
* WinUI(Preview)

**FileFormats**

* Read and Write Excel, Word, PDF and PowerPoint files

**Web (Essential JS 1)**

* ASP.NET Web Forms
* ASP.NET MVC
* ASP.NET Core
* JavaScript
* PHP
* JSP

N> Universal Windows Platform will be installed in Windows 8.1 and later.  

 
## Installation

The steps below show how to install Essential Studio Product Web installer.

1.  Open the Syncfusion Essential Studio Web Installer file from downloaded location by double-clicking it. The Installer Wizard automatically opens and extracts the package.

    ![Installer Extraction Wizard](WebInstaller/Step-by-Step-Installation_img1.png)

    
    N> The installer wizard extracts the syncfusionessential{platform}webinstaller_{version}.exe dialog, displaying the unzip operation of the package.
    
2.  The Syncfusion Web Installer’s welcome wizard will be displayed. Click the Next button

    ![Welcome wizard](WebInstaller/Step-by-Step-Installation_img2.png)

  
3.  The Platform Selection Wizard will appear. From the **Available** tab, select the products to be installed. Select the **Install All** checkbox to install all products.
    
	<em>**Available**</em>
	
	![Platform Selection wizard Available](WebInstaller/Step-by-Step-Installation_img3.png)
	
	If you have multiple products installed in the same version, they will be listed under the **Installed** tab. You can also select which products to uninstall from the same version. Click the Next button
	
	<em>**Installed**</em>
	
	![Platform Selection wizard Installed](WebInstaller/Step-by-Step-Installation_img3.png)
	
	I> If the required software of the selected platform was not already installed, **Additional Software Required** alert will be displayed. However, you can continue the installation and install the required software later.
	
	<em>**Required Software**</em>
	
	![Additional Software Alert](WebInstaller/Step-by-Step-Installation_img5.png)
		
4.  If previous version(s) for the selected products are installed, the Uninstall previous version wizard will be displayed. You can see the list of previously installed versions for the products you’ve chosen here. To remove all versions, check the **Uninstall All** checkbox. Click the Next button.

    ![Existing Version for install](WebInstaller/Step-by-Step-Installation_img20.png)

	N> From the 2021 Volume 1 release, Syncfusion has provided option to uninstall the previous versions from 18.1 while installing the new version.
	
	
5. 	Pop up screen will be displayed to get the confirmation to uninstall selected previous versions.

    ![Existing Version for install](WebInstaller/Step-by-Step-Installation_img21.png)


6.  The Confirmation Wizard will appear with the list of products to be installed/uninstalled. You can view and modify the list of products that will be installed and uninstalled from this page.

    ![Confirmation for install/uninstall](WebInstaller/Step-by-Step-Installation_img15.png)
	
	N> By clicking the **Download Size and Installation Size** links, you can determine the approximate size of the download and installation.
	
	![Downaload and Installation size install/uninstall](WebInstaller/Step-by-Step-Installation_img16.png)

7.  The Configuration Wizard will appear. You can change the Download, Install, and Demos locations from here. You can also change the Additional settings on a product-by-product basis. Click Next to install with the default settings.

    ![Install and samples location for install](WebInstaller/Step-by-Step-Installation_img8.png)
	
	**Additional settings**

    * Select the Install Demos check box to install Syncfusion samples, or leave the check box unchecked, if you do not want to install Syncfusion samples
    * Select the Configure Syncfusion controls in Visual Studio check box to configure the Syncfusion controls in the Visual Studio toolbox, or clear this check box when you do not want to configure the Syncfusion controls in the Visual Studio toolbox during installation. Note that you must also select the Register Syncfusion assemblies in GAC check box when you select this check box.
    * Select the Configure Syncfusion Extensions controls in Visual Studio checkbox to configure the Syncfusion Extensions in Visual Studio or clear this check box when you do not want to configure the Syncfusion Extensions in Visual Studio.
    * Check the Create Desktop Shortcut checkbox to add a desktop shortcut for Syncfusion Control Panel
    * Check the Create Start Menu Shortcut checkbox to add a shortcut to the start menu for Syncfusion Control Panel


8.  After reading the License Terms and Conditions, check the **I agree to the License Terms and Privacy Policy** check box. Click the Next button.

9.  The login wizard will appear. You must enter your Syncfusion email address and password. If you do not already have a Syncfusion account, you can create one by clicking on **Create an Account**. If you have forgotten your password, click **Forgot Password** to create a new one. Click the Install button.

    ![Login wizard install](WebInstaller/Step-by-Step-Installation_img9.png)
	
	I> The products you have chosen will be installed based on your Syncfusion License (Trial or Licensed).

10. The download and installation\uninstallation progress will be displayed as shown below.

    ![Download and Installation progress install](WebInstaller/Step-by-Step-Installation_img10.png)

11. When the installation is finished, the **Summary** wizard will appear. Here you can see the list of products that have been installed successfully and those that have failed. To close the Summary wizard, click Finish.

    ![Installation Summary](WebInstaller/Step-by-Step-Installation_img11.png)
	
	* To open the Syncfusion Control Panel, click **Launch Control Panel**
	
12. After installation, there will be two Syncfusion control panel entries, as shown below. The Essential Studio entry will manage all Syncfusion products installed in the same version, while the Product entry will only uninstall the specific product setup.

    ![Control Panel](WebInstaller/Step-by-Step-Installation_img19.png)


## Uninstallation

Syncfusion installer can be uninstalled in two ways.

* Uninstall the Syncfusion installer from the Syncfusion web installer
* Uninstall the Syncfusion installer from Windows Control Panel

Follow either one of the options below to uninstall Syncfusion Essential Studio installer.

**Option 1: Uninstall the Syncfusion installer from the Syncfusion web installer**

Syncfusion provides the option to uninstall products of the same version directly from the Web Installer application. Select the products to be uninstalled from the list, and Web Installer will uninstall them one by one.

Open the Syncfusion Essential Studio Online Installer file from downloaded location by double-clicking it. The Installer Wizard automatically opens and extracts the package

![Installer Extraction Wizard uninstall](WebInstaller/Step-by-Step-Installation_img1.png)
	
The Syncfusion Web Installer's welcome wizard will be displayed. Click the Next button
	
![Welcome wizard uninstall](WebInstaller/Step-by-Step-Installation_img2.png)
	
	
**Option 2: Uninstall the Syncfusion installer from Windows Control Panel**  
	
You can uninstall all the installed products by selecting the **Syncfusion Essential Studio {version}** entry (element 1 in the below screenshot) from the Windows control panel, or you can uninstall specific product alone by selecting the **Syncfusion Essential Studio for {Product} {version}** entry (element 2 in the below screenshot) from the Windows control panel.

![Control Panel](WebInstaller/Step-by-Step-Installation_img22.png)
	
N> If the **Syncfusion Essential Studio for {Product} {version}** entry is selected from the Windows control panel, the Syncfusion Essential Studio Product alone will be removed and the below default MSI uninstallation window will be displayed.	

1.  The Platform Selection Wizard will appear. From the **Installed** tab, select the products to be uninstalled. To select all products, check the **Uninstall All** checkbox. Click the Next button.
    
	<em>**Installed**</em>
	
	![Platform Selection wizard Installed](WebInstaller/Step-by-Step-Installation_img4.png)
	
	You can also select the products to be installed from the **Available** tab.Click the Next button.
	
	<em>**Available**</em>
	
	![Platform Selection wizard Available](WebInstaller/Step-by-Step-Installation_img25.png)
	
2.  If any other products selected for installation, Uninstall previous version wizard will be displayed with previous version(s) installed for the selected products. Here you can view the list of installed previous versions for the selected products. Select **Uninstall All** checkbox to select all the versions. Click Next.

	![Existing Version for install](WebInstaller/Step-by-Step-Installation_img26.png)
	
3.	Pop up screen will be displayed to get the confirmation to uninstall selected previous versions.

	![Existing Version for install](WebInstaller/Step-by-Step-Installation_img21.png)	
	
4.  The Confirmation Wizard will appear with the list of products to be installed/uninstalled. Here you can view and modify the list of products that will be installed/uninstalled.

    ![Confirmation for install/uninstall](WebInstaller/Step-by-Step-Installation_img15.png)
	
	N> By clicking the **Download Size and Installation** Size links, you can determine the approximate size of the download and installation
	
5.	The Configuration Wizard will appear. You can change the Download, Install, and Demos locations from here. You can also change the Additional settings on a product-by-product basis. Click Next to install with the default settings.

    ![Install and samples location install/uninstall](WebInstaller/Step-by-Step-Installation_img23.png)
	
6.	After reading the License Terms and Conditions, check the **I agree to the License Terms and Privacy Policy** check box. Click the Next button.

7.	The login wizard will appear. You must enter your Syncfusion email address and password. If you do not already have a Syncfusion account, you can create one by clicking on **Create an Account**. If you have forgotten your password, click **Forgot Password** to create a new one. Click the Install button.

    ![Login wizard install/uninstall](WebInstaller/Step-by-Step-Installation_img9.png)
	
	I> The products you have chosen will be installed based on your Syncfusion License (Trial or Licensed).

8.	The download, installation, and uninstallation progresses will be shown.

    ![Download and Installation progress install/uninstall](WebInstaller/Step-by-Step-Installation_img17.png)

9.	When the installation is finished, the **Summary** wizard will appear. Here you can see the list of products that have been successfully and unsuccessfully installed/uninstalled. To close the Summary wizard, click Finish.

    ![Summary install/uninstall](WebInstaller/Step-by-Step-Installation_img18.png)
	
	* To open the Syncfusion Control Panel, click **Launch Control Panel**.
