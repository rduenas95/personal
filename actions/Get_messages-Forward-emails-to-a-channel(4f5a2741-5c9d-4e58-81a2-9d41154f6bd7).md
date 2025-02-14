# Flow Documentation \- Forward emails to a channel

| Flow Name                  | Forward emails to a channel              |
| -------------------------- | ---------------------------------------- |
| Flow Name                  | Forward emails to a channel              |
| Flow ID                    | 4f5a2741\-5c9d\-4e58\-81a2\-9d41154f6bd7 |
| Documentation generated at | Thursday, February 13, 2025 5:17 PM      |
| Number of Variables        | 0                                        |
| Number of Actions          | 10                                       |

- [Overview](../index-Forward-emails-to-a-channel(4f5a2741-5c9d-4e58-81a2-9d41154f6bd7).md)
- [Connection References](../connections-Forward-emails-to-a-channel(4f5a2741-5c9d-4e58-81a2-9d41154f6bd7).md)
- [Variables](../variables-Forward-emails-to-a-channel(4f5a2741-5c9d-4e58-81a2-9d41154f6bd7).md)
- [Triggers & Actions](../triggersactions-Forward-emails-to-a-channel(4f5a2741-5c9d-4e58-81a2-9d41154f6bd7).md)

## Get\_messages

| Property   | Value                                                                                   |
| ---------- | --------------------------------------------------------------------------------------- |
| Name       | Get\_messages                                                                           |
| Type       | OpenApiConnection                                                                       |
| Connection | [![teams](../teams32.png) Microsoft Teams](https://docs.microsoft.com/connectors/teams) |

### Inputs

| Property       | Value                                                                                                                                                                                                            |
| -------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| host           | <table><tr><td>apiId</td><td>/providers/Microsoft.PowerApps/apis/shared_teams</td></tr><tr><td>connectionName</td><td>shared_teams</td></tr><tr><td>operationId</td><td>GetMessagesFromChannel</td></tr></table> |
| parameters     | <table><tr><td>groupId</td><td>bd7627e8-fd69-44a1-a5e3-1ce1a14dc5e9</td></tr><tr><td>channelId</td><td>19:742b8f5053b24def8e9e2bfb06bf116c@thread.tacv2</td></tr></table>                                        |
| authentication | @parameters('$authentication')                                                                                                                                                                                   |

### Next Action(s) Conditions

| Next Action                                                                                         |
| --------------------------------------------------------------------------------------------------- |
| [teamId \[Succeeded\]](teamId-Forward-emails-to-a-channel(4f5a2741-5c9d-4e58-81a2-9d41154f6bd7).md) |
