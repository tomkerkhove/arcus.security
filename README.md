# Arcus - Security
[![Build Status](https://dev.azure.com/codit/Arcus/_apis/build/status/Commit%20builds/CI%20-%20Arcus.Security?branchName=master)](https://dev.azure.com/codit/Arcus/_build/latest?definitionId=727&branchName=master)
[![NuGet Badge](https://buildstats.info/nuget/Arcus.Security.Core?includePreReleases=true)](https://www.nuget.org/packages/Arcus.Security.Core/)

Security for Azure development in a breeze.

![Arcus](https://raw.githubusercontent.com/arcus-azure/arcus/master/media/arcus.png)

# Installation
Easy to install it via NuGet:

- **Azure Key Vault secret provider**

```shell
PM > Install-Package Arcus.Security.Providers.AzureKeyVault
```

- **HashiCorp Vault secret provider**

```shell
PM > Install-Package Arcus.Security.Providers.HashiCorp
```

- **Secret store**

```shell
PM > Install-Package Arcus.Security.Core
```

- **Secret store for Azure Functions**

```shell
PM > Install-Package Arcus.Security.AzureFunctions
```

For a more thorough overview, we recommend reading [our documentation](#documentation).

# Documentation
All documentation can be found on [here](https://security.arcus-azure.net/).

# Customers
Are you an Arcus user? Let us know and [get listed](https://bit.ly/become-a-listed-arcus-user)!

# License Information
This is licensed under The MIT License (MIT). Which means that you can use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the web application. But you always need to state that Codit is the original author of this web application.

Read the full license [here](https://github.com/arcus-azure/arcus.security/blob/master/LICENSE).
