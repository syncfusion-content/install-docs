---
layout: post
title: Licensing FAQ – How to securely store and use Syncfusion License Keys in Azure Key Vault | Syncfusion
description: Learn here some information about to securely store and use Syncfusion License Keys in Azure Key Vault.
platform: common
control: Essential Studio
documentation: ug
---

# How to securely store and use Syncfusion License Keys in Azure Key Vault?

You can store the Syncfusion license key in azure key vaults and register it in your application.

To use the secrets stored in Azure Key Vault in your application, you can follow these general steps:

1.	Create an Azure Key Vault and add your secrets (Syncfusion License Key) to it.

2.	Grant your application access to the Key Vault and the secrets it needs.

3.	Modify your application code to retrieve the secrets from the Key Vault.

Here's a more detailed breakdown of each step:


**Create an Azure Key Vault and add your secrets to it:**

![Azue Key Vault](licensing-images/azure-key-vault1.png)

a. Sign in to the Azure portal and navigate to the Key Vault service.

b. Create a new Key Vault or select an existing one.

c. Add the secrets (**Here Syncfusion License Key**) to the Key Vault, using either the Azure portal or the Azure CLI. When adding a secret, make sure to give it a descriptive name and a value that is as secure as possible.

![Azue Key Vault](licensing-images/azure-key-vault2.png)


**Grant your application access to the Key Vault and the secrets it needs:**

![Azue Key Vault](licensing-images/azure-key-vault3.png)

a. In the Key Vault settings, add an access policy for your application. This policy will define the permissions that your application has for accessing secrets in the Key Vault.

b. If you're using an Azure-hosted application, you can assign an Azure Managed Identity to your application and use it to access the Key Vault. This is a secure way to authenticate your application without having to manage any credentials. 

Refer to the below documentation for access to the policy. 

https://learn.microsoft.com/en-us/azure/key-vault/general/security-features?WT.mc_id=Portal-Microsoft_Azure_KeyVault#access-model-overview

 
**Modify your application code to retrieve the secrets from the Key Vault:**

a. Use the Azure Key Vault client library to connect to the Key Vault and retrieve the secrets you need. The client library provides a simple and secure way to authenticate to the Key Vault, access secrets, and handle secrets rotation and versioning.

b. Depending on your application's programming language and framework, you can use the Azure Key Vault client library for .NET, Java, Python, or any other supported language.

Refer to the following code snippet for more detail.

	using Azure.Identity;
	using Azure.Security.KeyVault.Secrets;
	
	// Replace with your Key Vault URL and secret name
	string vaultUrl = "https://my-key-vault.vault.azure.net/";
	string secretName = "my-secret";
	
	// Authenticate to Azure using the default credentials
	var credential = new DefaultAzureCredential();
	
	// Create a new Key Vault client
	var client = new SecretClient(new Uri(vaultUrl), credential);
	
	// Retrieve the secret by name
	KeyVaultSecret secret = client.GetSecret(secretName);
	
	// Access the value of the secret
	string secretValue = secret.Value;
	
	// Use the secret value in your application
	Syncfusion.Licensing.SyncfusionLicenseProvider.RegisterLicense(secretValue);

Please follow the MSDN link for more details regarding authentication.

https://learn.microsoft.com/en-us/dotnet/api/overview/azure/security.keyvault.keys-readme?view=azure-dotnet

![Azue Key Vault](licensing-images/azure-key-vault4.png)

Note that you'll need to have the necessary NuGet packages installed, such as **Azure.Identity** and **Azure.Security.KeyVault.Secrets**, and you may need to configure your Azure Key Vault access policies to allow your application to access the secrets.

By following these steps, you can store the Syncfusion license key in Azure Key Vault and use them in a secure and reliable way in your application.
