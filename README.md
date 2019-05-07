# ![LOGO](logo.png) ContainerRegistryManagementClient **flow**ground Connector

## Description

A generated **flow**ground connector for the ContainerRegistryManagementClient API (version 2017-10-01).

Generated from: https://api.apis.guru/v2/specs/azure.com/containerregistry/2017-10-01/swagger.json<br/>
Generated at: 2019-05-07T17:37:52+03:00

## API Description



## Authorization

Supported authorization schemes:
- OAuth2

For OAuth 2.0 you need to specify OAuth Client credentials as environment variables in the connector repository:
* `OAUTH_CLIENT_ID` - your OAuth client id
* `OAUTH_CLIENT_SECRET` - your OAuth client secret

## Actions

### Lists all of the available Azure Container Registry REST API operations.

*Tags:* `Operation`

#### Input Parameters
* `api-version` - _required_ - The client API version.

### Checks whether the container registry name is available for use. The name must contain only alphanumeric characters, be globally unique, and between 5 and 50 characters in length.

*Tags:* `Operation`

#### Input Parameters
* `api-version` - _required_ - The client API version.
* `subscriptionId` - _required_ - The Microsoft Azure subscription ID.

### Lists all the container registries under the specified subscription.

*Tags:* `Registries`

#### Input Parameters
* `api-version` - _required_ - The client API version.
* `subscriptionId` - _required_ - The Microsoft Azure subscription ID.

### Lists all the container registries under the specified resource group.

*Tags:* `Registries`

#### Input Parameters
* `api-version` - _required_ - The client API version.
* `subscriptionId` - _required_ - The Microsoft Azure subscription ID.
* `resourceGroupName` - _required_ - The name of the resource group to which the container registry belongs.

### Deletes a container registry.

*Tags:* `Registries`

#### Input Parameters
* `api-version` - _required_ - The client API version.
* `subscriptionId` - _required_ - The Microsoft Azure subscription ID.
* `resourceGroupName` - _required_ - The name of the resource group to which the container registry belongs.
* `registryName` - _required_ - The name of the container registry.

### Gets the properties of the specified container registry.

*Tags:* `Registries`

#### Input Parameters
* `api-version` - _required_ - The client API version.
* `subscriptionId` - _required_ - The Microsoft Azure subscription ID.
* `resourceGroupName` - _required_ - The name of the resource group to which the container registry belongs.
* `registryName` - _required_ - The name of the container registry.

### Updates a container registry with the specified parameters.

*Tags:* `Registries`

#### Input Parameters
* `api-version` - _required_ - The client API version.
* `subscriptionId` - _required_ - The Microsoft Azure subscription ID.
* `resourceGroupName` - _required_ - The name of the resource group to which the container registry belongs.
* `registryName` - _required_ - The name of the container registry.

### Creates a container registry with the specified parameters.

*Tags:* `Registries`

#### Input Parameters
* `api-version` - _required_ - The client API version.
* `subscriptionId` - _required_ - The Microsoft Azure subscription ID.
* `resourceGroupName` - _required_ - The name of the resource group to which the container registry belongs.
* `registryName` - _required_ - The name of the container registry.

### Copies an image to this container registry from the specified container registry.

*Tags:* `Registries`

#### Input Parameters
* `api-version` - _required_ - The client API version.
* `subscriptionId` - _required_ - The Microsoft Azure subscription ID.
* `resourceGroupName` - _required_ - The name of the resource group to which the container registry belongs.
* `registryName` - _required_ - The name of the container registry.

### Lists the login credentials for the specified container registry.

*Tags:* `Registries`

#### Input Parameters
* `api-version` - _required_ - The client API version.
* `subscriptionId` - _required_ - The Microsoft Azure subscription ID.
* `resourceGroupName` - _required_ - The name of the resource group to which the container registry belongs.
* `registryName` - _required_ - The name of the container registry.

### Lists the policies for the specified container registry.

*Tags:* `Registries`

#### Input Parameters
* `api-version` - _required_ - The client API version.
* `subscriptionId` - _required_ - The Microsoft Azure subscription ID.
* `resourceGroupName` - _required_ - The name of the resource group to which the container registry belongs.
* `registryName` - _required_ - The name of the container registry.

### Gets the quota usages for the specified container registry.

*Tags:* `Registries`

#### Input Parameters
* `api-version` - _required_ - The client API version.
* `subscriptionId` - _required_ - The Microsoft Azure subscription ID.
* `resourceGroupName` - _required_ - The name of the resource group to which the container registry belongs.
* `registryName` - _required_ - The name of the container registry.

### Regenerates one of the login credentials for the specified container registry.

*Tags:* `Registries`

#### Input Parameters
* `api-version` - _required_ - The client API version.
* `subscriptionId` - _required_ - The Microsoft Azure subscription ID.
* `resourceGroupName` - _required_ - The name of the resource group to which the container registry belongs.
* `registryName` - _required_ - The name of the container registry.

### Lists all the replications for the specified container registry.

*Tags:* `Replications`

#### Input Parameters
* `api-version` - _required_ - The client API version.
* `subscriptionId` - _required_ - The Microsoft Azure subscription ID.
* `resourceGroupName` - _required_ - The name of the resource group to which the container registry belongs.
* `registryName` - _required_ - The name of the container registry.

### Deletes a replication from a container registry.

*Tags:* `Replications`

