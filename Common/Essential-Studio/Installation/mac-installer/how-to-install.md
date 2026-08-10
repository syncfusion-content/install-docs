---
layout: post
title: Installing Syncfusion Essential Studio Mac Installer
description: Learn how to install the Syncfusion Essential Studio Mac installer after downloading it from the Syncfusion website.
platform: common
control: Essential Studio
documentation: ug
---

# Installation Steps for Syncfusion Mac Installer

## Overview

Syncfusion<sup style="font-size:70%">&reg;</sup> provides the Mac installer for the following Essential Studio<sup style="font-size:70%">&reg;</sup> products.

* ASP.NET Core
* Blazor
* JavaScript
* WebKit HTML Converter
* Xamarin (retired)
* .NET MAUI
* Document SDK
* PDF Viewer SDK
* Spreadsheet Editor SDK
* DOCX Editor SDK
* Scheduler SDK
* Gantt SDK
* Rich Text Editor SDK
* Grid SDK
* Chart SDK
* Diagram SDK
* File Manager SDK


## Steps to resolve the warning message in Catalina OS or later

   While running Essential Studio<sup style="font-size:70%">&reg;</sup> Mac installers on Catalina macOS or later, the alert below will be displayed.

   ![Alert](images/Mac_Catalina_MacOS_Alert1.png)
     
   If you receive this alert, follow the below steps for the easiest solution.   

   1. Right-click the downloaded DMG file.
   2. Select the "Open With" option and choose "DiskImageMounter (Default)". The following pop-up appears.

		![Pop-up](images/Mac_Catalina_MacOS_Alert2.png)

   3. When you click "Open", the installer window will be opened.

## Step-by-Step Installation

The steps below show how to install the Essential Studio<sup style="font-size:70%">&reg;</sup> Mac installer.

1. Locate the downloaded DMG file and open it by double-clicking on it.

   ![DMG file in Finder](images/Mac_Installer1.png)
   

2. This action will automatically mount the disk image and create a virtual drive on your desktop or in the Finder sidebar.

   ![Mounted disk image](images/Mac_Installer2.png) 
   

3. Copy the mounted disk file.

   ![Copy the mounted disk file](images/Mac_Installer3.png)
   
   
4. And paste it in the "Applications" folder shortcut.

   ![Paste in Applications folder](images/Mac_Installer4.png)
   
   N> The unlock key is not required to install the Mac installer. The Syncfusion<sup style="font-size:70%">&reg;</sup> Mac installer can be used for development purposes without registering the unlock key.


5. Now you can open the folder to explore the Syncfusion<sup style="font-size:70%">&reg;</sup> Essential Studio<sup style="font-size:70%">&reg;</sup> Mac installer.

   ![Installed Syncfusion folder](images/Mac_Installer5.png)
   

6. To remove the DMG file, right-click on the virtual drive on your desktop or in the Finder sidebar and select "Eject". Also, delete the folder from the Applications.

   ![Eject virtual drive](images/Mac_Installer6.png)

## License key registration in samples

After installation, the license key is required to register the demo source that is included in the Mac installer. To learn about the steps for license registration for each Mac installer, please refer to the following table.

<table>
<tr>
<th>Mac Installer</th>
<th>Registration steps</th>
</tr>
<tr>
<td>ASP.NET Core (Essential<sup style="font-size:70%">&reg;</sup> JS 2)</td>
<td>Register the license key in the <code>Configure</code> method of {{ '[Startup.cs](https://help.syncfusion.com/common/essential-studio/licensing/how-to-register-in-an-application#aspnet-core)' | markdownify }}.</td>
</tr>
<tr>
<td>Blazor</td>
<td>For server-side applications, register the license key in the <code>Configure</code> method of {{ '[Startup.cs](https://help.syncfusion.com/common/essential-studio/licensing/how-to-register-in-an-application#server-side-application)' | markdownify }}.<br /><br />Register the license key in the {{ '[Program.cs](https://help.syncfusion.com/common/essential-studio/licensing/how-to-register-in-an-application#server-side-application-using-net-60)' | markdownify }} file if you created the Blazor server-side application with Visual Studio 2022 and .NET 6.0.<br /><br />For client-side applications, register the license key in the <code>Main</code> method of {{ '[Program.cs](https://help.syncfusion.com/common/essential-studio/licensing/how-to-register-in-an-application#client-side-application)' | markdownify }}.</td>
</tr>

<tr>
<td>JavaScript (Essential<sup style="font-size:70%">&reg;</sup> JS 2)</td>
<td>Only from 2022 Vol 1 v20.1.0.47, {{ '[license key registration](https://help.syncfusion.com/common/essential-studio/licensing/how-to-register-in-an-application#javascript-essential-js-2)' | markdownify }} is required for Essential<sup style="font-size:70%">&reg;</sup> JavaScript 2 products.</td>
</tr>
<tr>
<td>.NET MAUI</td>
<td>Register the license key in the {{ '[App.xaml.cs](https://help.syncfusion.com/common/essential-studio/licensing/how-to-register-in-an-application#net-maui)' | markdownify }} constructor before <code>InitializeComponent()</code>.</td>
</tr>
<tr>
<td>Xamarin (retired)</td>
<td>For Xamarin.Forms, register the license key in the {{ '[App.xaml.cs](https://help.syncfusion.com/common/essential-studio/licensing/how-to-register-in-an-application#xamarinforms)' | markdownify }} constructor before <code>InitializeComponent()</code>.<br /><br />For Xamarin.Android, register the license key in the <code>OnCreate</code> {{ '[override method](https://help.syncfusion.com/common/essential-studio/licensing/how-to-register-in-an-application#xamarinandroid)' | markdownify }} of your main activity class before initializing any Syncfusion<sup style="font-size:70%">&reg;</sup> control.<br /><br />For Xamarin.iOS, register the license key in the <code>FinishedLaunching</code> override method of {{ '[AppDelegate.cs](https://help.syncfusion.com/common/essential-studio/licensing/how-to-register-in-an-application#xamarinios)' | markdownify }}.</td>
</tr></table>