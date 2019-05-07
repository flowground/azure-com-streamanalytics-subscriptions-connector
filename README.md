# ![LOGO](logo.png) StreamAnalyticsManagementClient **flow**ground Connector

## Description

A generated **flow**ground connector for the StreamAnalyticsManagementClient API (version 2016-03-01).

Generated from: https://api.apis.guru/v2/specs/azure.com/streamanalytics-subscriptions/2016-03-01/swagger.json<br/>
Generated at: 2019-05-07T17:39:19+03:00

## API Description



## Authorization

Supported authorization schemes:
- OAuth2

For OAuth 2.0 you need to specify OAuth Client credentials as environment variables in the connector repository:
* `OAUTH_CLIENT_ID` - your OAuth client id
* `OAUTH_CLIENT_SECRET` - your OAuth client secret

## Actions

### Retrieves the subscription's current quota information in a particular region.

*Tags:* `Subscriptions`

#### Input Parameters
* `location` - _required_ - The region in which to retrieve the subscription's quota information. You can find out which regions Azure Stream Analytics is supported in here: https://azure.microsoft.com/en-us/regions/
* `api-version` - _required_ - Client Api Version.
* `subscriptionId` - _required_ - GUID which uniquely identify Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.

## License

**flow**ground :- Telekom iPaaS / azure-com-streamanalytics-subscriptions-connector<br/>
Copyright © 2019, [Deutsche Telekom AG](https://www.telekom.de)<br/>
contact: flowground@telekom.de

All files of this connector are licensed under the Apache 2.0 License. For details
see the file LICENSE on the toplevel directory.
