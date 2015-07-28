---
layout: post
title: Command-Line
description: command line
platform: js
control: Essential Studio
documentation: ug
---

#### Command Line

The following steps illustrate how to run the Project Migration tool through command line.

1. Open the Command Prompt in administrator mode and navigate to the following location:

{Installed Drive}\{ProgramFiles Folder}\Syncfusion\Essential Studio\{version}\Utilities\Project Migration\

Example: C:\Program Files (x86)\Syncfusion\Essential Studio\12.1.0.43\Utilities\Project Migration\



2. Run “ProjectMigrationConsole.exe” with the following arguments:

/source:"sourcepath" /studio:"Essential Studio version" /framework:"[v3.5] / [v2.0] / [v4.0] / [v4.5] / [v4.5.1]" /backup:"Backupfolderpath" /hintpath:"[False] / [True]"

Example: /source:"C:\Users\Vadivel\Documents\Visual Studio 2012\Projects\WindowsFormsApplication3" /studio:"11.2.0.25" /framework:"v4.0" /backup:"E:\ProjectMigrationBackup\WindowsFormsApplication3" /hintpath:"False"



The following screenshot illustrates this.

![cid:image003.png@01CEB5A3.33923680](Command-Line_images/Command-Line_img1.png)
{:.image }


