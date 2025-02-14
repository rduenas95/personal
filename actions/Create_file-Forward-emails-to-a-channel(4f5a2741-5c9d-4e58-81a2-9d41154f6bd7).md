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

## Create\_file

| Property   | Value                                                                                                               |
| ---------- | ------------------------------------------------------------------------------------------------------------------- |
| Name       | Create\_file                                                                                                        |
| Type       | OpenApiConnection                                                                                                   |
| Connection | [![sharepointonline](../sharepointonline32.png) SharePoint](https://docs.microsoft.com/connectors/sharepointonline) |

### Inputs

| Property             | Value                                                                                                                                                                                                                                                                                                                                                                               |
| -------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| host                 | <table><tr><td>apiId</td><td>/providers/Microsoft.PowerApps/apis/shared_sharepointonline</td></tr><tr><td>connectionName</td><td>shared_sharepointonline</td></tr><tr><td>operationId</td><td>CreateFile</td></tr></table>                                                                                                                                                          |
| parameters           | <table><tr><td>dataset</td><td>@outputs('SharePoint_Site')</td></tr><tr><td>folderPath</td><td>@replace(body('Get_Channel_info')['filesFolderWebUrl'], outputs('SharePoint_Site'), '')</td></tr><tr><td>name</td><td>@concat(replace(triggerOutputs()?['body/subject'], ' ', '_'),'_',ticks(utcNow()),'.eml')</td></tr><tr><td>body</td><td>@body('Export_email')</td></tr></table> |
| authentication       | @parameters('$authentication')                                                                                                                                                                                                                                                                                                                                                      |
| runtimeConfiguration | <table><tr><td>contentTransfer</td><td><table><tr><td>transferMode</td><td>Chunked</td></tr></table></td></tr></table>                                                                                                                                                                                                                                                              |

### Next Action(s) Conditions

| Next Action                                                                                                                                           |
| ----------------------------------------------------------------------------------------------------------------------------------------------------- |
| [Post\_adaptive\_card\_to\_channel \[Succeeded\]](Post_adaptive_card_to_channel-Forward-emails-to-a-channel(4f5a2741-5c9d-4e58-81a2-9d41154f6bd7).md) |
