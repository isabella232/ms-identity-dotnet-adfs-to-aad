---
page_type: sample
languages:
- csharp
products:
- dotnet
description: "Guidance to Migrate Web Applications from AD FS to Azure AD"
urlFragment: "ms-identity-dotnet-adfs-to-aad"
---

# Guidance to Migrate Web Applications from AD FS to Azure AD

## About this sample

### Overview

This sample will guide you through steps to migrate a web application from AD FS to Azure AD. It provides you a web application playground to test the migration, using both [SAML](https://docs.microsoft.com/azure/active-directory/develop/single-sign-on-saml-protocol) and [OpenId Connect](https://docs.microsoft.com/azure/active-directory/develop/v2-protocols-oidc) protocols.

Title: ADFS to Azure AD application migration playbook

This set of tutorials and guides will help you learn how to safely and securely migrate your applications integrated with 
Active Directory Federation Services (ADFS) to Azure Active Directory.

These code samples are an extension to the official Microsoft guide,[Moving application authentication from Active Directory Federation Services to Azure Active Directory](https://docs.microsoft.com/azure/active-directory/manage-apps/migrate-adfs-apps-to-azure).

>NOTE: For Integrated Windows Authentication (IWA) guide, please check [this sample](https://github.com/Azure-Samples/active-directory-dotnet-iwa-v2).

In the following chapters, we cover the most common types of authentication used by application in ADFS today. We hope that you can use these examples to learn and get experienced before undertaking the same steps with your in-production applications.

The following chapters are available for you to go through:

<---- Table with chapters, images and and links.--->


<---- standard stuff here --->

### Scenario

- A playground web application on AD FS using [SAML](https://docs.microsoft.com/azure/active-directory/develop/single-sign-on-saml-protocol) and [OpenId Connect](https://docs.microsoft.com/azure/active-directory/develop/v2-protocols-oidc) protocol, to be used as a migration test
- Guidance on how to configure Azure AD Connect tool
- Guidance on how to migrate [Directory Extensions](https://docs.microsoft.com/azure/active-directory/hybrid/how-to-connect-sync-feature-directory-extensions) to Azure AD
- Steps on migrating the playground web application to Azure AD and a code sample
- Guidance to enable Security Groups on the migrated playground application
- Steps on changing an application from SAML to OpenId Connect protocol and a code sample

## Contents

| File/folder       | Description                                |
|-------------------|--------------------------------------------|
| `1-ADFS-Host`     | Chapter about configuration on the AD FS side.                                                            |
| `2-AAD-Migration` | Chapter about configuration on the Azure AD side and the migration steps.                                             |
| `CONTRIBUTING.md` | Guidelines for contributing to the sample. |
| `README.md`       | This README file.                          |
| `LICENSE`         | The license for the sample.                |

## Setup

### Prerequisites

- .NET Framework 4.7.2
- An AD FS environment
- An Azure Active Directory (Azure AD) tenant. For more information on how to get an Azure AD tenant, see [How to get an Azure AD tenant](https://azure.microsoft.com/en-us/documentation/articles/active-directory-howto-tenant/)
- An Azure AD tenant admin account

## Community Help and Support

Use [Stack Overflow](http://stackoverflow.com/questions/tagged/msal) to get support from the community.

If you find a bug in the sample, please raise the issue on [GitHub Issues](../issues).

To provide a recommendation, visit the following [User Voice page](https://feedback.azure.com/forums/169401-azure-active-directory).

## Contributing

This project welcomes contributions and suggestions.  Most contributions require you to agree to a
Contributor License Agreement (CLA) declaring that you have the right to, and actually do, grant us
the rights to use your contribution. For details, visit https://cla.opensource.microsoft.com.

When you submit a pull request, a CLA bot will automatically determine whether you need to provide
a CLA and decorate the PR appropriately (e.g., status check, comment). Simply follow the instructions
provided by the bot. You will only need to do this once across all repos using our CLA.

This project has adopted the [Microsoft Open Source Code of Conduct](https://opensource.microsoft.com/codeofconduct/).
For more information see the [Code of Conduct FAQ](https://opensource.microsoft.com/codeofconduct/faq/) or
contact [opencode@microsoft.com](mailto:opencode@microsoft.com) with any additional questions or comments.
