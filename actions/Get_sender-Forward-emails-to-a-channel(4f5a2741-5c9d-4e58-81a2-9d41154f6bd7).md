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

## Get\_sender

| Property   | Value                                                                                                               |
| ---------- | ------------------------------------------------------------------------------------------------------------------- |
| Name       | Get\_sender                                                                                                         |
| Type       | OpenApiConnection                                                                                                   |
| Connection | [![office365users](../office365users32.png) Office 365 Users](https://docs.microsoft.com/connectors/office365users) |

### Inputs

| Property       | Value                                                                                                                                                                                                                      |
| -------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| host           | <table><tr><td>apiId</td><td>/providers/Microsoft.PowerApps/apis/shared_office365users</td></tr><tr><td>connectionName</td><td>shared_office365users</td></tr><tr><td>operationId</td><td>UserProfile_V2</td></tr></table> |
| parameters     | <table><tr><td>id</td><td>@triggerOutputs()?['body/from']</td></tr></table>                                                                                                                                                |
| authentication | @parameters('$authentication')                                                                                                                                                                                             |

### Next Action(s) Conditions

| Next Action                                                                                                              |
| ------------------------------------------------------------------------------------------------------------------------ |
| [Email\_sender \[Succeeded, Failed\]](Email_sender-Forward-emails-to-a-channel(4f5a2741-5c9d-4e58-81a2-9d41154f6bd7).md) |
