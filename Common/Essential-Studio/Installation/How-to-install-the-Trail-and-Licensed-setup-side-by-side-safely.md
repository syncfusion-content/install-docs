---
layout: post
title: How to install the Trial and Licensed setup side by side safely?  | common | Syncfusion
description: how to install the trial and licensed setup side by side safely?
platform: common
control: Essential Studio
documentation: ug
---


# How to install the Trial and Licensed setup side by side safely?

You can install both Licensed and Trial setup side by side but not for the same platform. Also, the following alert message will be shown while installation. However, you can continue the installation.   



<style>
#license {
    font-size: .88em!important;
margin-top: 1.5em;     margin-bottom: 1.5em;
    background-color: #def8ff;
    padding: 10px 17px 14px;
}
</style>

<div id="license">
For example, you can install WPF (Licensed) setup and Windows (Trial) setup in same machine. But you can't install both Licensed and Trial WPF setup in the same machine.
</div>

If you install Licensed and Trial setup in the same machine, assemblies will conflict as both Licensed and Trial assemblies will be present in GAC. This will leads to licensing issues while development. To avoid this chaos, run the [Assembly Manager](https://help.syncfusion.com/common/essential-studio/utilities#assembly-manager) for the licensed setup after installing both Licensed and Trial setup.