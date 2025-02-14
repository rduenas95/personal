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

## Trigger

| Property  | Value                              |
| --------- | ---------------------------------- |
| Name      | When\_a\_new\_email\_arrives\_(V3) |
| Type      | OpenApiConnectionNotification      |
| Connector | office365                          |

### Inputs Details

<table><tr><td>host</td><td><table><tr><td>apiId</td><td>/providers/Microsoft.PowerApps/apis/shared_office365</td></tr><tr><td>connectionName</td><td>shared_office365</td></tr><tr><td>operationId</td><td>OnNewEmailV3</td></tr></table></td></tr><tr><td>parameters</td><td><table><tr><td>to</td><td>v-rduenas@microsoft.com</td></tr><tr><td>includeAttachments</td><td>False</td></tr><tr><td>importance</td><td>Any</td></tr><tr><td>fetchOnlyWithAttachment</td><td>False</td></tr></table></td></tr><tr><td>authentication</td><td>@parameters('$authentication')</td></tr></table>

### Other Trigger Properties

<table><tr><td>splitOn</td><td>@triggerOutputs()?['body/value']</td></tr></table>
