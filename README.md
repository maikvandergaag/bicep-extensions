Welcome to a  list of useful Bicep extensions! This repository aims to showcase extensions and helpers for Bicep.

## Extensions

| Name                         | Repo                                  | Maintainer             | Description                                                  |
| ---------------------------- | ------------------------------------- | ---------------------- | ------------------------------------------------------------ |
| Azure DevOps Extension       | [azure-devops-bicep-local-deploy][00] | [johnlokerse][13]      | Extension for Azure DevOps resources                         |
| Databricks Extension         | [bicep-ext-databricks][01]            | [gijsreyn][14]         | Extension for creating Databricks resources and objects      |
| GitHub Extension             | [bicep-ext-github][02]                | [anthony-c-martin][15] | Extension for Github                                         |
| Http Extension               | [bicep-ext-http][03]                  | [maikvandergaag][16]   | C# Http Extension (Get/Post/Put/Patch/Delete)                |
| Key Vault Extension          | [bicep-ext-keyvault][04]              | [anthony-c-martin][15] | Extension for the dataplane of Azure Key Vault               |
| Kubernetes Extension         | [bicep-ext-kubernetes][05]            | [anthony-c-martin][15] | Extension for Kubernetes                                     |
| Local Extension              | [bicep-ext-local][06]                 | [anthony-c-martin][15] | Extension for local execution                                |
| Password Generator Extension | [bicep-ext-PassWordGenerator][07]     | [mimachniak][17]       | Extension to generate complex password and pass to resources |

## Extension helpers

| Name                             | Repo                     | Maintainer     | Description                                                                 | Package                 |
| -------------------------------- | ------------------------ | -------------- | --------------------------------------------------------------------------- | ----------------------- |
| Bicep Local Deploy Doc Generator | [bicep-local-docgen][08] | [gijsreyn][14] | Library for Bicep annotations and documentation generator for Bicep models. | [Bicep.LocalDeploy][09] |

## Information

Check out the below documentation to get started with Bicep Extensions:

* [Creating a Local Extension with .NET][10]
* [Using Local Deploy (Experimental!)][11]
* [Power Up Your Infrastructure with Bicep Extensions][12]
* [Build a Custom Extension for Bicep][18]

## Contribute Your Extension

Have an extension that you think should be included? Feel free to submit a pull request and add your extension to the list. Community contributions are highly encouraged to keep this collection up to date and valuable for everyone.

<!-- Link reference definitions -->
[00]: https://github.com/johnlokerse/azure-devops-bicep-local-deploy
[01]: https://github.com/Gijsreyn/bicep-ext-databricks
[02]: https://github.com/anthony-c-martin/bicep-ext-github
[03]: https://github.com/maikvandergaag/bicep-ext-http
[04]: https://github.com/anthony-c-martin/bicep-ext-keyvault
[05]: https://github.com/anthony-c-martin/bicep-ext-kubernetes
[06]: https://github.com/anthony-c-martin/bicep-ext-local
[07]: https://github.com/mimachniak/bicep-ext-PassWordGenerator
[08]: https://github.com/Gijsreyn/bicep-local-docgen
[09]: https://www.nuget.org/packages/Bicep.LocalDeploy
[10]: https://github.com/Azure/bicep/blob/main/docs/experimental/local-deploy-dotnet-quickstart.md
[11]: https://github.com/Azure/bicep/blob/main/docs/experimental/local-deploy.md
[12]: https://msftplayground.com/2025/09/bicep-extensions
[13]: https://github.com/johnlokerse
[14]: https://github.com/Gijsreyn
[15]: https://github.com/anthony-c-martin
[16]: https://github.com/maikvandergaag
[17]: https://github.com/mimachniak
[18]: https://msftplayground.com/2025/09/bicep-custom-extension
