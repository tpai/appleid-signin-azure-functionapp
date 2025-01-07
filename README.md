# Apple ID Sign In Azure Function App

## Commands

```bash
# list packages
dotnet list packages

# build bin
dotnet build

# clean and publish binary
dotnet clean --configuration Debug /property:GenerateFullPaths=true /consoleloggerparameters:NoSummary
dotnet publish --configuration Debug /property:GenerateFullPaths=true /consoleloggerparameters:NoSummary
```

## How to deploy?

1. Install [.NET 8.0](https://dotnet.microsoft.com/en-us/download/dotnet/8.0).
1. Download [VS Code](https://code.visualstudio.com/download) and install the `Azure Functions` extension.
1. Switch to `Azure Functions` tab and log in to Azure.
1. Right click on `Local Project` in WORKSPACE pane and select `Deploy to Azure...`

## How to debug?

1. Visit the Azure Function App page
1. Enable `Application Insights`
1. Switch to Functions tab
1. Click `Invocations and more`
1. Click `Code + Test`

## References

https://learn.microsoft.com/en-us/azure/active-directory-b2c/identity-provider-apple-id?pivots=b2c-custom-policy#signing-the-client-secret
