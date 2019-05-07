# ![LOGO](logo.png) AutomationManagement **flow**ground Connector

## Description

A generated **flow**ground connector for the AutomationManagement API (version 2018-06-30).

Generated from: https://api.apis.guru/v2/specs/azure.com/automation-runbook/2018-06-30/swagger.json<br/>
Generated at: 2019-05-07T17:37:21+03:00

## API Description



## Authorization

Supported authorization schemes:
- OAuth2

For OAuth 2.0 you need to specify OAuth Client credentials as environment variables in the connector repository:
* `OAUTH_CLIENT_ID` - your OAuth client id
* `OAUTH_CLIENT_SECRET` - your OAuth client secret

## Actions

### Retrieve a list of runbooks.

*Tags:* `Runbook`

#### Input Parameters
* `subscriptionId` - _required_ - Gets subscription credentials which uniquely identify Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.
* `resourceGroupName` - _required_ - Name of an Azure Resource group.
* `automationAccountName` - _required_ - The name of the automation account.
* `api-version` - _required_ - Client Api Version.

### Delete the runbook by name.

*Tags:* `Runbook`

#### Input Parameters
* `subscriptionId` - _required_ - Gets subscription credentials which uniquely identify Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.
* `resourceGroupName` - _required_ - Name of an Azure Resource group.
* `automationAccountName` - _required_ - The name of the automation account.
* `runbookName` - _required_ - The runbook name.
* `api-version` - _required_ - Client Api Version.

### Retrieve the runbook identified by runbook name.

*Tags:* `Runbook`

#### Input Parameters
* `subscriptionId` - _required_ - Gets subscription credentials which uniquely identify Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.
* `resourceGroupName` - _required_ - Name of an Azure Resource group.
* `automationAccountName` - _required_ - The name of the automation account.
* `runbookName` - _required_ - The runbook name.
* `api-version` - _required_ - Client Api Version.

### Update the runbook identified by runbook name.

*Tags:* `Runbook`

#### Input Parameters
* `subscriptionId` - _required_ - Gets subscription credentials which uniquely identify Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.
* `resourceGroupName` - _required_ - Name of an Azure Resource group.
* `automationAccountName` - _required_ - The name of the automation account.
* `runbookName` - _required_ - The runbook name.
* `api-version` - _required_ - Client Api Version.

### Create the runbook identified by runbook name.

*Tags:* `Runbook`

#### Input Parameters
* `subscriptionId` - _required_ - Gets subscription credentials which uniquely identify Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.
* `resourceGroupName` - _required_ - Name of an Azure Resource group.
* `automationAccountName` - _required_ - The name of the automation account.
* `runbookName` - _required_ - The runbook name.
* `api-version` - _required_ - Client Api Version.

### Retrieve the content of runbook identified by runbook name.

*Tags:* `Runbook`

#### Input Parameters
* `subscriptionId` - _required_ - Gets subscription credentials which uniquely identify Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.
* `resourceGroupName` - _required_ - Name of an Azure Resource group.
* `automationAccountName` - _required_ - The name of the automation account.
* `runbookName` - _required_ - The runbook name.
* `api-version` - _required_ - Client Api Version.

### Retrieve the runbook draft identified by runbook name.

*Tags:* `RunbookDraft`

#### Input Parameters
* `subscriptionId` - _required_ - Gets subscription credentials which uniquely identify Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.
* `resourceGroupName` - _required_ - Name of an Azure Resource group.
* `automationAccountName` - _required_ - The name of the automation account.
* `runbookName` - _required_ - The runbook name.
* `api-version` - _required_ - Client Api Version.

### Retrieve the content of runbook draft identified by runbook name.

*Tags:* `RunbookDraft`

#### Input Parameters
* `subscriptionId` - _required_ - Gets subscription credentials which uniquely identify Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.
* `resourceGroupName` - _required_ - Name of an Azure Resource group.
* `automationAccountName` - _required_ - The name of the automation account.
* `runbookName` - _required_ - The runbook name.
* `api-version` - _required_ - Client Api Version.

### Replaces the runbook draft content.

*Tags:* `RunbookDraft`

#### Input Parameters
* `subscriptionId` - _required_ - Gets subscription credentials which uniquely identify Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.
* `resourceGroupName` - _required_ - Name of an Azure Resource group.
* `automationAccountName` - _required_ - The name of the automation account.
* `runbookName` - _required_ - The runbook name.
* `api-version` - _required_ - Client Api Version.

