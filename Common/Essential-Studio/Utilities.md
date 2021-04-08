---
layout: post
title: Essential Studio Utilities | Common | Syncfusion
description: This section provides information regarding all the Syncfusion Essential Studio utilities and its usage
platform: common
control: Essential Studio
documentation: ug
---

# Syncfusion Utilities


## Syncfusion Control Panel

This section provides details on the structure and composition of the Syncfusion Control Panel. It also elaborates on navigating the Syncfusion Control Panel to access various utilities, add ons and product samples.

<style>
#license {
    font-size: .88em!important;
margin-top: 1.5em;     margin-bottom: 1.5em;
    background-color: #def8ff;
    padding: 10px 17px 14px;
}
</style>

<div id="license">
From the 2018 Volume 2 release, each Essential Studio platform has separate Syncfusion Control Panel. You can launch the Syncfusion Control Panel either from <b>Desktop Shortcut</b> or <b>Start Menu->Syncfusion Control Panel {version}</b>
</div>

![Syncfusion Control Panel](Utilities_images/Dashboard_img1.png)


### Accessing Product Samples

Syncfusion provides lots of online and local samples for better understanding of the controls. You can access them using the following steps. 

1. Open the Syncfusion Control Panel.

   ![Syncfusion Control Panel](Utilities_images/Dashboard_img9.png)

2. Click any of the following to know more about the selected product.

   * **Run Local Demos** - To run the locally installed samples.
   * **Run Online Demos** - To view online samples.
   * **Explore Demos** - To open local installed location.
   * **Explore Source** - To view the source, when you have installed the source add-on.
   * **User Guide** - To view the user guide documentation for the respective products.
   * **API Reference** - To view the online documentation help contents for the respective products.
   * **Release Notes** - To view the “Release Notes” content.
   * **Read Me** - To view the “Read Me” content.
   * **What’s New** - To view the “What’s New” content.

    

### Checking Prerequisites

You need to install a list of prerequisites, for all of the products to work successfully. When some of the software is not installed, the Syncfusion Control Panel displays an alert. Click Additional Software Required, and a Missing Software dialog box opens.

![Syncfusion Control Panel](Utilities_images/Dashboard_img11.png)

### Missing Software 

Missing Software lists the prerequisites for all platforms. A ![Missing Software Alert](Utilities_images/Dashboard_img13.png) <font color="red">Additional Software Required</font>

symbol appears when any recommended software for a platform is not installed in your system.

The **Recheck** option rechecks the prerequisites list and refreshes the currently installed software list.



![Missing Software](Utilities_images/Dashboard_img14.png)	


### Purpose of Recheck button

**Recheck** option in Syncfusion Control Panel is used to update the recently installed software information in your machine. If you have installed any required software for Essential Studio platforms after installing the Syncfusion installer, those software information will not be updated in the Syncfusion Control Panel. In this case, you can just click the Recheck button in Syncfusion Control Panel which will update the recently installed software in your machine. 

![Syncfusion Control Panel](Utilities_images/Dashboard_img15.png)

### Accessing utilities from Syncfusion Control Panel

This section allows you to access the following. 

1. **Add-ons** - This lists the add-on utilities that help you to utilize the additional product services from Syncfusion. 
   
   ![Syncfusion Control Panel](Utilities_images/Add-ons.png)
   
