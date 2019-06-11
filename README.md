# ![LOGO](logo.png) Azure Media Services **flow**ground Connector

## Description

A generated **flow**ground connector for the Azure Media Services API (version 2018-07-01).

Generated from: https://api.apis.guru/v2/specs/azure.com/mediaservices-AssetsAndAssetFilters/2018-07-01/swagger.json<br/>
Generated at: 2019-06-11T18:14:00+03:00

## API Description

This Swagger was generated by the API Framework.

## Authorization

Supported authorization schemes:
- OAuth2

For OAuth 2.0 you need to specify OAuth Client credentials as environment variables in the connector repository:
* `OAUTH_CLIENT_ID` - your OAuth client id
* `OAUTH_CLIENT_SECRET` - your OAuth client secret

## Actions

### List Assets

> List Assets in the Media Services account with optional filtering and ordering

#### Input Parameters
* `subscriptionId` - _required_ - The unique identifier for a Microsoft Azure subscription.
* `resourceGroupName` - _required_ - The name of the resource group within the Azure subscription.
* `accountName` - _required_ - The Media Services account name.
* `api-version` - _required_ - The Version of the API to be used with the client request.
* `$filter` - _optional_ - Restricts the set of items returned.
* `$top` - _optional_ - Specifies a non-negative integer n that limits the number of items returned from a collection. The service returns the number of available items up to but not greater than the specified value n.
* `$orderby` - _optional_ - Specifies the the key by which the result collection should be ordered.

### Delete an Asset.

> Deletes an Asset in the Media Services account

#### Input Parameters
* `subscriptionId` - _required_ - The unique identifier for a Microsoft Azure subscription.
* `resourceGroupName` - _required_ - The name of the resource group within the Azure subscription.
* `accountName` - _required_ - The Media Services account name.
* `assetName` - _required_ - The Asset name.
* `api-version` - _required_ - The Version of the API to be used with the client request.

### Get an Asset

> Get the details of an Asset in the Media Services account

#### Input Parameters
* `subscriptionId` - _required_ - The unique identifier for a Microsoft Azure subscription.
* `resourceGroupName` - _required_ - The name of the resource group within the Azure subscription.
* `accountName` - _required_ - The Media Services account name.
* `assetName` - _required_ - The Asset name.
* `api-version` - _required_ - The Version of the API to be used with the client request.

### Update an Asset

> Updates an existing Asset in the Media Services account

#### Input Parameters
* `subscriptionId` - _required_ - The unique identifier for a Microsoft Azure subscription.
* `resourceGroupName` - _required_ - The name of the resource group within the Azure subscription.
* `accountName` - _required_ - The Media Services account name.
* `assetName` - _required_ - The Asset name.
* `api-version` - _required_ - The Version of the API to be used with the client request.

### Create or update an Asset

> Creates or updates an Asset in the Media Services account

#### Input Parameters
* `subscriptionId` - _required_ - The unique identifier for a Microsoft Azure subscription.
* `resourceGroupName` - _required_ - The name of the resource group within the Azure subscription.
* `accountName` - _required_ - The Media Services account name.
* `assetName` - _required_ - The Asset name.
* `api-version` - _required_ - The Version of the API to be used with the client request.

### List Asset Filters

> List Asset Filters associated with the specified Asset.

#### Input Parameters
* `subscriptionId` - _required_ - The unique identifier for a Microsoft Azure subscription.
* `resourceGroupName` - _required_ - The name of the resource group within the Azure subscription.
* `accountName` - _required_ - The Media Services account name.
* `assetName` - _required_ - The Asset name.
* `api-version` - _required_ - The Version of the API to be used with the client request.

### Delete an Asset Filter.

> Deletes an Asset Filter associated with the specified Asset.

#### Input Parameters
* `subscriptionId` - _required_ - The unique identifier for a Microsoft Azure subscription.
* `resourceGroupName` - _required_ - The name of the resource group within the Azure subscription.
* `accountName` - _required_ - The Media Services account name.
* `assetName` - _required_ - The Asset name.
* `filterName` - _required_ - The Asset Filter name
* `api-version` - _required_ - The Version of the API to be used with the client request.

### Get an Asset Filter.

> Get the details of an Asset Filter associated with the specified Asset.

#### Input Parameters
* `subscriptionId` - _required_ - The unique identifier for a Microsoft Azure subscription.
* `resourceGroupName` - _required_ - The name of the resource group within the Azure subscription.
* `accountName` - _required_ - The Media Services account name.
* `assetName` - _required_ - The Asset name.
* `filterName` - _required_ - The Asset Filter name
* `api-version` - _required_ - The Version of the API to be used with the client request.

### Update an Asset Filter

> Updates an existing Asset Filter associated with the specified Asset.

#### Input Parameters
* `subscriptionId` - _required_ - The unique identifier for a Microsoft Azure subscription.
* `resourceGroupName` - _required_ - The name of the resource group within the Azure subscription.
* `accountName` - _required_ - The Media Services account name.
* `assetName` - _required_ - The Asset name.
* `filterName` - _required_ - The Asset Filter name
* `api-version` - _required_ - The Version of the API to be used with the client request.

### Create or update an Asset Filter

> Creates or updates an Asset Filter associated with the specified Asset.

#### Input Parameters
* `subscriptionId` - _required_ - The unique identifier for a Microsoft Azure subscription.
* `resourceGroupName` - _required_ - The name of the resource group within the Azure subscription.
* `accountName` - _required_ - The Media Services account name.
* `assetName` - _required_ - The Asset name.
* `filterName` - _required_ - The Asset Filter name
* `api-version` - _required_ - The Version of the API to be used with the client request.

### Gets the Asset storage key

> Gets the Asset storage encryption keys used to decrypt content created by version 2 of the Media Services API

#### Input Parameters
* `subscriptionId` - _required_ - The unique identifier for a Microsoft Azure subscription.
* `resourceGroupName` - _required_ - The name of the resource group within the Azure subscription.
* `accountName` - _required_ - The Media Services account name.
* `assetName` - _required_ - The Asset name.
* `api-version` - _required_ - The Version of the API to be used with the client request.

### List the Asset URLs

> Lists storage container URLs with shared access signatures (SAS) for uploading and downloading Asset content. The signatures are derived from the storage account keys.

#### Input Parameters
* `subscriptionId` - _required_ - The unique identifier for a Microsoft Azure subscription.
* `resourceGroupName` - _required_ - The name of the resource group within the Azure subscription.
* `accountName` - _required_ - The Media Services account name.
* `assetName` - _required_ - The Asset name.
* `api-version` - _required_ - The Version of the API to be used with the client request.

### List Streaming Locators

> Lists Streaming Locators which are associated with this asset.

#### Input Parameters
* `subscriptionId` - _required_ - The unique identifier for a Microsoft Azure subscription.
* `resourceGroupName` - _required_ - The name of the resource group within the Azure subscription.
* `accountName` - _required_ - The Media Services account name.
* `assetName` - _required_ - The Asset name.
* `api-version` - _required_ - The Version of the API to be used with the client request.

## License

**flow**ground :- Telekom iPaaS / azure-com-mediaservices-assets-and-asset-filters-connector<br/>
Copyright © 2019, [Deutsche Telekom AG](https://www.telekom.de)<br/>
contact: flowground@telekom.de

All files of this connector are licensed under the Apache 2.0 License. For details
see the file LICENSE on the toplevel directory.
