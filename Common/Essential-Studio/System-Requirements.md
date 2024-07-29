---
layout: post
title: System Requirements of Essential Studio | Syncfusion
description: Learn here about the information of the system requirements for each platform with supported browsers.
platform: common
control: Essential Studio
documentation: ug
---

# System Requirements of Essential Studio

<style>
#note {
    font-size: .88em!important;
margin-top: 1.5em;     margin-bottom: 1.5em;
    background-color: #def8ff;
    padding: 10px 17px 14px;
}
</style>

## ASP.NET MVC

To get started with an ASP.NET MVC application, the following software must be installed on the machine.

### Operating Systems

* Windows 7 SP1
* Windows 8, 8.1
* Windows 10
* Windows 11
* Android 4.1 & later
* iOS 9 & later

### Hardware Environment

* Processor: x86 or x64
* RAM : 512 MB (minimum), 1 GB (recommended)
* Hard disk: up to 3 GB of available space may be required

### Integrated Development Environment (IDE)

By using the following IDEs, you can develop ASP.NET MVC Applications

* [Visual Studio 2017](https://visualstudio.microsoft.com/vs/older-downloads/)
* [Visual Studio 2019](https://visualstudio.microsoft.com/downloads/)
* [Visual Studio 2022](https://visualstudio.microsoft.com/downloads/)

### Frameworks & SDK

The tools listed below are required to run the Syncfusion ASP.NET MVC UI application.

* .NET Framework 4.5 or above.
* ASP.NET MVC 4 or ASP.NET MVC 5

### Browser support and Required Polyfills

#### Browser support

The Syncfusion Essential JS 2 components are supported only in modern browsers. This includes the following versions.

<table>
<tr>
<th>Chrome</th>
<th>Firefox</th>
<th>Opera</th>
<th>Edge</th>
<th>IE</th>
<th>Safari</th>
<th>iOS</th>
<th>Android</th>
<th>Windows Mobile</th>
</tr>
<tr>
<td>Latest</td>
<td>Latest</td>
<td>Latest</td>
<td>13 +</td>
<td>11 +</td>
<td>9 +</td>
<td>9 +</td>
<td>4.4 +</td>
<td>IE 11 +</td>
</tr></table>

#### Required Polyfills

The following polyfills are required to run Essential JS 2 components in each browser.

<table>
<tr>
<th>Browser</th>
<th>Polyfills</th></tr>
<tr>
<td>Chrome(latest), Firefox(latest), Opera(latest), Edge, Safari 9+</td>
<td>NONE</td>
</tr>
<tr>
<td>IE 11</td>
<td>ES6 Promise</td>
</tr>
</table>

The Syncfusion Essential JS 2 components are supported in IE 11 browser with ES6 Promise polyfills.

### Using CDN

{% tabs %}

<!-- Automatically provides/replaces `Promise` if missing or broken. -->
<script src="https://cdn.jsdelivr.net/npm/es6-promise@4/dist/es6-promise.js"></script>
<script src="https://cdn.jsdelivr.net/npm/es6-promise@4/dist/es6-promise.auto.js"></script>
<!-- Minified version of `es6-promise-auto` below. -->
<script src="https://cdn.jsdelivr.net/npm/es6-promise@4/dist/es6-promise.min.js"></script>
<script src="https://cdn.jsdelivr.net/npm/es6-promise@4/dist/es6-promise.auto.min.js"></script>

{% endtabs %}

Refer this [link](https://github.com/stefanpenner/es6-promise) for more details.

## ASP.NET Core

To get started with an ASP.NET Core application, the following software must be installed on the machine.

### Operating Systems

* Windows 7 SP1
* Windows 8, 8.1
* Windows 10
* Windows 11
* Android 4.1 & later
* iOS 9 & later

### Hardware Environment

* Processor: x86 or x64
* RAM : 512 MB (minimum), 1 GB (recommended)
* Hard disk: up to 3 GB of available space may be required

### Integrated Development Environment (IDE)

By using the following IDEs, you can develop ASP.NET Core Applications

* [Visual Studio 2017](https://visualstudio.microsoft.com/vs/older-downloads/) 
* [Visual Studio 2019](https://visualstudio.microsoft.com/downloads/)
* [Visual Studio 2022](https://visualstudio.microsoft.com/downloads/)
* [Visual Studio Code](https://code.visualstudio.com/)

### Frameworks & SDK

The below tool is required to run the Syncfusion UI controls for ASP.NET Core application.

* [.NET Core SDK 2.1](https://dotnet.microsoft.com/en-us/download/dotnet/2.1) / [.NET Core SDK 3.1](https://dotnet.microsoft.com/en-us/download/dotnet/3.1) / [.NET 5.0 SDK](https://dotnet.microsoft.com/en-us/download/dotnet/5.0)


<div id="note">
.NET Core SDK 3.1 requires Visual Studio 2019 16.4 or later
.NET 5.0 requires Visual Studio 2019 16.8 or later.
</div>

### Browser support and Required Polyfills

#### Browser support

The Syncfusion Essential JS 2 components are supported only in modern browsers. This includes the following versions.

<table>
<tr>
<th>Chrome</th>
<th>Firefox</th>
<th>Opera</th>
<th>Edge</th>
<th>IE</th>
<th>Safari</th>
<th>iOS</th>
<th>Android</th>
<th>Windows Mobile</th>
</tr>
<tr>
<td>Latest</td>
<td>Latest</td>
<td>Latest</td>
<td>13 +</td>
<td>11 +</td>
<td>9 +</td>
<td>9 +</td>
<td>4.4 +</td>
<td>IE 11 +</td>
</tr></table>

#### Required Polyfills

The following polyfills are required to run Essential JS 2 components in each browser. 

<table>
<tr>
<th>Browser</th>
<th>Polyfills</th></tr>
<tr>
<td>Chrome(latest), Firefox(latest), Opera(latest), Edge, Safari 9+</td>
<td>NONE</td>
</tr>
<tr>
<td>IE 11</td>
<td>ES6 Promise</td>
</tr>
</table>

The Syncfusion Essential JS 2 components are supported in IE 11 browser with ES6 Promise polyfills.

### Using CDN

To add ES6 Promise polyfills using CDN, include this in your HTML file.

{% tabs %}

<!-- Automatically provides/replaces `Promise` if missing or broken. -->
<script src="https://cdn.jsdelivr.net/npm/es6-promise@4/dist/es6-promise.js"></script>
<script src="https://cdn.jsdelivr.net/npm/es6-promise@4/dist/es6-promise.auto.js"></script>
<!-- Minified version of `es6-promise-auto` below. -->
<script src="https://cdn.jsdelivr.net/npm/es6-promise@4/dist/es6-promise.min.js"></script>
<script src="https://cdn.jsdelivr.net/npm/es6-promise@4/dist/es6-promise.auto.min.js"></script>

{% endtabs %}

Refer this [link](https://github.com/stefanpenner/es6-promise) for more details.

## JavaScript

To get started with JavaScript application, the following software must be installed on the machine.

### Operating Systems

* Windows 11
* Windows 10
* Windows 8, 8.1
* Windows 7
* Windows vista
* Windows server 2008 and later
* Linux
* Unix
* Mac

### Hardware Environment

* Processor: x86 or x64
* RAM : 512 MB (minimum), 1 GB (recommended)
* Hard disk: up to 3 GB of available space may be required

### Integrated Development Environment (IDE)

By using the following IDEs, you can develop JavaScript applications

* [Visual Studio Code](https://code.visualstudio.com/download)
* Any text editors such as Notepad or Notepad++.

### Development Environment

* [Node.js](https://nodejs.org/en/)
* Web browsers with [JavaScript](https://support.microsoft.com/en-in/gp/howtoscript) enabled in it. 

### Browser support and Required Polyfills

#### Browser support

The Syncfusion Essential JS 2 components are supported only in modern browsers. This includes the following versions.

<table>
<tr>
<th>Chrome</th>
<th>Firefox</th>
<th>Opera</th>
<th>Edge</th>
<th>IE</th>
<th>Safari</th>
<th>iOS</th>
<th>Android</th>
<th>Windows Mobile</th>
</tr>
<tr>
<td>63+</td>
<td>58+</td>
<td>50+</td>
<td>13 +</td>
<td>11 +</td>
<td>9 +</td>
<td>9 +</td>
<td>4.4 +</td>
<td>IE 11 +</td>
</tr></table>

#### Required Polyfills

The following polyfills are required to run Essential JS 2 components in each browser. 

<table>
<tr>
<th>Browser</th>
<th>Polyfills</th></tr>
<tr>
<td>Chrome(latest), Firefox(latest), Opera(latest), Edge, Safari 9+</td>
<td>NONE</td>
</tr>
<tr>
<td>IE 11</td>
<td>ES6 Promise</td>
</tr>
</table>

The Syncfusion Essential JS 2 components are supported in IE 11 browser with ES6 Promise polyfills.

### Using CDN

To add ES6 Promise polyfills using CDN, include this in your HTML file.

{% tabs %}

<!-- Automatically provides/replaces `Promise` if missing or broken. -->
<script src="https://cdn.jsdelivr.net/npm/es6-promise@4/dist/es6-promise.js"></script>
<script src="https://cdn.jsdelivr.net/npm/es6-promise@4/dist/es6-promise.auto.js"></script>
<!-- Minified version of `es6-promise-auto` below. -->
<script src="https://cdn.jsdelivr.net/npm/es6-promise@4/dist/es6-promise.min.js"></script>
<script src="https://cdn.jsdelivr.net/npm/es6-promise@4/dist/es6-promise.auto.min.js"></script>

{% endtabs %}

### Node.js

ES6 Promise polyfills can also be installed in Node.js

**To install:**

{% tabs %}
yarn add es6-promise
(or)
npm install es6-promise
{% endtabs %}

** To use:**

{% tabs %}
var Promise = require('es6-promise').Promise;
{% endtabs %}

Refer this [link](https://github.com/stefanpenner/es6-promise) for more details.

## Blazor

To learn more about Blazor system requirements, see, this [documentation](https://blazor.syncfusion.com/documentation/system-requirements).


## Windows Forms

The system requirements for using our Syncfusion Windows Forms platform are as follows.

### Operating Systems

* Windows 2000
* Windows XP
* Windows Vista
* Windows 7
* Windows 8
* Windows 10
* Windows 11
* Windows Server (from 2003 to latest)


### Hardware Environment

* Processor: x86 or x64
* RAM : 512 MB (minimum), 1 GB (recommended)
* Hard disk: up to 4 GB of space may be required. However, even if you install in a different drive, 400 MB of free space is required in the boot drive.

### Development Environment

* Microsoft Visual Studio 2008/2010/2012/2013/2015/2017/2019/2022
* .NET Framework 2.0/3.5/4.0/4.5/4.5.1/4.6
* Lower Syncfusion .NET frameworks can be used in applications because they are compatible with .NET 4.7, .NET 4.7.1, .NET 4.7.2, and .NET 4.8. For example, in the application, the Syncfusion 4.6 .NET framework assembly can be referred to as 4.7 or higher target versions.
* .NET Core supported from [2019 Volume 1 release](https://help.syncfusion.com/windowsforms/release-notes) (17.1.0.32).

## WPF

The system requirements for using our Syncfusion WPF platform are as follows.

### Operating Systems

* Windows XP
* Windows Vista SP2
* Windows 7 SP1
* Windows 8, 8.1
* Windows 10
* Windows 11


### Hardware Environment

* Processor: x86 or x64
* RAM : 512 MB (minimum), 1 GB (recommended)
* Hard disk: up to 3 GB of available space may be required

### Development Environment

* Microsoft Visual Studio 2008/2010/2012/2013/2015/2017/2019/2022
* .NET Framework 2.0/3.5/4.0/4.5/4.5.1/4.6
* .NET Core 3.1
* .NET 5.0

## Universal Windows Platform

The following topic describes the system requirements required by Syncfusion Universal Windows Platform.

### Operating Systems

* Windows 11
* Windows 10

### Hardware Environment

* Processor: x86 or x64
* RAM : 512 MB (minimum), 1 GB (recommended)
* Hard disk: up to 3 GB of available space may be required

### Development Environment

The following IDEs can be used for development that are [compatible](https://www.visualstudio.com/en-us/products/visual-studio-2015-compatibility-vs.aspx) with Microsoft Windows, both 32bit and 64 bit Operating System in Windows 11, Windows 10 and Windows 8.1 with Windows 10 toolkit

* Microsoft Visual Studio 2015/2017/2019/2022
* Windows 10 SDK and later

### Framework

The following frameworks are supported:

* Microsoft .NET Framework 4.6


## WinUI

The system requirements for using our Syncfusion WinUI platform are as follows.

### Operating Systems

* Windows 11 and Windows 10, version 1809 (build 17763) or later.

### Development Environment

* [Visual Studio 2019, version 16.10 Preview](https://visualstudio.microsoft.com/vs/preview/) (or later) with following components. 
* [Visual Studio 2022](https://visualstudio.microsoft.com/downloads/)
* <b>Universal Windows Platform development</b> of the <b>Workloads</b> tab of the installation dialog.  
* <b>Windows 10 SDK (10.0.19041.0) and later</b> on <b>Individual components</b> tab of the installation dialog.
* [Project Reunion 0.5 extension](https://marketplace.visualstudio.com/items?itemName=ProjectReunion.MicrosoftProjectReunion)

N> Visual Studio 2019, version 16.9 also supports Project Reunion and it does not support all WinUI 3 tooling features such as Hot Reload, Live Visual Tree, etc. Refer [Windows UI Library 3 - Project Reunion 0.5](https://docs.microsoft.com/en-us/windows/apps/winui/winui3/) to know more about WinUI 3 tooling support.


{% seealso %}

[How to set up your WinUI Project Reunion development environment](https://docs.microsoft.com/en-us/windows/apps/windows-app-sdk/set-up-your-development-environment?tabs=visual-studio-2019) in Microsoft Docs.

{% endseealso %}

## .NET MAUI

The system requirements for using our Syncfusion .NET MAUI platform are as follows.

### Operating Systems

* Windows 11 and Windows 10, version 1909 or higher.

### Hardware Environment

* Processor: x86 or x64
* RAM : 512 MB (minimum), 1 GB (recommended)
* Hard disk: up to 3 GB of available space may be required

### Development Environment

* [Visual Studio 2022, version 3.1 Preview](https://visualstudio.microsoft.com/vs/preview/) (or later) with following components. 
* <b>.NET MAUI Platform development</b> of the <b>[Workloads](https://docs.microsoft.com/en-us/dotnet/maui/get-started/installation)</b>

## Xamarin

The system requirements for using our Syncfusion Xamarin platform are as follows.

### Operating Systems

* Windows XP
* Windows Vista SP2
* Windows 7 SP1
* Windows 8, 8.1
* Windows 10
* Windows 11
* Android 4.1 & later
* iOS 9 & later

### Hardware Environment

* Processor: x86 or x64
* RAM : 512 MB (minimum), 1 GB (recommended)
* Hard disk: up to 3 GB of available space may be required

### Xamarin.Forms

#### Development Environment

See the link below for the recommended Xamarin development environments
 
[System Requirements - Xamarin](https://docs.microsoft.com/en-us/xamarin/cross-platform/get-started/requirements)

#### Supported Platforms

The platforms supported by our Xamarin.Forms controls are listed in the table below.

<table>
    <tr>
        <th>Platform<br/>
            <br/></th>        
        <th>
          Device Types
            <br/>
            <br/>
        </th>
          <th>
            Controls
            <br/>
            <br/>
        </th>
        <th>
            Supported versions
            <br/>
            <br/>
        </th>
    </tr>
    <tr>
        <td rowspan="2">
            Android
            <br/>
            <br/>
        </td>
        <td rowspan="2">
        Phone, Tablet
        <br/>
        <br/>
        </td>
        <td>
            SfPdfViewer, SfCheckBox and Material theme support
            <br/>
            <br/>
        </td>
         <td>
            API level 21 and later versions
            <br/>
            <br/>
        </td>
    </tr>
     <tr>
        <td>
            All other controls 
            <br/>
            <br/>
        </td>
         <td>
            API level 19 and later versions
            <br/>
            <br/>
        </td>
    </tr>
    <tr>
        <td>
            iOS
            <br/>
            <br/>
        </td>
        <td>
            iPhone, iPod, iPad
            <br/>
            <br/>
        </td>
          <td>
            All controls 
            <br/>
            <br/>
        </td>
        <td>
            iOS 9.0 and later versions
            <br/>
            <br/>
        </td>
    </tr>
    <tr>
        <td>
            UWP
            <br/>
            <br/>
        </td>
        <td>
           Desktop, Tablet
            <br/>
            <br/>
        </td>
          <td>
            All controls
            <br/>
            <br/>
        </td>
        <td>
            Windows 10 and later
            <br/>
            <br/>
        </td>
    </tr>
<td>
            macOS
            <br/>
            <br/>
        </td>
        <td>
            iMac, Mac book, Mac mini
             <br/>
             <br/>
        </td>
        <td>
            SfChart, SfDataGrid and SfListView
            <br/>
            <br/>
        </td>
         <td>
            macOS 10.11 and later versions
            <br/>
            <br/>
        </td>
    <tr>
        <td>
            WPF
            <br/>
            <br/>
        </td>
        <td>
           Desktop
            <br/>
            <br/>
        </td>
          <td>
            SfChart, SfDataGrid, SfListView, SfSchedule, SfBorder, SfButton, SfChip, SfSwitch, SfRadioButton, SfCheckBox, SfGradientView, SfSegmentedControl, SfTextInputLayout
            <br/>
            <br/>
        </td>
        <td>
            Windows 10 and later
            <br/>
            <br/>
        </td>
    </tr>
    
</table>

#### Target Framework (Compile SDK Version) for Android

The target framework or compile SDK version of the application for the Android platform should be equal to or greater than the latest API available at the time of our release. More information on setting the target framework can be found at the following link.

 [https://docs.microsoft.com/en-us/xamarin/android/app-fundamentals/android-api-levels?tabs=windows#target-framework](https://docs.microsoft.com/en-us/xamarin/android/app-fundamentals/android-api-levels?tabs=windows#target-framework)

### Xamarin.Android

#### Development Environment

See the link below for the recommended Xamarin development environments

[https://docs.microsoft.com/en-us/xamarin/cross-platform/get-started/requirements](https://docs.microsoft.com/en-us/xamarin/cross-platform/get-started/requirements)

#### Supported Platforms

The following table lists the platforms supported by our Xamarin.Android controls.

<table>
    <tr>
        <th>Platform<br/>
            <br/></th>        
        <th>
          Device Types
            <br/>
            <br/>
        </th>
          <th>
            Controls
            <br/>
            <br/>
        </th>
        <th>
            Supported versions
            <br/>
            <br/>
        </th>
    </tr>
    <tr>
        <td rowspan="2">
            Android
            <br/>
            <br/>
        </td>
        <td rowspan="2">
        Phone, Tablet
        <br/>
        <br/>
        </td>
        <td>
            SfPdfViewer, SfCheckBox
            <br/>
            <br/>
        </td>
         <td>
            API level 21 and later versions
            <br/>
            <br/>
        </td>
    </tr>
     <tr>
        <td>
            All other controls 
            <br/>
            <br/>
        </td>
         <td>
            API level 19 and later versions
            <br/>
            <br/>
        </td>
    </tr>
</table>

#### Target Framework (Compile SDK Version) for Android

The target framework or compile SDK version of the application for the Android platform should be equal to or greater than the latest API available at the time of our release. More information on setting the target framework can be found at the following link.

 [https://docs.microsoft.com/en-us/xamarin/android/app-fundamentals/android-api-levels?tabs=windows#target-framework](https://docs.microsoft.com/en-us/xamarin/android/app-fundamentals/android-api-levels?tabs=windows#target-framework)
 
### Xamarin.iOS
 
#### Development Environment

See the link below for the recommended Xamarin development environments

[https://docs.microsoft.com/en-us/xamarin/cross-platform/get-started/requirements](https://docs.microsoft.com/en-us/xamarin/cross-platform/get-started/requirements)

#### Supported Platforms

<table>
    <tr>
        <th>Platform<br/>
            <br/></th>        
        <th>
          Device Types
            <br/>
            <br/>
        </th>
          <th>
            Controls
            <br/>
            <br/>
        </th>
        <th>
            Supported versions
            <br/>
            <br/>
        </th>
    </tr>
	<tr>
        <td>
            iOS
            <br/>
            <br/>
        </td>
        <td>
            iPhone, iPod, iPad
            <br/>
            <br/>
        </td>
          <td>
            All controls 
            <br/>
            <br/>
        </td>
        <td>
            iOS 9.0 and later versions
            <br/>
            <br/>
        </td>
    </tr>
</table>

## Flutter

The system requirements for using our Syncfusion Flutter platform are as follows

### Operating Systems

* Windows 7 SP1
* Windows 8, 8.1
* Windows 10
* Windows 11
* Android API level 16 & later
* iOS 8 & later

### Hardware Environment

* Processor: x86 or x64
* RAM : 512 MB (minimum), 1 GB (recommended)
* Hard disc: up to 3 GB of free space will be required.

### Development Environment

See the links below for the recommended Flutter development environments

* Windows - [`https://flutter.dev/docs/get-started/install/windows`](https://flutter.dev/docs/get-started/install/windows)
* MacOS - [`https://flutter.dev/docs/get-started/install/macos`](https://flutter.dev/docs/get-started/install/macos)
* Linux - [`https://flutter.dev/docs/get-started/install/linux`](https://flutter.dev/docs/get-started/install/linux)

### SDK Version

The following Flutter SDK version is required for our widgets:

<table>
    <tr>
        <th>Channel</th>
        <th>Version</th>
    </tr>
    <tr>
        <td>Stable</td>
        <td style="text-align:center">
            <a href="https://storage.googleapis.com/flutter_infra/releases/stable/windows/flutter_windows_2.0.0-stable.zip">v2.0.0</a>
        </td>
    </tr>
    <tr>
        <td>Beta</td>
        <td style="text-align:center">
            <a href="https://storage.googleapis.com/flutter_infra/releases/beta/windows/flutter_windows_2.0.0-beta.zip">v2.0.0</a>
        </td>
    </tr>
</table>

### Supported Platforms

Our Flutter packages are compatible with iOS, Android, Web, Windows, macOS, and Linux. You can find the supported version at the link below.

[`https://flutter.dev/docs/development/tools/sdk/release-notes/supported-platforms#supported-platforms`](https://flutter.dev/docs/development/tools/sdk/release-notes/supported-platforms#supported-platforms)