### Retrieve the test job for the specified runbook.

*Tags:* `TestJob`

#### Input Parameters
* `subscriptionId` - _required_ - Gets subscription credentials which uniquely identify Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.
* `resourceGroupName` - _required_ - Name of an Azure Resource group.
* `automationAccountName` - _required_ - The name of the automation account.
* `runbookName` - _required_ - The runbook name.
* `api-version` - _required_ - Client Api Version.

### Create a test job of the runbook.

*Tags:* `TestJob`

#### Input Parameters
* `subscriptionId` - _required_ - Gets subscription credentials which uniquely identify Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.
* `resourceGroupName` - _required_ - Name of an Azure Resource group.
* `automationAccountName` - _required_ - The name of the automation account.
* `runbookName` - _required_ - The parameters supplied to the create test job operation.
* `api-version` - _required_ - Client Api Version.

### Resume the test job.

*Tags:* `TestJob`

#### Input Parameters
* `subscriptionId` - _required_ - Gets subscription credentials which uniquely identify Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.
* `resourceGroupName` - _required_ - Name of an Azure Resource group.
* `automationAccountName` - _required_ - The name of the automation account.
* `runbookName` - _required_ - The runbook name.
* `api-version` - _required_ - Client Api Version.

### Stop the test job.

*Tags:* `TestJob`

#### Input Parameters
* `subscriptionId` - _required_ - Gets subscription credentials which uniquely identify Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.
* `resourceGroupName` - _required_ - Name of an Azure Resource group.
* `automationAccountName` - _required_ - The name of the automation account.
* `runbookName` - _required_ - The runbook name.
* `api-version` - _required_ - Client Api Version.

### Retrieve a list of test job streams identified by runbook name.

*Tags:* `TestJobStream`

#### Input Parameters
* `subscriptionId` - _required_ - Gets subscription credentials which uniquely identify Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.
* `resourceGroupName` - _required_ - Name of an Azure Resource group.
* `automationAccountName` - _required_ - The name of the automation account.
* `runbookName` - _required_ - The runbook name.
* `$filter` - _optional_ - The filter to apply on the operation.
* `api-version` - _required_ - Client Api Version.

### Retrieve a test job stream of the test job identified by runbook name and stream id.

*Tags:* `TestJobStream`

#### Input Parameters
* `subscriptionId` - _required_ - Gets subscription credentials which uniquely identify Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.
* `resourceGroupName` - _required_ - Name of an Azure Resource group.
* `automationAccountName` - _required_ - The name of the automation account.
* `runbookName` - _required_ - The runbook name.
* `jobStreamId` - _required_ - The job stream id.
* `api-version` - _required_ - Client Api Version.

### Suspend the test job.

*Tags:* `TestJob`

#### Input Parameters
* `subscriptionId` - _required_ - Gets subscription credentials which uniquely identify Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.
* `resourceGroupName` - _required_ - Name of an Azure Resource group.
* `automationAccountName` - _required_ - The name of the automation account.
* `runbookName` - _required_ - The runbook name.
* `api-version` - _required_ - Client Api Version.

### Undo draft edit to last known published state identified by runbook name.

*Tags:* `RunbookDraft`

#### Input Parameters
* `subscriptionId` - _required_ - Gets subscription credentials which uniquely identify Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.
* `resourceGroupName` - _required_ - Name of an Azure Resource group.
* `automationAccountName` - _required_ - The name of the automation account.
* `runbookName` - _required_ - The runbook name.
* `api-version` - _required_ - Client Api Version.

### Publish runbook draft.

*Tags:* `Runbook`

#### Input Parameters
* `subscriptionId` - _required_ - Gets subscription credentials which uniquely identify Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.
* `resourceGroupName` - _required_ - Name of an Azure Resource group.
* `automationAccountName` - _required_ - The name of the automation account.
* `runbookName` - _required_ - The parameters supplied to the publish runbook operation.
* `api-version` - _required_ - Client Api Version.

## License

**flow**ground :- Telekom iPaaS / azure-com-automation-runbook-connector<br/>
Copyright © 2019, [Deutsche Telekom AG](https://www.telekom.de)<br/>
contact: flowground@telekom.de

All files of this connector are licensed under the Apache 2.0 License. For details
see the file LICENSE on the toplevel directory.
