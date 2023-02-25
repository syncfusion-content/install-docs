---
layout: post
title: Assembly Version Format of Essential Studio | Syncfusion
description: Learn here some information about the assembly version format of Syncfusion Essential Studio and more details.
platform: common
control: Essential Studio
documentation: ug
---

# Assembly Information

## Assembly Description

We have two types of assembly descriptions to distinguish between trial and licensed assemblies.

### Trial Installer

In the trial installer, License Enforced Syncfusion assemblies will be shipped and this information will be present in the File Description as **License Required (LR).**

**Example:** Syncfusion.SfBarcode.XForms (LR)

![Assembly Details](Documentation-Setup_images/Assembly-Description_img1.png)

### Licensed Installer

In the License installer, licensed Syncfusion assemblies will be shipped and **LR** information will not be shown in the File description.

**Example:** Syncfusion.SfBarcode.XForms

![Assembly Details](Documentation-Setup_images/Assembly-Description_img2.png)


## Assembly Version Format

The assembly version format differs for each of the Essential Studio platform. Refer the following table for the assembly version’s format for ASP.NET MVC (Essential JS 2), WPF, Windows Forms, UWP, WinUI, .NET MAUI and Xamarin platforms.



<table>
<tr>
<td>
<b>Platforms/Frameworks</b></td><td>
<b>4.0</b></td><td>
<b>4.5</b></td><td>
<b>4.5.1</b></td><td>
<b>4.6</b></td><td>
<b>netcoreapp3.1</b></td><td>
<b>net 5.0</b></td><td>
<b>net 6.0</b></td><td>
<b>uap10.0</b></td></tr>
<tr>
<td>
<b>.NET MAUI</b></td><td>
NA</td><td>
NA</td><td>
NA</td><td>
NA</td><td>
NA</td><td>
NA</td><td>
21.0.x</td><td>
NA</td></tr>
<tr>
<td>
<b>WinUI</b></td><td>
NA</td><td>
NA</td><td>
NA</td><td>
NA</td><td>
NA</td><td>
21.0.x</td><td>
NA</td><td>
21.0.x</td></tr>
<tr>
<td>
<b>Windows Forms</b></td><td>
21.0400.x</td><td>
21.0450.x</td><td>
21.0451.x</td><td>
21.0460.x</td><td>
21.0.x</td><td>
21.0.x</td><td>
NA</td><td>
NA</td></tr>
<tr>
<td>
<b>WPF</b></td><td>
21.0400.x</td><td>
21.0450.x</td><td>
21.0451.x</td><td>
21.0460.x</td><td>
21.0.x</td><td>
21.0.x</td><td>
NA</td><td>
NA</td></tr>
<tr>
<td>
<b>UWP</b></td><td>
NA</td><td>
NA</td><td>
NA</td><td>
21.0.x</td><td>
NA</td><td>
NA</td><td>
NA</td><td>
NA</td></tr>
<tr>
<td>
<b>Xamarin</b></td><td>
NA</td><td>
NA</td><td>
21.0.x</td><td>
NA</td><td>
NA</td><td>
NA</td><td>
NA</td><td>
NA</td></tr>
<tr>
<td>
<b>ASP.NET MVC (Essential JS 2)</b></td><td>
MVC 4 - 21.0400.x</td><td>
MVC 5 - 21.0450.x</td><td>
NA</td><td>
NA</td><td>
NA</td><td>
NA</td><td>
NA</td><td>
NA</td></tr>
</table>

**For .NET Standard Frameworks:**

<table>
<tr>
<td>
<b>netstandard 1.2</b></td><td>
<b>netstandard 1.4</b></td><td>
<b>netstandard 2.0</b></td></tr>
<tr>
<td>
21.0.x</td><td>
21.0.x</td><td>
21.0.x</td></tr>
</table>

The following Essential Studio platforms do not have assembly support.

* JavaScript (Essential JS 2)

## Supported Framework version for Essential Studio Assemblies

Following are the supported Framework versions of the Essential Studio assemblies

<table>
<tr>
<th>Essential Studio platform</th>
<th>Supported Framework version</th>
</tr>
<tr>
<td>Xamarin</td>
<td>netstandard 2.0. Find the platform specific version {{'[here](https://help.syncfusion.com/xamarin/installation-and-upgrade/system-requirements#supported-platforms)'| markdownify }}</td>
</tr>
<tr>
<td>.NET MAUI</td>
<td>.NET 6.0</td>
</tr>
<tr>
<td>UWP</td>
<td>Target Platform version UAP 10.0.16299 and above</td>
</tr>
<tr>
<td>WinUI</td>
<td>Target Platform version UAP 10.0.17134 and above</td>
</tr>
<tr>
<td>WPF</td>
<td>.NET Framework 4.0 to 4.6, .NET Core 3.1 and .NET 5.0</td>
</tr>
<tr>
<td>Windows Forms</td>
<td>.NET Framework 4.0 to 4.6, .NET Core 3.1 and .NET 5.0</td>
</tr>
<tr>
<td>ASP.NET MVC (Essential JS 2)</td>
<td>MVC 4 and MVC 5</td>
</tr>
</table>