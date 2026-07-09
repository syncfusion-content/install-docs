---
layout: post
title: Requirement to use Syncfusion with GitHub | Syncfusion
description: Learn the requirement for using Syncfusion Essential Studio license keys when publishing source code to GitHub or other public repositories.
platform: common
control: Essential Studio
documentation: ug
---

# Requirement to use Syncfusion<sup style="font-size:70%">&reg;</sup> with GitHub

When you use Syncfusion<sup style="font-size:70%">&reg;</sup> components and wish to push the source code to a public repository, or share the source project with clients, **you should not publicly push or provide the Syncfusion<sup style="font-size:70%">&reg;</sup> license keys along with the sources.** Push the source code without the Syncfusion<sup style="font-size:70%">&reg;</sup> license keys.

We recommend signing up with [Syncfusion<sup style="font-size:70%">&reg;</sup>](https://www.syncfusion.com/account/register) to obtain a trial or a valid license to use our products.

You may distribute the deployed applications, but you should not distribute the Syncfusion<sup style="font-size:70%">&reg;</sup> license keys in a public environment or through the source code.

## How to keep license keys out of source control

Use the following best practices to prevent license keys from being committed to your repository:

* **Externalize the key**: Load the license key from an environment variable, a user-secrets store, or a configuration file that is excluded from version control. For example, in a .NET application, retrieve the key at runtime:

    ```csharp
    // filepath: Program.cs
    Syncfusion.Licensing.SyncfusionLicenseProvider.RegisterLicense(
        Environment.GetEnvironmentVariable("SYNCFUSION_LICENSE_KEY"));
    ```

    Add any file that stores the key (for example, `appsettings.Development.json`) to `.gitignore`.

* **Use a secrets manager**: For production deployments, store the key in a secure store such as Azure Key Vault. See [How to securely store Syncfusion license keys in Azure Key Vault](how-to-securely-store-and-use-Syncfusion-License-Keys-in-Azure-Key-Vault.md).

* **Configure CI/CD securely**: Register the license key as a secret variable in your build pipeline so it is injected at build or run time and never committed to the repository.

## Related topics

* [How to generate a license key](https://help.syncfusion.com/common/essential-studio/licensing/how-to-generate)
* [How to register a license key in an application](https://help.syncfusion.com/common/essential-studio/licensing/how-to-register-in-an-application)
* [How to securely store Syncfusion license keys in Azure Key Vault](how-to-securely-store-and-use-Syncfusion-License-Keys-in-Azure-Key-Vault.md)

> **Note**: This licensing requirement applies to Syncfusion<sup style="font-size:70%">&reg;</sup> version 16.2.0.x and later. Earlier versions used the installer unlock key, which does not need to be excluded from source code.

