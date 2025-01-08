---
layout: post
title: Install Trial and Licensed Installer of Essential Studio  | Syncfusion
description: Learn here about the information of how to install the trial and licensed installer side by side safely.
platform: common
control: Essential Studio
documentation: ug
---


# How to install the Trial and Licensed installer side by side safely?

You can install both Licensed and Trial installer side by side for different Essential Studio<sup style="font-size:70%">&reg;</sup>  products. The following alert message will be shown if you install the combination of License and Trial platform installer. However, you can continue the installation. The alert message will be shown for the following products.

* Windows Forms
* WPF
* File Formats  

<em>**Online Installer**</em>

![License Conflict Alert](Errors/Side-by-side_img2.png)

<em>**Offline Installer**</em>

![Alert Message](Errors/Side-by-side_img1.png)


### Problem

If you install Licensed and Trial installer in the same machine, licensing issues will occur while development and the following licensing alert will be shown.

![Syncfusion License](Errors/Side-by-side_img3.png)

### Reason

Assemblies will conflict as both Licensed and Trial assemblies will be present in GAC.

### Suggested solution

To avoid licensing issues while running demos or using Syncfusion<sup style="font-size:70%">&reg;</sup>  controls, launch the [Assembly Manager](https://help.syncfusion.com/common/essential-studio/utilities#assembly-manager) for the licensed product you're using for development and install the licensed assemblies in GAC.

