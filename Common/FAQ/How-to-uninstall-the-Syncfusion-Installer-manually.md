---
layout: post
title: Installer FAQ - Uninstall Syncfusion Installer Manually | Syncfusion
description: Learn here some information about how to uninstall the syncfusion essential studio installer manually.
platform: common
control: Essential Studio
documentation: ug
---

# How to uninstall the Syncfusion<sup style="font-size:70%">&reg;</sup> Installer manually?

Sometimes, installation may crash due to the machine getting switched off during installation or for other reasons. In such cases, the Uninstall utility is not available. The following are the steps to uninstall manually:

## For Essential Studio<sup style="font-size:70%">&reg;</sup> version 16.1.0.37 and before

1. Download and install the **Windows Installer Cleanup** utility from the following link:  [Windows Installer Cleanup](https://help.syncfusion.com/uwp/overview).
2. Remove Syncfusion’s product-related installers, for the version you are trying to uninstall, using the Windows Installer Cleanup utility.

   ![Uninstall Manually](How-to-uninstall-the-Syncfusion-Setup-manually_images/How-to-uninstall-the-Syncfusion-Setup-manually_img1.png)

3. Manually remove or delete the installed Syncfusion<sup style="font-size:70%">&reg;</sup> files from the following location.

   **Source (Windows XP, Windows Vista, Windows 7):** (Installed location)\ Syncfusion\Essential Studio\ (version)

   **Example:** C:\Program Files\Syncfusion\Essential Studio\9.4.0.62

   **Samples (Windows XP):** C:\Syncfusion\(version)

   **Example:** C:\Syncfusion\9.4.0.62

   **Samples (Windows Vista, Windows 7):** C:\Users\(user name)\AppData\Local\Syncfusion\EssentialStudio\ (version)

   **Example:** C:\Users\(user name)\AppData\Local\Syncfusion\EssentialStudio\9.4.0.62

   N> Sample locations mentioned above is default for corresponding OS. When you have installed samples in any other location, remove it from that location.

4. Essential Studio<sup style="font-size:70%">&reg;</sup> is uninstalled. You can install it again.

## For Essential Studio<sup style="font-size:70%">&reg;</sup> version 16.2.0.41 and later

1.	Download and extract the **SyncfusionCleanUp.zip** from [here](http://files2.syncfusion.com/dtsupport/directtrac/general/ze/SyncfusionCleanUp-18.4.0.391826167431.zip). 

2.	Run the SyncfusionCleanUp.exe by double clicking it. This will remove the installed registry entries from your machine for Syncfusion version present in “SyncfusionCleanUp.exe.config” file.

    N> If you want to remove entries for other version you can change the version in **“SyncfusionCleanUp.exe.config”** file and run the utility.
	
	![Uninstall Manually](How-to-uninstall-the-Syncfusion-Setup-manually_images/How-to-uninstall-the-Syncfusion-Setup-manually_img3.png)

3.	Manually remove or delete the installed Syncfusion<sup style="font-size:70%">&reg;</sup> files from the following location.

    **Source location:** (Installed location)\ Syncfusion\Essential Studio\ (platform)\(version)

    **Example:** C:\Program Files\Syncfusion\Essential Studio\(WPF)\18.4.0.30

    **Samples location:** C:\Users\Public\Documents\Syncfusion\(platform)\(version)

    **Example: C:\Users\Public\Documents\Syncfusion\WPF\18.4.0.30

4.	Now try to install Essential Studio<sup style="font-size:70%">&reg;</sup> installer, once the above operation is completed.