#### Input Parameters
* `api-version` - _required_ - The client API version.
* `subscriptionId` - _required_ - The Microsoft Azure subscription ID.
* `resourceGroupName` - _required_ - The name of the resource group to which the container registry belongs.
* `registryName` - _required_ - The name of the container registry.
* `replicationName` - _required_ - The name of the replication.

### Gets the properties of the specified replication.

*Tags:* `Replications`

#### Input Parameters
* `api-version` - _required_ - The client API version.
* `subscriptionId` - _required_ - The Microsoft Azure subscription ID.
* `resourceGroupName` - _required_ - The name of the resource group to which the container registry belongs.
* `registryName` - _required_ - The name of the container registry.
* `replicationName` - _required_ - The name of the replication.

### Updates a replication for a container registry with the specified parameters.

*Tags:* `Replications`

#### Input Parameters
* `api-version` - _required_ - The client API version.
* `subscriptionId` - _required_ - The Microsoft Azure subscription ID.
* `resourceGroupName` - _required_ - The name of the resource group to which the container registry belongs.
* `registryName` - _required_ - The name of the container registry.
* `replicationName` - _required_ - The name of the replication.

### Creates a replication for a container registry with the specified parameters.

*Tags:* `Replications`

#### Input Parameters
* `api-version` - _required_ - The client API version.
* `subscriptionId` - _required_ - The Microsoft Azure subscription ID.
* `resourceGroupName` - _required_ - The name of the resource group to which the container registry belongs.
* `registryName` - _required_ - The name of the container registry.
* `replicationName` - _required_ - The name of the replication.

### Updates the policies for the specified container registry.

*Tags:* `Registries`

#### Input Parameters
* `api-version` - _required_ - The client API version.
* `subscriptionId` - _required_ - The Microsoft Azure subscription ID.
* `resourceGroupName` - _required_ - The name of the resource group to which the container registry belongs.
* `registryName` - _required_ - The name of the container registry.

### Lists all the webhooks for the specified container registry.

*Tags:* `Webhooks`

#### Input Parameters
* `api-version` - _required_ - The client API version.
* `subscriptionId` - _required_ - The Microsoft Azure subscription ID.
* `resourceGroupName` - _required_ - The name of the resource group to which the container registry belongs.
* `registryName` - _required_ - The name of the container registry.

### Deletes a webhook from a container registry.

*Tags:* `Webhooks`

#### Input Parameters
* `api-version` - _required_ - The client API version.
* `subscriptionId` - _required_ - The Microsoft Azure subscription ID.
* `resourceGroupName` - _required_ - The name of the resource group to which the container registry belongs.
* `registryName` - _required_ - The name of the container registry.
* `webhookName` - _required_ - The name of the webhook.

### Gets the properties of the specified webhook.

*Tags:* `Webhooks`

#### Input Parameters
* `api-version` - _required_ - The client API version.
* `subscriptionId` - _required_ - The Microsoft Azure subscription ID.
* `resourceGroupName` - _required_ - The name of the resource group to which the container registry belongs.
* `registryName` - _required_ - The name of the container registry.
* `webhookName` - _required_ - The name of the webhook.

### Updates a webhook with the specified parameters.

*Tags:* `Webhooks`

#### Input Parameters
* `api-version` - _required_ - The client API version.
* `subscriptionId` - _required_ - The Microsoft Azure subscription ID.
* `resourceGroupName` - _required_ - The name of the resource group to which the container registry belongs.
* `registryName` - _required_ - The name of the container registry.
* `webhookName` - _required_ - The name of the webhook.

### Creates a webhook for a container registry with the specified parameters.

*Tags:* `Webhooks`

#### Input Parameters
* `api-version` - _required_ - The client API version.
* `subscriptionId` - _required_ - The Microsoft Azure subscription ID.
* `resourceGroupName` - _required_ - The name of the resource group to which the container registry belongs.
* `registryName` - _required_ - The name of the container registry.
* `webhookName` - _required_ - The name of the webhook.

### Gets the configuration of service URI and custom headers for the webhook.

*Tags:* `Webhooks`

#### Input Parameters
* `api-version` - _required_ - The client API version.
* `subscriptionId` - _required_ - The Microsoft Azure subscription ID.
* `resourceGroupName` - _required_ - The name of the resource group to which the container registry belongs.
* `registryName` - _required_ - The name of the container registry.
* `webhookName` - _required_ - The name of the webhook.

### Lists recent events for the specified webhook.

*Tags:* `Webhooks`

#### Input Parameters
* `api-version` - _required_ - The client API version.
* `subscriptionId` - _required_ - The Microsoft Azure subscription ID.
* `resourceGroupName` - _required_ - The name of the resource group to which the container registry belongs.
* `registryName` - _required_ - The name of the container registry.
* `webhookName` - _required_ - The name of the webhook.

### Triggers a ping event to be sent to the webhook.

*Tags:* `Webhooks`

#### Input Parameters
* `api-version` - _required_ - The client API version.
* `subscriptionId` - _required_ - The Microsoft Azure subscription ID.
* `resourceGroupName` - _required_ - The name of the resource group to which the container registry belongs.
* `registryName` - _required_ - The name of the container registry.
* `webhookName` - _required_ - The name of the webhook.

## License

**flow**ground :- Telekom iPaaS / azure-com-containerregistry-connector<br/>
Copyright © 2019, [Deutsche Telekom AG](https://www.telekom.de)<br/>
contact: flowground@telekom.de

All files of this connector are licensed under the Apache 2.0 License. For details
see the file LICENSE on the toplevel directory.
