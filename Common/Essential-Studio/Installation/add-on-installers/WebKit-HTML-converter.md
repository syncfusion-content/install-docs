---
layout: post
title: Downloading Syncfusion Essential Studio WebKit HTML converter Add-on installer - Syncfusion
description: Learn here about how to download the Syncfusion Essential Studio WebKit HTML converter Add-on installer from our Syncfusion website with license.
platform: common
control: Essential Studio
documentation: ug

---


# WebKit HTML converter


## Downloading Syncfusion<sup style="font-size:70%">&reg;</sup> Essential Studio<sup style="font-size:70%">&reg;</sup> WebKit HTML converter Add-on installer

1. Essential Studio<sup style="font-size:70%">&reg;</sup> WebKit HTML converter Add On installer can be downloaded from your account’s [download](https://help.syncfusion.com/common/essential-studio/download) section. 

2. Syncfusion<sup style="font-size:70%">&reg;</sup> WebKit HTML converter Add On installer can be downloaded based on your license. Refer [this](https://www.syncfusion.com/kb/10442/who-can-access-source-license) KB for the WebKit HTML converter license.

3. WebKit HTML converter Add On installer can be downloaded from the setup downloads page by clicking the **More Download Option** button.

   ![Download Page](WebKit-HTML-converter-images/WebKitAddOn_Download.png)



## Installing Syncfusion<sup style="font-size:70%">&reg;</sup> Essential Studio<sup style="font-size:70%">&reg;</sup> WebKit HTML converter Add-on installer

Syncfusion<sup style="font-size:70%">&reg;</sup> introduces the HTML converter in Essential Studio<sup style="font-size:70%">&reg;</sup> 13.1.0.21, which supports HTML to PDF conversion by using the advanced Qt WebKit rendering engine. This converter can easily be integrated into any.NET application such as Windows Forms, WPF, ASP.NET, ASP.NET MVC, and ASP.NET Core to convert URLs, HTML strings, SVG, and MHTML to PDF, as well as HTML to MHTML, HTML to SVG, and HTML to image.

## Step-by-Step Installation

The steps for installing the HTML Converter installer are as follows.

1. Run the Syncfusion<sup style="font-size:70%">&reg;</sup> HTML Converter Installer by double-clicking it. The installer Wizard automatically opens and extracts the package.

   ![Installer Extraction Wizard](WebKit-HTML-converter-images/Step-by-Step-Installation_img1.png)

   

   N> The installer extracts the syncfusionessentialhtmlconverter_(version).exe dialogue, which displays the package's unzip operation.

2. After reading the License terms and Privacy Policy, enter the [Essential Studio<sup style="font-size:70%">&reg;</sup> Unlock Key](https://www.syncfusion.com/kb/2326/how-to-generate-syncfusion-setup-unlock-key-from-syncfusion-support-account) in the corresponding text box and check the **I agree to the License Terms and Privacy Policy** check box.

   ![License Agreement](WebKit-HTML-converter-images/Step-by-Step-Installation_img5.png)

3. Click the Next button. The installation location screen will appear.

   ![Installation location](WebKit-HTML-converter-images/Step-by-Step-Installation_img6.png)

   N> By clicking **Browse**, you can also browse and select a location.

4. Click Install, To install in the displayed default location, .

   ![Installation progress](WebKit-HTML-converter-images/Step-by-Step-Installation_img8.png)
   
   N> The Completed screen will be displayed once the  HTML converter is installed.
   
   ![Installation Complete](WebKit-HTML-converter-images/Step-by-Step-Installation_img10.png)

5. Click Finish.  HTML converter is installed in your machine.

N> Starting with v20.1.0.x, if you reference Syncfusion<sup style="font-size:70%">&reg;</sup> HTML converter assemblies from trial setup or from the NuGet feed, include a license key in your projects. Refer to the [link](https://help.syncfusion.com/file-formats/licensing/overview) to learn about generating and registering Syncfusion<sup style="font-size:70%">&reg;</sup> license key in your application to use the components without trail message.

## Command Line 

Command Line Install and Uninstall are supported by the Syncfusion<sup style="font-size:70%">&reg;</sup>  HTML converter Installer. The following section demonstrate this ability.

### Command Line Installation

Follow the given steps to install through Command Line in Silent mode.

1. Double-click the Syncfusion<sup style="font-size:70%">&reg;</sup>  HTML converter Installer to launch it. The Self-Extractor Wizard automatically opens and extracts the package.
2. The syncfusionessentialhtmlconverter_(version).exe file is extracted into the Temp folder. 
3. Run %temp%. The Temp folder opens. The syncfusionessentialhtmlconverter_(version).exe file is available in one of the folders.
4. Copy the syncfusionessentialhtmlconverter_(version).exe file in local drive. Example: D:\temp
5. Cancel the wizard.
6. Open Command Prompt in administrator mode and pass the following arguments:

   **Arguments:** “Installer file path\syncfusionessentialhtmlconverter_(version).exe” /Install silent [/log “{Log file path}”] [/InstallPath:{Location to install}]

   N> [..] – Arguments inside the square brackets are optional.

   **Example:** “D:\Temp\syncfusionessentialhtmlconverter13.2.0.30.exe” /Install silent /log “C:\Temp\EssentialWebkit.log” /InstallPath:C:\Syncfusion\x.x.x.x 

7.  HTML converter is installed.
    
	N> * x.x.x.x needs to be replaced with the HTML Converter version installed on your machine.* Above steps applicable from the version 13.2.0.x.
   
### Command Line Uninstallation

Uninstalling Syncfusion<sup style="font-size:70%">&reg;</sup>  HTML converter Installer via Command Line in Silent mode is possible. The steps below will assist you in uninstalling the  HTML converter.

1. When you do not have the extracted installer (syncfusionessentialhtmlconverter_(version).exe) then follow the steps from 2 to 7.
2. Double-click the Syncfusion<sup style="font-size:70%">&reg;</sup> Essential Studio<sup style="font-size:70%">&reg;</sup> installer. The Self-ExtractorWizard opens and extracts the package automatically.
3. The syncfusionessentialhtmlconverter_(version).exe file gets extracted into the Temp folder.
4. Run %temp%. The Temp folder opens. The syncfusionessentialhtmlconverter_(version).exe file is available in one of the folders.
5. Copy the syncfusionessentialhtmlconverter_(version).exe file in local drive. Example: D:\temp
6. Cancel the wizard.
7. Open the Command Prompt in administrator mode and pass the following arguments: 

   **Arguments:** “Installer file path\ syncfusionessentialhtmlconverter_(version).exe” /uninstall silent 

    **Example:** “D:\Temp\ syncfusionessentialhtmlconverter_13.2.0.30.exe" /uninstall silent

8.  HTML Converter is uninstalled.
    
	N> * x.x.x.x need to be replaced with the HTML Converter version installed in your machine.* Above steps applicable from the version 13.2.0.x.		
