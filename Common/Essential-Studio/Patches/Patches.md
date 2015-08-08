---
layout: post
title: Patches
description: patches
platform: js
control: Essential Studio
documentation: ug
---

# Patches

Syncfusion provides patch setup to install a new assembly, either to add new features or to fix issues.


## Installing a Patch Setup

The following procedure illustrates how to install a patch.

> Note:
> 
> * Before installing the patch, ensure that corresponding Essential Studio version and platforms to install the patch in your machine.
> * If you installed Syncfusion WinRT platform alone then the Assembly Manager execution dialog will not appear during the patch installation. It will skip this dialog from step 1 to step 4. Because, Assembly Manager Utility is not shipped with WinRT platform.

1. Double-click the Syncfusion Essential Studio patch setup file. The Syncfusion Essential Studio Service Pack opens.

   ![](Installing-a-Patch-Setup_images/Installing-a-Patch-Setup_img2.png)

2. Click Next. The Assembly Manager screen opens.

   ![](Installing-a-Patch-Setup_images/Installing-a-Patch-Setup_img3.png)

3. Select the Run Assembly Manager check box to install the assemblies in GAC.

4. Click Next. The Ready To Install screen opens.

   ![](Installing-a-Patch-Setup_images/Installing-a-Patch-Setup_img4.png)

5. Click Install to continue installing.

   ![](Installing-a-Patch-Setup_images/Installing-a-Patch-Setup_img5.png)


   > Note: The patch is installed on your computer, and a dialog box appears when the installation is complete.

   ![](Installing-a-Patch-Setup_images/Installing-a-Patch-Setup_img7.png)

6. Click Finish. 

   The new assemblies are placed in the Pre-Compiled Assemblies folder. These new assemblies can be referenced in your project.
   
   
## Command Line Installation

The patch can also be installed through Command Line. Follow the given steps to run the Patch Installer via Command Line. 

1. Open Command Prompt with administrative privileges, that is, in the Admin mode.
2. Navigate to the patch file’s location and pass the following argument:

   #### _{patchsetup.exe} [/silent or /verysilent]_

   #### Example: 

   SyncfusionPatch_12.4.0.24_234640_5192015083205629_139538.exe /verysilent
   SyncfusionPatch_12.4.0.24_234640_5192015083205629_139538.exe /silent
 
   ![](Command-Line-Installation_images/Command-Line-Installation_img1.png)

   > Note:
   > 
   > /silent – Displays the progress dialog alone during the patch setup installation.
   > /verysilent – It is installed in the background.
   
## Reverting a Patch

The Patch Install takes a backup of the Release Assemblies and stores them in the Backup Assemblies folder. The patch assemblies are also stored in the Patch folder. You can revert back when needed. 

Reverting back to Release Assemblies: 

The following steps help you revert to the Release Assemblies. 

1. Copy the Release Assemblies from the Backup Assemblies folder.

2. Paste them in the precompiledassemblies folder.

3. Open Dashboard > Utility > Assembly Management > Assembly Manager.

   ![](Reverting-a-Patch_images/Reverting-a-Patch_img1.png)

4. Select the Remove allversions radio button.

5. Click Perform Action. All versions are removed.

6. Select Install version x.x.x.x.

   > Note: x.x.x.x has to be replaced with the corresponding Essential Studio Version.

7. Click Perform Action. The assemblies for that specific version are configured in your machine.

   > Note: You can also revert to specific patch assemblies by copying the patch assemblies from the Patch folder and adding them in the precompiledassemblies folder.