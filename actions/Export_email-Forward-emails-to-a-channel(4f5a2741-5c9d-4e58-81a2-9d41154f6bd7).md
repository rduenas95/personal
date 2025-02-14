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

## Export\_email

| Property   | Value                                                                                                  |
| ---------- | ------------------------------------------------------------------------------------------------------ |
| Name       | Export\_email                                                                                          |
| Type       | OpenApiConnection                                                                                      |
| Connection | [![office365](../office36532.png) Office 365 Outlook](https://docs.microsoft.com/connectors/office365) |

### Inputs

| Property       | Value                                                                                                                                                                                                            |
| -------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| host           | <table><tr><td>apiId</td><td>/providers/Microsoft.PowerApps/apis/shared_office365</td></tr><tr><td>connectionName</td><td>shared_office365</td></tr><tr><td>operationId</td><td>ExportEmail_V2</td></tr></table> |
| parameters     | <table><tr><td>messageId</td><td>@triggerOutputs()?['body/id']</td></tr></table>                                                                                                                                 |
| authentication | @parameters('$authentication')                                                                                                                                                                                   |

### Next Action(s) Conditions

| Next Action                                                                                                    |
| -------------------------------------------------------------------------------------------------------------- |
| [Create\_file \[Succeeded\]](Create_file-Forward-emails-to-a-channel(4f5a2741-5c9d-4e58-81a2-9d41154f6bd7).md) |
