---
layout: page
title: Arcus Security
permalink: /
---

# Arcus Security

[![Build Status](https://dev.azure.com/codit/Arcus/_apis/build/status/Commit%20builds/CI%20-%20Arcus.Security?branchName=master)](https://dev.azure.com/codit/Arcus/_build/latest?definitionId=727&branchName=master)
[![NuGet Badge](https://buildstats.info/nuget/Arcus.Security.Core?includePreReleases=true)](https://www.nuget.org/packages/Arcus.Security.Core/)

Security for Azure development in a breeze.

![Arcus](https://raw.githubusercontent.com/arcus-azure/arcus/master/media/arcus.png)

## Installation

We provide a NuGet package per provider and area.

Here is how you install all Arcus Security packages
```shell
PM > Install-Package Arcus.Security.All
```

Here is how you consume secrets for Azure Key Vault:
```shell
PM > Install-Package Arcus.Security.Providers.AzureKeyVault
```

## Features

- **Using a Secret Store**
  - What is it?
  - Providers
    - Azure Key Vault
    - Configuration
    - Environment variables
    - User Secrets
  - Creating your own secret provider
- **Interacting with Secrets**
    - General
    - Consume from Azure Key Vault
    - Authenticate with Azure Key Vault

