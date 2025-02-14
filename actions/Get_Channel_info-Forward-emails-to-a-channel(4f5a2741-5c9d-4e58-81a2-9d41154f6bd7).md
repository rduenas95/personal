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

## Get\_Channel\_info

| Property   | Value                                                                                   |
| ---------- | --------------------------------------------------------------------------------------- |
| Name       | Get\_Channel\_info                                                                      |
| Type       | OpenApiConnection                                                                       |
| Connection | [![teams](../teams32.png) Microsoft Teams](https://docs.microsoft.com/connectors/teams) |

### Inputs

| Property       | Value                                                                                                                                                                                                                                            |
| -------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| host           | <table><tr><td>apiId</td><td>/providers/Microsoft.PowerApps/apis/shared_teams</td></tr><tr><td>connectionName</td><td>shared_teams</td></tr><tr><td>operationId</td><td>HttpRequest</td></tr></table>                                            |
| parameters     | <table><tr><td>Uri</td><td>@concat('https://graph.microsoft.com/beta/teams/', outputs('teamId'), '/channels/', outputs('channelId'))</td></tr><tr><td>Method</td><td>GET</td></tr><tr><td>ContentType</td><td>application/json</td></tr></table> |
| authentication | @parameters('$authentication')                                                                                                                                                                                                                   |

### Next Action(s) Conditions

| Next Action                                                                                                            |
| ---------------------------------------------------------------------------------------------------------------------- |
| [SharePoint\_Site \[Succeeded\]](SharePoint_Site-Forward-emails-to-a-channel(4f5a2741-5c9d-4e58-81a2-9d41154f6bd7).md) |
