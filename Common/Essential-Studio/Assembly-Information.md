---
layout: post
title: Assembly Version Format | Common | Syncfusion
description: Learn here some information about the Assembly Version format of Syncfusion Essential Studio and more details.
platform: common
control: Essential Studio
documentation: ug
---

# Assembly Information

## Assembly Description

Starting with version 16.2.0.41 (2018 Vol 2), Syncfusion provides separate installer for Paying (Licensed installer) and Evaluation (Trial installer) customers. In the trial installer, License Enforced Syncfusion assemblies will be shipped and this information will be present in the File Description as **License Required (LR)**.

**Example:** Syncfusion.SfBarcode.XForms (LR)

![Assembly Details](Documentation-Setup_images/Assembly-Description_img1.png)

In the License installer, licensed Syncfusion assemblies will be shipped and **LR** information will not be shown in the File description.

**Example:** Syncfusion.SfBarcode.XForms

![Assembly Details](Documentation-Setup_images/Assembly-Description_img2.png)


## Assembly Version Format

The assembly version format differs for each platform. Refer the following table for the assembly version’s format for ASP.NET Web Forms, ASP.NET MVC (Essential JS 1), ASP.NET MVC (Essential JS 2), JavaScript (Essential JS 1), WPF, Windows Forms, UWP and Xamarin platforms.



<table>
<tr>
<td>
<b>Platforms/Frameworks</b></td><td>
<b>2.0</b></td><td>
<b>3.5</b></td><td>
<b>4.0</b></td><td>
<b>4.5</b></td><td>
<b>4.5.1</b></td><td>
<b>4.6</b></td><td>
<b>netcoreapp3.0</b></td></tr>
<tr>
<td>
<b>Windows Forms</b></td><td>
17.1200.0.x</td><td>
17.1350.0.x</td><td>
17.1400.0.x</td><td>
17.1450.0.x</td><td>
17.1451.0.x</td><td>
17.1460.0.x</td><td>
17.1300.0.x</td></tr>
<tr>
<td>
<b>WPF</b></td><td>
NA</td><td>
17.1350.0.x</td><td>
17.1400.0.X</td><td>
17.1450.0.X</td><td>
17.1451.0.X</td><td>
17.1460.0.x</td><td>
17.1300.0.x</td></tr>
<tr>
<td>
<b>UWP</b></td><td>
NA</td><td>
NA</td><td>
NA</td><td>
NA</td><td>
NA</td><td>
17.1460.0.x</td><td>
NA</td></tr>
<tr>
<td>
<b>Xamarin</b></td><td>
NA</td><td>
NA</td><td>
NA</td><td>
NA</td><td>
17.1451.0.x</td><td>
NA</td><td>
NA</td></tr>
<tr>
<td>
<b>ASP.NET MVC (Essential JS 2)</b></td><td>
NA</td><td>
NA</td><td>
MVC 4 - 17.1400.0.x</td><td>
MVC 5 - 17.1500.0.x</td><td>
NA</td><td>
NA</td><td>
NA</td></tr>
<tr>
<td>
<b>ASP.NET Web Forms (Essential JS 1)</b></td><td>
NA</td><td>
17.1350.0.x</td><td>
17.1400.0.x</td><td>
17.1450.0.x</td><td>
17.1451.0.x</td><td>
17.1460.0.x</td><td>
NA</td></tr>
<tr>
<td>
<b>ASP.NET MVC (Essential JS 1)</b></td><td>
NA</td><td>
NA</td><td>
<li>MVC 3 - 17.1300.0.x</li><li>MVC 4 - 17.1400.0.x</li></td><td>
MVC 5 - 17.1500.0.x</td><td>
NA</td><td>
NA</td><td>
NA</td></tr>
<tr>
<td>
<b>JavaScript (Essential JS 1)</b></td><td>
NA</td><td>
17.1350.0.x</td><td>
17.1400.0.X</td><td>
17.1450.0.X</td><td>
17.1451.0.X</td><td>
17.1460.0.X</td><td>
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
17.1120.0.x</td><td>
17.1140.0.x</td><td>
17.1200.0.x</td></tr>
</table>

The following Essential Studio platforms do not have assembly support.

* JavaScript (Essential JS 2)
* PHP (Essential JS 1)
* JSP (Essential JS 1)