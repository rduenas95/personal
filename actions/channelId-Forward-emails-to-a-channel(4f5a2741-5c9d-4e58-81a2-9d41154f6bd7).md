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

## channelId

| Property | Value     |
| -------- | --------- |
| Name     | channelId |
| Type     | Compose   |

### Inputs

| Property | Value                                                                        |
| -------- | ---------------------------------------------------------------------------- |
| Value    | @first(body('Get\_messages')\['value'\])\['channelIdentity'\]\['channelId'\] |

### Next Action(s) Conditions

| Next Action                                                                                                               |
| ------------------------------------------------------------------------------------------------------------------------- |
| [Get\_Channel\_info \[Succeeded\]](Get_Channel_info-Forward-emails-to-a-channel(4f5a2741-5c9d-4e58-81a2-9d41154f6bd7).md) |
