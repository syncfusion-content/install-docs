---
layout: post
title: Security Advisory in Syncfusion Controls - Syncfusion
description: Learn here about security updates available for Syncfusion controls for volume release..
platform: common
control: Essential Studio
documentation: ug
---

# Security Advisory in Syncfusion Essential JS2 Controls

Syncfusion places the utmost priority on the security of our controls. Users can rest assured about the security of our controls, as we have implemented all necessary measures to mitigate security vulnerabilities such as cross-site scripting and insecure dependencies. To meet security standards, Syncfusion utilizes the [ESLint](https://eslint.org/) and [ESLint plugin security](https://github.com/eslint-community/eslint-plugin-security#rules) tools for static code analysis. Additionally, Syncfusion packages undergo software composition analysis using the [SOOS](https://soos.io/) security tool.

This document provides a description of the security updates available for Syncfusion Essential JS2 controls for volume release.

## Security Updates

The following security updates are available for Syncfusion Essential JS2 controls and are listed based on the release version.

### 2023 Volume 2 (v22.1.34) - June 21, 2023

The Content Security Policy for Syncfusion controls has been enhanced by eliminating the usage of unsafe-eval directive. This ensures compliance with strict Content Security Policy (CSP) guidelines and improves the overall security of Syncfusion controls.

**Threat:**

The unsafe-eval directive is a CSP directive that allows the use of eval(). This directive is used to execute the code from strings, which is a potential security risk.

**Resolution:**

Starting from the release (v22.1.34), Syncfusion has removed the usage of the unsafe-eval directive in the CSP meta tag by implementing a [function template](https://ej2.syncfusion.com/documentation/common/template#function-template) approach for template properties. This change will prevent the execution of code from strings and further improve the overall security of Syncfusion controls.

For more information about the Content Security Policy, refer to this [documentation](https://ej2.syncfusion.com/documentation/common/troubleshoot/content-security-policy).

### 2019 Volume 4 (v17.4.39) - December 17, 2019

An HTML Sanitizer has been implemented to prevent cross-site scripting (XSS) attacks in Syncfusion controls. This ensures that the data rendered in the controls is safe and secure.

**Threat:**

Cross-Site Scripting (XSS) is a vulnerability where attackers inject malicious code into a web application, typically using JavaScript, but it could also involve HTML or CSS. Some Syncfusion controls accept user input values, including HTML strings.

**Resolution:**

To mitigate this threat, we have introduced the sanitize method in the Syncfusion JavaScript base library. This method sanitizes user input HTML strings before rendering them in the control. We recommend utilizing this method to prevent Cross-Site Scripting vulnerabilities. For example, refer to the following code snippet.

{% tabs %}
{% highlight JS %}
import { SanitizeHtmlHelper } from ‘@syncfusion/ej2-base’;
let html: string = ’
’;
let sanitizedHtml: string = SanitizeHtmlHelper.sanitize(html);
{% endhighlight %}
{% endtabs %}

## Security Issue

If users discover any security issues or need assistance in resolving them with Syncfusion controls, please contact us by creating a support ticket on our [support site](https://www.syncfusion.com/support).
