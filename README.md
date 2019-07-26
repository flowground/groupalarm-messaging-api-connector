# ![LOGO](logo.png) groupalarm Messaging API **flow**ground Connector

## Description

A generated **flow**ground connector for the groupalarm Messaging API API (version 1.16.4).

Generated from: https://app.groupalarm.com/api/v1<br/>
Generated at: 2019-07-26T13:59:34+03:00

## API Description

The messaging service implements all functions for message-management in GroupAlarm<br/>
<br/>
# Authentication<br/>
<br/>
<!-- ReDoc-Inject: <security-definitions> --><br/>

## Authorization

Supported authorization schemes:
- API Key
- API Key

## Actions

### UpsertEscalation
> Creates or updates an existing escalation configuration for the passed user<br/>

*Tags:* `user`

### GetEscalation
> Returns the escalation configuration for the passed user<br/>

*Tags:* `user`

#### Input Parameters
* `userID` - _required_ - user id for the requested escalation<br/>

### GetAlarmMessageStatus
> Returns the current alarm message status for the user in the given alarm<br/>

*Tags:* `alarm`

#### Input Parameters
* `alarm_id` - _required_ - alarmID this request is about<br/>
* `organization_id` - _required_ - associated organization requesting the information (used for rbac-check)<br/>
* `user_id` - _required_ - requested user status<br/>
* `unit_id` - _required_ - unit this user is assigned to in this alarm<br/>
* `label_id` - _required_ - label this user is assigned to in this alarm<br/>

### UserFeedback
> Sets the user feedback for a specific alarm using the api<br/>

*Tags:* `feedback`

## License

**flow**ground :- Telekom iPaaS / groupalarm-messaging-api-connector<br/>
Copyright © 2019, [Deutsche Telekom AG](https://www.telekom.de)<br/>
contact: flowground@telekom.de

All files of this connector are licensed under the Apache 2.0 License. For details
see the file LICENSE on the toplevel directory.
