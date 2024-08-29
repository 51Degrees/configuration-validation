# 51Degrees Pipeline API - Configuration schemas

![51Degrees](https://51degrees.com/img/logo.png?utm_source=github&utm_medium=repository&utm_content=readme_main&utm_campaign=shared-open-source "Data rewards the curious") **Pipeline API**

[Developer Documentation](https://51degrees.com/documentation/index.html?utm_source=github&utm_medium=repository&utm_content=documentation&utm_campaign=shared-open-source "developer documentation")

# Introduction
This repository contains the schemas that are used to validate Pipeline API configuration files.

# Schemas

|Filename|Description|
|---|---|
|pipelineOptions.xsd|Used to validate xml settings files used by the Java Pipeline API|
|pipelineOptionsSchema.json|Used to validate json settings files used by the .NET Pipeline API|
|pipelineOptionsInAppSettings.json|Used to validate json `appsettings.json` files that contain ASP.NET configuration in addition to Pipeline API configuration |

\* The `pipelineOptionsSchema.json` file is used in [FiftyOne.Pipeline.Web.Framework](https://github.com/51Degrees/pipeline-dotnet/blob/d74f3e7ba6554a5df93e4045b8a113676b06e5d9/Web%20Integration/FiftyOne.Pipeline.Web.Framework/Configuration/Extensions.cs#L121-L144) to validate the user's configuration file.