2. [Utilities](https://help.syncfusion.com/common/essential-studio/utilities#dashboard ) - This section displays the utilities that are available for the corresponding product.

   ![Syncfusion Control Panel](Utilities_images/utilities.png)
   
   * [Toolbox Configuration](https://help.syncfusion.com/common/essential-studio/utilities#toolbox-configuration )- This installer allows you to configure Syncfusion controls for various .NET Frameworks in combination with compatible Visual Studio versions.
   * [Assembly Manager](https://help.syncfusion.com/common/essential-studio/utilities#assembly-manager )- This utility allows you to manage installing or uninstalling Syncfusion Essential Studio assemblies in the GAC and in the Assemblies folders.
   * [License Manager](https://help.syncfusion.com/common/essential-studio/utilities#license-manager )- This allows you to manage the license information, such as the validity of license key and products that are licensed with this key.   
   * [Project Migration](https://help.syncfusion.com/common/essential-studio/utilities#project-migration )- This allows to migrate the project references to the given Essential Studio version.
   * [Extension Installer](https://help.syncfusion.com/common/essential-studio/utilities#vsix-installer )- This allows to configure the Syncfusion Visual Studio extensions in Visual Studio.
   

### License Information

You can view your license details in the Syncfusion Control Panel. License information which includes, whether the setup is installed with Licensed or Trial. Syncfusion Trial expires in 30 days.

* Messages- This section allows you to view the License information, like whether the user is Licensed or Trial. Syncfusion Trial expires in 30 days.

  ![Syncfusion Control Panel](Utilities_images/Dashboard_img16.png)

### General resources

* [Sales FAQ](https://www.syncfusion.com/sales/faq) - Clicking this link directs you to the FAQ page that lists common sales-related queries and other sales contact information.
* [Contact Support](https://www.syncfusion.com/Account/Logon?ReturnUrl=%2fsupport%2fdirecttrac) - Clicking this link directs you to the Direct-Trac Login page to contact the Support Team.
* Check for updates - Shows the latest version of Syncfusion Essential Studio if available.
* License Agreement - Shows the License Agreement for the current version of Essential Studio.

### Documentation

You can access the respective products user guide, online and offline class reference documents from here.

  ![Syncfusion Control Panel](Utilities_images/documentation.png)

### User Guide

PDF Download – Downloads the respective product and versions user guide documents in PDF format.

View on Web – You can also view the online user guide documents on clicking this button

### API Reference

   -	Visual Studio Help Viewer – You can download the offline class reference document and integrate it your Visual Studio Help Viewer
   -	View on Web – You can also view the online API Class Reference document for the respective product and version.
   
### Other products

You can also get a quick glimpse of our other available products here, download, and install it and have a try.

  ![Syncfusion Control Panel](Utilities_images/other-products.png)
  
If you have installed any other products in the same version, then you can open the respective products Syncfusion Control Panel from here too.


## Assembly Manager

The Assembly Manager is used to install and uninstall the assemblies, to and from the GAC and Public Assemblies folder under the installed location.

### Supported Platforms

Assembly Manager will be shipped for the following platforms as these platforms alone have the GAC support. Other Syncfusion platform assemblies will not be installed in GAC and the Assembly Manager will not be shipped.

* ASP.NET Web Forms
* ASP.NET MVC
* JavaScript(Essential JS 1)
* WPF
* Windows Forms
* FileFormats

### Launching the Assembly Manager 

Use the following steps to run the Assembly Manager.

1. Open Syncfusion Control Panel.
2. Click Add On and Utilities > Assembly Manager.
   
   ![Add On and Utilities](Utilities_images/Assembly-Manager_img1.png)

3. The Syncfusion {platform} Assembly Manager x.x.x.x window opens.

<div id="license">
You can also open the Assembly Manager from {Installed location}\Syncfusion\Essential Studio\{Platform}\x.x.x.x\Utilities\Assembly Manager\AssemblyManagerWindows.exe
</div>


   ![Assembly Manager](Utilities_images/Assembly-Manager_img3.png)

4. Select the required option from Select Assembly Type.

   * **Pre-built Assemblies** - These are the assemblies shipped with Essential Studio. Selecting this mode triggers the Assembly Manager to install the pre-built assemblies.    

    
5. Select the required option for the Action sections.

   **Action**

   The Assembly Manager can install or uninstall assemblies. To perform this action, select the **Install version x.x.x.x** or **Remove version x.x.x.x** radio button. To remove all, select the **Remove all versions** radio button.
   
    N> Remove All Versions must be used with caution in scenarios when one has applications depending on certain versions of the Syncfusion assemblies installed in the GAC. They may cease to function.

6. Select the required option for Framework sections. 

   **Framework**

   The Framework group box comprises of check boxes for the .NET Framework versions based on the Visual Studio SDK installed in the machine. The following check boxes are available:

   * 4.6 - Selecting **4.6** ensures installation of 4.6 assemblies into the GAC and assemblies folder. In cases where only Visual Studio 2015 SDK is installed, the 4.6 assemblies have to be deployed.
   * 4.5.1 - Selecting **4.5.1** ensures installation of 4.5.1 assemblies into the GAC and assemblies folder. In cases where only Visual Studio 2013 SDK is installed, the 4.5.1 assemblies have to be deployed.
   * 4.5 - Selecting **4.5** ensures installation of 4.5 assemblies into the GAC and assemblies folder. In cases where only Visual Studio 2012 SDK is installed, the 4.5 assemblies have to be deployed.
   * 4.0 - Selecting **4.0** ensures installation of 4.0 assemblies into the GAC and assemblies folder. In cases where only Visual Studio 2010 SDK is installed, the 4.0 assemblies have to be deployed.
   * 3.5 - Selecting **3.5** ensures installation of 3.5 assemblies into the GAC and assemblies folder. In cases where only Visual Studio 2008 SDK is installed, the 3.5, 2.0 assemblies can be deployed.
   * 2.0 - Selecting **2.0** ensures installation of 2.0 assemblies into the GAC and assemblies folder. In cases where only Visual Studio 2005 SDK is installed, the 2.0 assemblies have to be deployed.
   * All – Selecting **All** ensures installation of all Frameworks installed in the machine, and assemblies into the GAC and assemblies folder.

   N> * From 2018 Volume 4, Syncfusion has removed the .NET Framework 2.0, 3.5, 4.5.1 and MVC3 assemblies from installer. Refer to [this](https://help.syncfusion.com/common/essential-studio/installation/essential-studio-platform-framework-add-ons) topic to enable 2.0,3.5 and 4.5.1 checkboxes.  
   * By default 2.0 is enabled in a system where Visual Studio 2008 SDK is installed.

7. Click Perform Action. It starts processing.

   ![Assembly Manager](Utilities_images/Assembly-Manager_img7.png)

8. Once the action is completed, a confirmation message is displayed.

   ![Assembly Manager](Utilities_images/Assembly-Manager_img8.png)

9. Click OK.

   ![Assembly Manager](Utilities_images/Assembly-Manager_img9.png)

   
## License Manager

The License Manager helps to manage license key information, such as the validity of a Syncfusion key used on your system.

N> * License Manager is used only to view the license information, adding\removing the unlock key.
* Syncfusion License key should not be used here. Refer this KB article to know more about the difference between the Syncfusion Unlock Key and the Syncfusion License Key

### Launching License Manager

Follow the steps provided to launch the License Manager from the Dashboard.

1. Open the Syncfusion Control Panel.
2. Click Add On and Utilities->License Manager.
3. The Syncfusion License Manager dialog box opens. 
   
   ![License Manager](Utilities_images/License-Manager_img1.png)

### Adding a Product Key

The following are the steps to add a product key.

1. Open the Syncfusion License Manager Dialog box.

   ![License Manager](Utilities_images/License-Manager_img2.png)

2. Click Add Key. The following dialog box opens.

   ![License Manager](Utilities_images/License-Manager_img3.png)

3. Enter the license key of the product in the space provided.

4. Click OK. The entered key is displayed in the log.

   ![License Manager](Utilities_images/License-Manager_img4.png)

By adding an additional product key, you can also:

* Extend evaluation period. This is applicable for evaluation versions of EssentialStudio.
* Unlock additional products.

### Removing a Product Key

This option allows you to remove a product key from the License Manager window. It allows you to remove an incorrectly added or old license key.

The following are the steps to remove a license key:

1. Open the Syncfusion License Manager dialog box.
2. Select the key to be removed. The selected key is highlighted. 

   ![License Manager](Utilities_images/License-Manager_img5.png)

3. Click Remove Key. The selected key is removed.

    N> The removal is reflected in the log, when the product key has already been added.

### Copying a Product Key

You can copy the product key from the License Manager window to the clipboard. The following are the steps to copy the license key.

1. Open the Syncfusion License Manager Dialog box.
2. Select the required key to be copied. The selected key is highlighted.
3. Click Copy Key. The selected key is copied. You can paste the key in the required place.

## Toolbox Configuration 

Syncfusion provides toolbox support for WPF, Windows Forms, ASP.NET Web Forms, UWP and Xamarin platforms. The Syncfusion Toolbox Installer utility adds the Syncfusion controls into the Visual Studio .NET toolbox.

N> Toolbox configuration support is not available for the Visual Studio Express Edition. However, you can manually configure the Syncfusion controls into the Visual Studio Express Toolbox. To do so, refer the [Manual Toolbox Configuration](https://help.syncfusion.com/common/faq/how-to-configure-the-toolbox-of-visual-studio-manually) .

### Configuring Toolbox

#### For Xamarin:

To configure the Syncfusion Xamarin controls to the Visual Studio toolbox, refer [this](https://help.syncfusion.com/extension/xamarin-extension/toolbox) link.

I> Syncfusion has started providing Toolbox support for Xamarin platform from v16.2.0.41

#### For UWP:

Syncfusion UWP controls will be automatically configured in Visual Studio toolbox while installing the Syncfusion UWP installer.

#### For WPF, Windows Forms and ASP.NET Web Forms platforms:

Syncfusion controls will be automatically configured in the Visual Studio toolbox, while installing the Syncfusion installer, if the <b>“Configure Syncfusion Controls in Visual Studio”</b> checkbox is selected from installer UI.

To launch Toolbox configuration utility, follow the steps given below:

   
1. Open the Syncfusion Control Panel, click **Add On and Utilities > Toolbox Installer**.
   
   ![Add On and Utilities](Utilities_images/Toolbox-Configuration_img1.png)
   

2. Toolbox Installer will be opened.

   ![Toolbox Installer](Utilities_images/Toolbox-Configuration_img2.png)

   The following options are available in Toolbox Configuration:

   * Install VS2005 – Configures Framework 2.0 Syncfusion controls in VS 2005 toolbox.
   * Install VS2008 – Configures Framework 3.5 Syncfusion controls in VS 2008 toolbox.
   * Install VS2010 – Configures Framework 4.0 Syncfusion controls in VS 2010 toolbox.
   * Install VS2012 – Configures Framework 4.5 Syncfusion controls in VS 2012 toolbox.
   * Install VS2013 – Configures Framework 4.5.1 Syncfusion controls in VS 2013 toolbox.
   * Install VS2015 – Configures Framework 4.6 Syncfusion controls in VS 2015 toolbox.
   * Install VS2017 – Configures Framework 4.6 Syncfusion controls in VS 2017 toolbox.
   * Install VS2019 – Configures Framework 4.6 Syncfusion controls in VS 2019 toolbox
   
    N> You can also configure Syncfusion controls from a lower version Framework assembly to higher version of Visual Studio.
   
3. An Information message is displayed indicating the successful configuration of Toolbox. Click OK.

   ![Toolbox Installer](Utilities_images/Toolbox-Configuration_img3.png)
   
   
   N> * You must reset the toolbox, when the installed controls are not reflected properly in the Toolbox.

   * This tool configures only the controls that are located under {Installed Location}\Assemblies\{Framework version}.
   
### Configuring toolbox for WPF .NET 5.0 projects

From 2021 Volume 1, Syncfusion started providing toolbox support for WPF .NET 5.0 framework in Visual Studio 2019. Syncfusion controls will be automatically configured in the Visual Studio 2019 toolbox for WPF .NET 5.0 project, after installing the Syncfusion WPF installer.

N> * Syncfusion included this toolbox support for .NET 5.0 WPF platform from 2021 Volume 1 release version v19.1.0.54 only.
* After installing the WPF setup, if the project created with TargetFramework .NET Core 3.1 and changed to .NET 5.0, you need to restart Visual Studio to get the Syncfusion controls in Visual Studio Toolbox.
* Visual Studio 2019 16.7 Preview 2 and later is required


### Configuring toolbox for .NET Core 3.1 projects

To configure the Syncfusion toolbox in the WPF .NET Core application, the Syncfusion NuGet packages should be installed in the .NET Core application. After installing the Syncfusion NuGet packages in .NET Core application, the corresponding NuGet packages Syncfusion components will be configured in Visual Studio toolbox. 

Please refer the documentation [link](https://help.syncfusion.com/wpf/visual-studio-integration/nuget-packages#using-components-from-nuget), to learn more about how to use the Syncfusion components using the Syncfusion NuGet packages in .NET Core application.

   
## Multi-Target Manager

Multi-Target Manager helps to manage multiple .NET Frameworks in your Visual Studio 2008 project that is, switching between multiple Frameworks.

 N> This is not essential for VS 2010 because Common Language Runtime (CLR) differs for both 3.5 and 4.0 Frameworks. VS 2010 selects the required .NET Framework assembly for the corresponding projects. 3.5 and 4.0 are the only Frameworks configured; the MultiTarget Manager utility allows you to work on Framework 2.0 with VS 2010.

### When to Use Multi-Target Manager?

When Essential Studio is installed in a machine comprising both 2.0 and 3.5 Frameworks, then, by default, the target Framework is set to 3.5, and the following registry entry AssemblyFoldersEx is also set to 3.5 assembly. You can use the Multi-Target Manager to change the target Framework to 2.0. 

**Registry Location:** HKLM\Software\Microsoft\.NetFramework\v3.5\AssemblyFoldersEx\Syncfusion Essential {platform} 3.5

### Launching MultiTarget Manager 

1. Open the Multi-Target Manager from below location

   <div id="license">
   <b>Location:</b>{Installed location}\Syncfusion\Essential Studio\{platform}\x.x.x.x\Utilities\MultiTargetManager\MultiTargetManager.exe
   </div>

2. The Essential Studio Multi-Target Manager x.x.x.x dialog box opens.

   ![Multi-Target Manager](Utilities_images/Multi-Target-Manager_img4.png)

3. Select the required version from the drop-down list. The Multi-Target Manager dialog box opens.

   ![Multi-Target Manager](Utilities_images/Multi-Target-Manager_img5.png)

4. Click OK.

5. Open an application.

6. Refresh the application before building.

    N> The target value and the registry value change according to the selected Framework version.
   

## Project Migration

The Project Migration tool helps to upgrade the projects to the given Syncfusion Essential Studio Version.

Syncfusion Project Migration tool supports from, Syncfusion Essential Studio Version 3.2.1.0 to the latest version and the supported platforms are Windows Forms, WPF and Universal Windows Platform.

N> Project Migration utility will change the Visual Studio Target Framework version and Syncfusion assembly version alone in the .csproj files.

The following steps illustrate how to migrate a project.

### Windows Forms, WPF and Universal Windows Platform

1. Open the Project Migration Tool from the following location.

   <div id="license">
   <b>Location:</b> {Installed location}\Syncfusion\Essential Studio\{Platform}\x.x.x.x\Utilities\Project Migration\ProjectMigrationWindows.exe.
   </div>

   ![Project Migration Tool](Utilities_images/Project-Migration_img1.png)

2. Select the project to be upgraded in the **Select Project Folder** field.

    N> If you have multiple projects in the same folder, you can select/deselect the projects of your choice. You can also select multiple projects location by using the **Select Folder List** option.

3. Select a folder to store a backup in the **Select backup folder** field. 

4. By default, corresponding Essential Studio version will be displayed in the **Migrate to Essential Studio Version** field.

5. Select the required **Visual Studio .NET Framework version** and **Syncfusion .NET Framework version** from the respective drop-down list.

6. When you refer the Syncfusion assemblies from Hint path instead of GAC location then, copy the latest assemblies to that location manually or select the Remove hint path from projects check box, to remove the hint from the project. If you are migrating UWP project and you are using the UWP assemblies in your projects instead of SDK, don't enable the **Remove hint path from projects** option. 

    N> If you have referred the Syncfusion assemblies to your project from hint path and you have selected the Remove hint path from projects check box in Project Migration utility, Syncfusion assemblies will be referred from GAC for Windows Forms and WPF platforms if the assemblies are installed in GAC

7. Click Perform Action. The utility upgrades the selected projects to the newer version. 

### For Web platforms.

For Web platforms, follow the steps suggested in the following documentation link to migrate the projects to the latest version. 

ASP.NET Web Forms - [ASP.NET Migration](https://help.syncfusion.com/extension/aspnet-extension/project-migration) 

ASP.NET MVC - [ASP.NET MVC Migration](https://help.syncfusion.com/extension/aspnet-mvc-extension/project-migration)

ASP.NET Core - [ASP.NET Core Migration](https://help.syncfusion.com/extension/aspnetcore-extension/project-migration)

### Command Line

The following steps illustrate how to run the Project Migration tool through command line.

1. Open the Command Prompt in administrator mode and navigate to the following location.

   <div id="license">
   <b>Location:</b> {Installed Drive}\{ProgramFiles Folder}\Syncfusion\Essential Studio\{version}\Utilities\Project Migration\
   <b>Example:</b> C:\Program Files (x86)\Syncfusion\Essential Studio\{Platform}\16.1.0.24\Utilities\Project Migration\
   </div>


2. Run “ProjectMigrationConsole.exe” with the following arguments.

   <div id="license">
   <b>Arguments:</b> /source:"sourcepath" /studio:"Essential Studio version" /framework:"[v3.5] / [v2.0] / [v4.0] / [v4.5] / [v4.5.1] / [v4.6]" /targetframework:"[v3.5] / [v2.0] / [v4.0] / [v4.5] / [v4.5.1] / [v4.6]" /backup:"Backupfolderpath" /hintpath:"[False] / [True]" /sourcefolder:"sourcefolderpath" /isfolderbackedup:"[False] / [True]"
   <b>Example:</b> /source:"C:\Users\syncfusion\Documents\Visual Studio 2017\Projects\SyncfusionWindowsFormsApplication1\SyncfusionWindowsFormsApplication1" /studio:"16.1.0.24" /framework:"v4.6" /targetframework:"v4.7" /backup:"C:\Syncfusion\backup\SyncfusionWindowsFormsApplication1_2018_02_27_022449\SyncfusionWindowsFormsApplication1" /hintpath:"False" /sourcefolder:"C:\Users\syncfusion\Documents\Visual Studio 2017\Projects\SyncfusionWindowsFormsApplication1" /isfolderbackedup:"False"
   </div>

The following screenshot illustrates this.

![Project Migration Console](Utilities_images/Command-Line_img1.png)

## Configuring Extension

Syncfusion provides VSIX Installer for configuring the Syncfusion extensions in Visual Studio. On installing the Syncfusion platform installer, all the required extensions for the corresponding product will be configured in the supported Visual Studio.

You can also use the utility from the following location in command line to configure the available extensions,

**Location :** {Program Files Folder}\Syncfusion\Essential Studio\WPF\19.1.0.54\Utilities\Extensions\VSIX Installer\SyncfusionVSIXInstallerConsole.exe

**Command Line Parameters**

**Arguments:** {InstallPath}\Utilities\Extensions\VSIX Installer\SyncfusionVSIXInstallerConsole.exe /action:install /isinstaller:true /platform:"{platform}"

<table>
<tr>
<td><b>Platform</b></td>
<td><b>Parameter</b></td>
</tr>
<tr>
<td>All the Essential Studio platforms</td>
<td>{InstallPath}\Utilities\Extensions\VSIX Installer\SyncfusionVSIXInstallerConsole.exe /action:install /isinstaller:true /platform:"Windows,WPF,ASP.NET,ASP.NET MVC,ASP.NET Core,Universal Windows,ASP.NET MVC - EJ2,ASP.NET CORE - EJ2,Xamarin"</td>
</tr>
<tr>
<td>WPF</td>
<td>{InstallPath}\Utilities\Extensions\VSIX Installer\SyncfusionVSIXInstallerConsole.exe /action:install /isinstaller:true /platform:"WPF"</td>
</tr>
<tr>
<td>Windows Forms</td>
<td>{InstallPath}\Utilities\Extensions\VSIX Installer\SyncfusionVSIXInstallerConsole.exe /action:install /isinstaller:true /platform:"Windows"</td>
</tr>
<tr>
<td>ASP.NET Web Forms (Essential JS 1)</td>
<td>{InstallPath}\Utilities\Extensions\VSIX Installer\SyncfusionVSIXInstallerConsole.exe /action:install /isinstaller:true /platform:"ASP.NET"</td>
</tr>
<tr>
<td>ASP.NET MVC (Essential JS 1)</td>
<td>{InstallPath}\Utilities\Extensions\VSIX Installer\SyncfusionVSIXInstallerConsole.exe /action:install /isinstaller:true /platform:"ASP.NET MVC"</td>
</tr>
<tr>
<td>ASP.NET Core (Essential JS 1)</td>
<td>{InstallPath}\Utilities\Extensions\VSIX Installer\SyncfusionVSIXInstallerConsole.exe /action:install /isinstaller:true /platform:"ASP.NET Core"</td>
</tr>
<tr>
<td>UWP</td>
<td>{InstallPath}\Utilities\Extensions\VSIX Installer\SyncfusionVSIXInstallerConsole.exe /action:install /isinstaller:true /platform:"Universal Windows"</td>
</tr>
<tr>
<td>ASP.NET MVC (Essential JS 2)</td>
<td>{InstallPath}\Utilities\Extensions\VSIX Installer\SyncfusionVSIXInstallerConsole.exe /action:install /isinstaller:true /platform:"ASP.NET MVC - EJ2"</td>
</tr>
<tr>
<td>ASP.NET Core (Essential JS 2)</td>
<td>{InstallPath}\Utilities\Extensions\VSIX Installer\SyncfusionVSIXInstallerConsole.exe /action:install /isinstaller:true /platform:"ASP.NET CORE - EJ2"</td>
</tr>
<tr>
<td>JavaScript (Essential JS 2)</td>
<td>{InstallPath}\Utilities\Extensions\VSIX Installer\SyncfusionVSIXInstallerConsole.exe /action:install /isinstaller:true /platform:"JavaScript - EJ2"</td>
</tr>
<tr>
<td>Blazor</td>
<td>{InstallPath}\Utilities\Extensions\VSIX Installer\SyncfusionVSIXInstallerConsole.exe /action:install /isinstaller:true /platform:"Blazor"</td>
</tr>
<tr>
<td>Xamarin</td>
<td>{InstallPath}\Utilities\Extensions\VSIX Installer\SyncfusionVSIXInstallerConsole.exe /action:install /isinstaller:true /platform:"Xamarin"</td>
</tr>
<tr>
<td>FileFormats</td>
<td>{InstallPath}\Utilities\Extensions\VSIX Installer\SyncfusionVSIXInstallerConsole.exe /action:install /isinstaller:true /platform:"FileFormats"</td>
</tr>
</table>


	

