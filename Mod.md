#ChannelMute
>
###Description:
**Toggles all commands** from **being used in the channel** in which this command is used. **Overrides the muted channel** condition so it can be used in a muted channel.
###Aliases:
`cmute`
###Cooldown:
`5s`  
###Delete On Use:
`True`
###Works in DM's:
`False`  
###Usage:
`channelmute`  


#SetPrefix
>
###Description:
**Sets the current prefix** to the inputted term. Spaces **cannot** be used. Sending **nothing will revert it** to the default prefix.
###Aliases:
`None`
###Cooldown:  
`25s`
###Delete On Use:  
`False`
###Works in DM's:
`False`  
###Usage:  
`setprefix [new prefix]`


#Setting
>
###Description:
Used to configure/toggle settings including **automated table unflipping** and **welcome/leave messages**, both of which are off by default. **Welcome/leave messages** are sent in the **channel** in which this command is last used and can be toggled off by leaving the message field **blank**.
###Welcome & Leave Message can include:
```markdown
[Example](Replaced with this)
[GuildName](Guild Name)
[ChannelMention](Mention to Channel)
[ChannelName](Name of the Channel)
[UserName](Name of the User)
[UserMention](Mention to the User)
# Exact case MUST be used excluding brackets #
```
###Aliases:
`set`
###Cooldown:  
`5s`
###Delete On Use:  
`false`
###Works in DM's: 
`False` 
###Usage:  
`setting tableflip`  
`setting welcome`  
`setting leave`  
`setting welcome [message]`  
`setting leave [message]`

#Toggle
>
###Description:
**Toggle commands** on/off. **Not all** commands are togglable. Check their individual **help messages for more info**.
###Aliases:
`None`
###Cooldown:  
`5s`
###Delete On Use:  
`True`
###Works in DM's:  
`False`
###Usage:  
`toggle [command name to toggle]`

---
*These commands are open source and can be found [here](https://github.com/hsiW/WishBot/tree/v6/commands/mod).*