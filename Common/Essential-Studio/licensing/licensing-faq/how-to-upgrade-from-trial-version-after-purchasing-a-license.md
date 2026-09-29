---
layout: post
title: Upgrade from Trial Version After Purchasing a License | Syncfusion
description: Learn here about upgrading from the trial version of Essential Studio to the licensed version, with steps for installer-based and NuGet-based references.
platform: common
control: Essential Studio
documentation: ug
---

# How to Upgrade from Trial Version After Purchasing a License?

To upgrade from the trial version of Essential Studio, there are two possible options. Choose the option that matches how your project references Syncfusion<sup style="font-size:70%">&reg;</sup> assemblies: the installer (machine-wide install) or NuGet (per-project packages).

**Before you begin**

- Ensure you have a valid paid license key. Generate one from the [License & Downloads](https://www.syncfusion.com/account/downloads) page (open the **License Keys** tab for your active subscription).
- If you reference Syncfusion<sup style="font-size:70%">&reg;</sup> from a trial installer, locate the installed version in **Control Panel → Programs and Features**.
- If you use NuGet, ensure the [Syncfusion.Licensing](https://www.nuget.org/packages/Syncfusion.Licensing) package is referenced in your project.

## Option 1: Installer-based reference

1. Uninstall the trial build of Essential Studio<sup style="font-size:70%">&reg;</sup> from **Control Panel → Programs and Features** (or **Settings → Apps** on Windows 10/11).
2. Sign in to your account on the [License & Downloads](https://www.syncfusion.com/account/downloads) page and download the licensed installer that matches your platform.
3. Run the licensed installer. The installer automatically registers the paid license machine-wide, so no per-project license registration is required.
4. Open your existing projects and verify that assembly references still point to the new install path. The licensed installer updates the common reference path used by Syncfusion<sup style="font-size:70%">&reg;</sup> controls, so most projects compile without manual changes.
5. Clean and rebuild your solution to refresh the output (`bin`/`obj`) folders.

## Option 2: NuGet-based reference

1. Remove the existing trial license key from your project's startup code or configuration file (for example, `App.xaml.cs`, `Program.cs`, `web.config`, `app.config`, or `appsettings.json`).
2. Generate a paid license key for the correct version and platform from the [License & Downloads](https://www.syncfusion.com/account/downloads) page.
3. Register the paid license key in your application as described in [this](https://help.syncfusion.com/common/essential-studio/licensing/how-to-register-in-an-application) topic. Registration locations vary by platform: WinForms/WPF use `App()`/`Program.cs`; ASP.NET uses `web.config`; ASP.NET Core uses `appsettings.json`; Xamarin/MAUI use the platform startup method.
4. Update the [Syncfusion.Licensing](https://www.nuget.org/packages/Syncfusion.Licensing) NuGet package to the latest version, then clean the solution (`bin` and `obj` folders) and rebuild.
5. Run the application and confirm the licensing warning is no longer displayed.

> **Note:** License registration is not required if you reference Syncfusion<sup style="font-size:70%">&reg;</sup> assemblies from the **Licensed installer** — it injects a machine-level license at install time. The license registration steps above apply to evaluators who reference the Syncfusion<sup style="font-size:70%">&reg;</sup> assemblies from the **evaluation installer**, and to developers who use the Syncfusion<sup style="font-size:70%">&reg;</sup> NuGet packages from [nuget.org](https://www.nuget.org/packages?q=syncfusion).

## Related topics

- [Licensing overview](https://help.syncfusion.com/common/essential-studio/licensing/overview)
- [How to generate a license key](https://help.syncfusion.com/common/essential-studio/licensing/how-to-generate)
- [How to register a license key in an application](https://help.syncfusion.com/common/essential-studio/licensing/how-to-register-in-an-application)
- [Licensing errors](https://help.syncfusion.com/common/essential-studio/licensing/licensing-errors)