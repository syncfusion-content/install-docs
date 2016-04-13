---
layout: post
title: How-to-Upgrade-the-Project-into-a-New-Syncfusion-V
description: how to upgrade the project into a new syncfusion version? 
platform: common
control: Essential Studio
documentation: ug
---

# How to Upgrade the Project into a New Syncfusion Version? 


## Upgrade the Project Using Project Migration Utility

To upgrade the project using the Project Migration Utility, refer to [Project Migration](http://help.syncfusion.com/common/essential-studio/utilities#project-migration).

## Upgrading the Projects Manually

You can upgrade the project in two methods, based on the procedure used in your project, to reference the Syncfusion assemblies. They are:

### CopyLocal=True

1. Set the SpecificVersion to False.
2. Remove the bin and obj folders in your local project directory.
3. Replace the latest assemblies with the upgraded assemblies in the local folder of your project.
4. Recompile the project.

### CopyLocal=False

1. Ensure that the old Syncfusion assemblies are removed from GAC.
   * For 2.0 and 3.5 assemblies: (C:\windows\assembly)
   * For 4.0, 4.5, and 4.5.1 assemblies: (C:\Windows\Microsoft.NET\assembly\GAC_MSIL)
2. Install the latest Syncfusion assemblies on your machine using the Syncfusion Assembly Manager.
3. Set the SpecificVersion to False.
4. Recompile your project; the latest assemblies from GAC refer to your project automatically. 
   
   ![](Upgrading-the-Projects-Manually_images/Upgrading-the-Projects-Manually_img1.png)

### Switching the Framework Version While Upgrading the Project

When you want to switch the Framework version while upgrading the project, use the Multi-Target Manager from the Syncfusion Dashboard.

After switching the Framework version using Multi-Target Manager, remove the bin and obj folders from your local project directory, and then recompile your project.

For more details about Multi-Target Manager, refer to [Multi-Target Manager](http://help.syncfusion.com/common/essential-studio/utilities#multi-target-manager).

### Migrating the Resource Files

Follow the given steps to move the resource files (.resx) of your project to the newer version:

1. Open Start > Syncfusion > Essential Studio x.x.x.x > Utilities > Migration > ConvertResx(Framework 2.0,3.5 or 4.0).
2. Click the Choose ResX Files to convert.
3. Select the Resx files you want to convert.
4. Click Start Converting Files.
5. After the conversion, the new Resx files should have the same name as the original files. Copies of the original files have the old suffix added to their names.
