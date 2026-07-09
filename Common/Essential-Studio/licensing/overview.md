---
layout: post
title: Overview of Syncfusion License Key - Syncfusion
description: Learn here about the Syncfusion license key, the difference between the license key and the unlock key, and how to register the license key in your application.
platform: common
control: Essential Studio
documentation: ug
---

<style>
#license {
    font-size: .88em !important;
    margin-top: 1.5em;
    margin-bottom: 1.5em;
    background-color: #fbefca;
    padding: 10px 17px 14px;
}
</style>


# Syncfusion<sup style="font-size:70%">&reg;</sup> Licensing Overview

Starting with the version 16.2.0.x release of Essential Studio<sup style="font-size:70%">&reg;</sup>, Syncfusion<sup style="font-size:70%">&reg;</sup> introduced a new licensing system. These modifications apply to all evaluators (trial users) and to paid customers who reference Syncfusion<sup style="font-size:70%">&reg;</sup> assemblies through the [nuget.org](https://www.nuget.org/) feed. Starting with v16.2.0.x, if you use the trial installer or the NuGet feed to reference Syncfusion<sup style="font-size:70%">&reg;</sup> assemblies, you must also include the corresponding platform (or edition, see below) and version license key in your projects.

> **Starting with v31.1.17 (2025 Volume 3 release),** Syncfusion<sup style="font-size:70%">&reg;</sup> introduced a new licensing model where license keys are generated **per edition** rather than per platform. The available editions are: Essential Studio UI Edition, Essential Studio Document SDK, Essential Studio PDF Viewer SDK, Essential Studio DOCX Editor SDK, Essential Studio Spreadsheet Editor SDK, and Essential Studio Enterprise Edition. See [How to Generate the License Key](https://help.syncfusion.com/common/essential-studio/licensing/how-to-generate) for details.

The [Syncfusion.Licensing](https://www.nuget.org/packages/Syncfusion.Licensing) NuGet package does not need to be added to your project individually. When you install any Syncfusion<sup style="font-size:70%">&reg;</sup> NuGet package from [nuget.org](https://www.nuget.org/) into your project, the Syncfusion.Licensing package is added automatically to the project dependencies. If it is not added, you can manually install the [Syncfusion.Licensing](https://www.nuget.org/packages/Syncfusion.Licensing) package from nuget.org.

## Difference between unlock key and license key

The **license key** is a runtime string registered in your application code (or configuration) to validate Syncfusion<sup style="font-size:70%">&reg;</sup> assemblies sourced from the trial installer or nuget.org. The **unlock key** is an older mechanism used by the Syncfusion<sup style="font-size:70%">&reg;</sup> installer to convert a trial installation into a licensed installation. The two are independent: a valid license key does not require an unlock key, and vice versa. Refer to [this KB article](https://www.syncfusion.com/kb/8950/difference-between-the-unlock-key-and-licensing-key) to learn more about the difference between the Syncfusion<sup style="font-size:70%">&reg;</sup> Unlock Key and the Syncfusion<sup style="font-size:70%">&reg;</sup> License Key.

The following licensing error is shown if the license key is not registered in your projects while using assemblies from the trial installer or from nuget.org.

<div id="license">

This application was built using a trial version of Syncfusion<sup style="font-size:70%">&reg;</sup> Essential Studio<sup style="font-size:70%">&reg;</sup>. You should include a valid license key to permanently remove this license validation message. You can also obtain a free 30-day evaluation license key to temporarily remove this message during the evaluation period. Please refer to this <a href="/common/essential-studio/licensing/overview">help topic</a> for more information.

</div>

If you are using the File-Format libraries, a trial watermark is displayed in the generated documents until a valid license key is registered.

**Example:** Trial watermark rendered in a generated PDF document.

![IO Licensing Message](licensing-images/io-licensing-message.png)

## Registering the license key in your application

The license key is a runtime string that must be registered before any Syncfusion<sup style="font-size:70%">&reg;</sup> control is initialized. A minimal registration call is shown below.

**Registering a single license key (C#)**

```csharp
Syncfusion.Licensing.SyncfusionLicenseProvider.RegisterLicense("YOUR_LICENSE_KEY");
```

Starting with v31.1.17, if your application uses components from multiple editions (for example, the UI Edition **and** the PDF Viewer SDK), register each generated license key. Refer to [How to Register the License Key in the Application](https://help.syncfusion.com/common/essential-studio/licensing/how-to-register-in-an-application) for the complete set of platforms (ASP.NET Core, Blazor, JavaScript, Java, etc.) and placement guidance (startup, Main, appsettings.json, environment variable).

## Registering Syncfusion<sup style="font-size:70%">&reg;</sup> license keys in a build server

| Source of Syncfusion<sup style="font-size:70%">&reg;</sup> assemblies | Details | License key needs to be registered? | Where to get the license key from |
| ------------- | ------------- | ------------- | ------------- |
| **NuGet package** | If the Syncfusion<sup style="font-size:70%">&reg;</sup> assemblies used in the build server are obtained from Syncfusion<sup style="font-size:70%">&reg;</sup> NuGet packages, you do not need to install any Syncfusion<sup style="font-size:70%">&reg;</sup> installer. Reference the required Syncfusion<sup style="font-size:70%">&reg;</sup> NuGet packages directly from [nuget.org](https://www.nuget.org/). When using NuGet packages from [nuget.org](https://www.nuget.org/packages?q=syncfusion), register the Syncfusion<sup style="font-size:70%">&reg;</sup> license key in the application. | Yes | Use any developer license to [generate](https://help.syncfusion.com/common/essential-studio/licensing/how-to-generate) keys for build environments. |
| **Trial installer** | If the Syncfusion<sup style="font-size:70%">&reg;</sup> assemblies used in the build server are obtained from the trial installer, register the license key in the application for the corresponding version and platform to avoid the trial license warning. | Yes | Use any developer trial license to [generate](https://help.syncfusion.com/common/essential-studio/licensing/how-to-generate) keys for build environments. |
| **Licensed installer** | If the Syncfusion<sup style="font-size:70%">&reg;</sup> assemblies used in the build server are obtained from the licensed installer, you do not need to register the license keys. You can [download](https://help.syncfusion.com/common/essential-studio/installation/web-installer/how-to-download#download-the-license-version) and [install](https://help.syncfusion.com/common/essential-studio/installation/web-installer/how-to-install) the licensed version of our installer. | No | Not applicable |

> If the build server uses assemblies from more than one source (for example, NuGet packages **and** the licensed installer), register the license key only if NuGet packages are referenced. The licensed installer does not require a runtime license key.

## See Also

* [How to Generate Syncfusion<sup style="font-size:70%">&reg;</sup> Essential Studio<sup style="font-size:70%">&reg;</sup> License Key](https://help.syncfusion.com/common/essential-studio/licensing/how-to-generate)
* [How to Register Syncfusion<sup style="font-size:70%">&reg;</sup> License Key in the Application](https://help.syncfusion.com/common/essential-studio/licensing/how-to-register-in-an-application)
* [Syncfusion<sup style="font-size:70%">&reg;</sup> Licensing Errors and Resolutions](licensing-errors.md)
