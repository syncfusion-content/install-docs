---
layout: post
title: About Essential Studio Licensing | Syncfusion
description: Learn here about Syncfusion Essential Studio license key, how to generate the license key, how to register the license key, and more details.
platform: common
control: Essential Studio
documentation: ug
---

<style>
#license {
    font-size: .88em!important;
margin-top: 1.5em;     margin-bottom: 1.5em;
    background-color: #fbefca;
    padding: 10px 17px 14px;
}
</style>


# Syncfusion Essential Studio Licensing Overview

We have introduced a new licensing system starting with version 16.2.0.x release of Essential Studio. These changes applicable to all evaluators and only to paid customers who use NuGet packages from [nuget.org](https://www.nuget.org/). Starting with v16.2.0.x, if you reference Syncfusion assemblies from evaluation installer or from the NuGet feed, you also must include its corresponding platform and version license key in your projects.

Please note that this license key is different from the installer unlock key that you might have used in the past and needs to be separately generated from Syncfusion website. Refer [this](https://www.syncfusion.com/kb/8950/difference-between-the-unlock-key-and-licensing-key) KB article to know more about difference between the Syncfusion Unlock Key and the Syncfusion License Key.

Following licensing error will be shown if the license key is not registered in your projects, while using assemblies from evaluation installer or from the nuget.org.

<div id="license">

This application was built using a trial version of Syncfusion Essential Studio. Please include a valid license to permanently remove this license validation message. You can also obtain a free 30 day evaluation license to temporarily remove this message during the evaluation period. Please refer to this <a href="/common/essential-studio/licensing/license-key">help topic</a> for more information 

</div>

If you are using File-Format libraries, trial message will be displayed as watermark in the generated documents.

**Example**

![IO Licensing Message](licensing-images/io-licensing-message.png)



N> This licensing system is not applicable for JavaScript (Essential JS 1 & Essential JS 2) script files (.js files). So, there is no need to apply license key anywhere in scripts or themes.
