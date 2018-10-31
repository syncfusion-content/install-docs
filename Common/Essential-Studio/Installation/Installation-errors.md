---
layout: post
title: Installation-faq | common | Syncfusion
description: essential studio mac installer
platform: common
control: Essential Studio
documentation: ug
---

# Installation Errors

This article lists the common Installation errors, reasons and solution for those errors.

* [Could not unlock the Licensed setup with Trial key?](https://help.syncfusion.com/common/essential-studio/installation/installation-errors#could-not-unlock-the-licensed-setup-with-trial-key)
* [Licensed Expired! What to do?](https://help.syncfusion.com/common/essential-studio/installation/installation-errors#licensed-expired-what-to-do)
* [Not a Valid license holder?](https://help.syncfusion.com/common/essential-studio/installation/installation-errors#not-a-valid-license-holder)
* [Could not install the setup due to another installation?](https://help.syncfusion.com/common/essential-studio/installation/installation-errors#could-not-install-the-setup-due-to-another-installation)

### Could not the unlock Licensed setup with Trial key?

#### Problem

**Error Message:** Sorry, the provided unlock key is a trial key and cannot be used to unlock the licensed version of our Essential Studio for {platform} setup

![Alert Message](Errors/Installation_Errors_img1.png)

#### Reason

If you unlocked the Licensed setup with Trial key, this error message will be shown.

#### Suggested solution

Licensed setup can be unlocked only by License key. So, use the License key to unlock the Licensed setup. Refer [this](http://syncfusion.com/kb/2326) topic to generate the license key.


### Licensed Expired! What to do?

#### Problem

**Error Message:** Your license for Syncfusion Essential Studio for {platform} has been expired since {date}. Please renew your subscription and try again

**Online Installer**

![Warning Message](Errors/Installation_Errors_img2.png)

#### Reason

This error message will be shown when your license has been expired.

#### Suggested solution.

Renew the subscription [here](https://www.syncfusion.com/sales/products) or contact our sales team at <salessupport@syncfusion.com>. Also, you can continue the 30 days trial after your license has been expired.


### Not a Valid license holder?

#### Problem

**Error Message:** Sorry, we were unable to find a valid license for Essential Studio for {platform} under your account.

![Alert Message](Errors/Installation_Errors_img3.png)

#### Reason

The possible reasons for this error are:

* When your trial expired
* When you don't have License or trial

#### Suggested solution.

Renew the subscription [here](https://www.syncfusion.com/sales/products) or contact our sales team at <salessupport@syncfusion.com>.

### Could not install the setup due to another installation?

#### Problem

**Error Message:** Another installation is in progress. You cannot complete this installation without completing all other currently active installations. Click cancel to end this setup, or retry to attempt to install again.

![Warning Message](Errors/Installation_Errors_img4.png)

#### Reason

This error message will be shown when another installation is already running in your machine. 

#### Suggested solution.

Open the Task Manager and kill the msiexec process and then continue the Syncfusion installation. If still the problem persists, restart the machine and try installing Syncfusion setup.

1. Open the Windows Task Manager.

2. Navigate to the Details tab.

3. Select the msiexec.exe and click **End task**.

![Task Manager](Errors/Installation_Errors_img5.png)






