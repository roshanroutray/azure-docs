---
title: Access the Azure Media Services API - Azure CLI | Microsoft Docs
description: Follow the steps of this how-to to access the Azure Media Services API.
services: media-services
documentationcenter: ''
author: Juliako
manager: femila
editor: ''

ms.service: media-services
ms.workload: 
ms.topic: article
ms.custom: mvc
ms.date: 01/28/2019
ms.author: juliako
---

# Access Azure Media Services API with the Azure CLI
 
You should use the Azure AD service principal authentication to connect to the Azure Media Services API. Your application needs to request an Azure AD token that has the following parameters:

* Azure AD tenant endpoint
* Media Services resource URI
* Resource URI for REST Media Services
* Azure AD application values: the client ID and client secret

This article shows you how to use the Azure CLI to create an Azure AD application and service principal and get the values that are needed to access Azure Media Services resources.

## Prerequisites 

[Create a Media Services account](create-account-cli-how-to.md).

Make sure to remember the values that you used for the resource group name and Media Services account name.
 
[!INCLUDE [media-services-cli-instructions](../../../includes/media-services-cli-instructions.md)]

[!INCLUDE [media-services-v3-cli-access-api-include](../../../includes/media-services-v3-cli-access-api-include.md)]

## Next steps

[Stream a file](stream-files-dotnet-quickstart.md)

## See also

[Azure CLI](https://docs.microsoft.com/cli/azure/ams?view=azure-cli-latest)
