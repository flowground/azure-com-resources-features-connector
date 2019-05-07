# ![LOGO](logo.png) FeatureClient **flow**ground Connector

## Description

A generated **flow**ground connector for the FeatureClient API (version 2015-12-01).

Generated from: https://api.apis.guru/v2/specs/azure.com/resources-features/2015-12-01/swagger.json<br/>
Generated at: 2019-05-07T17:38:45+03:00

## API Description

Azure Feature Exposure Control (AFEC) provides a mechanism for the resource providers to control feature exposure to users. Resource providers typically use this mechanism to provide public/private preview for new features prior to making them generally available. Users need to explicitly register for AFEC features to get access to such functionality.

## Authorization

Supported authorization schemes:
- OAuth2

For OAuth 2.0 you need to specify OAuth Client credentials as environment variables in the connector repository:
* `OAUTH_CLIENT_ID` - your OAuth client id
* `OAUTH_CLIENT_SECRET` - your OAuth client secret

## Actions

### Lists all of the available Microsoft.Features REST API operations.

*Tags:* `Operations`

#### Input Parameters
* `api-version` - _required_ - The API version to use for this operation.

### Gets all the preview features that are available through AFEC for the subscription.

*Tags:* `Features`

#### Input Parameters
* `api-version` - _required_ - The API version to use for this operation.
* `subscriptionId` - _required_ - The ID of the target subscription.

### Gets all the preview features in a provider namespace that are available through AFEC for the subscription.

*Tags:* `Features`

#### Input Parameters
* `resourceProviderNamespace` - _required_ - The namespace of the resource provider for getting features.
* `api-version` - _required_ - The API version to use for this operation.
* `subscriptionId` - _required_ - The ID of the target subscription.

### Gets the preview feature with the specified name.

*Tags:* `Features`

#### Input Parameters
* `resourceProviderNamespace` - _required_ - The resource provider namespace for the feature.
* `featureName` - _required_ - The name of the feature to get.
* `api-version` - _required_ - The API version to use for this operation.
* `subscriptionId` - _required_ - The ID of the target subscription.

### Registers the preview feature for the subscription.

*Tags:* `Features`

#### Input Parameters
* `resourceProviderNamespace` - _required_ - The namespace of the resource provider.
* `featureName` - _required_ - The name of the feature to register.
* `api-version` - _required_ - The API version to use for this operation.
* `subscriptionId` - _required_ - The ID of the target subscription.

## License

**flow**ground :- Telekom iPaaS / azure-com-resources-features-connector<br/>
Copyright © 2019, [Deutsche Telekom AG](https://www.telekom.de)<br/>
contact: flowground@telekom.de

All files of this connector are licensed under the Apache 2.0 License. For details
see the file LICENSE on the toplevel directory.
