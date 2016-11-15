#Chan
>
###Description:
**Create**, **Copy**, **Edit** & **Delete** **Global** & **Local** Chans. Chans are **created** by using `chan [name] [content]` and may be **edited** by the Chan **author** by doing `chan [name] [new content]` on an existing Chan.
###Additional Chan Functions
```markdown
[list](Lists the local chans, lists global chans if no local chans exist)
* chan list & chan list global(to show global chans if local exist)
*
[delete](Deletes then mentioned chan, must be the chan author)
* chan local delete [chan name] & chan global delete [chan name]  
*
[copy](Allows you to copy a global chan to local and vice versa)
* chan copy [chan name] local global [optional new name] & chan copy [chan name] global local [optional new name]  
* chan copy [chan name] [from here] [to here]
* Copies from one chan location to another, may take an optional name if chan already exists  
*
[global](Used to specify the global version of the chan)
* chan global [chan name] & chan global [chan name] [new content]
* Use a global chan if a local one of the same name exists and edit a global chan
```
###Aliases:
`c`
###Cooldown:  
`5s`
###Delete On Use:  
`False`
###Works in DM's:  
`True`
###Usage:  
`chan [chan name]`  
`chan global [chan name]`

#ChanInfo
>
###Description:
Returns **info** about the passed chan. Returns the **chan author**, **creation date**, & wheather it is **global**.
###Aliases:
`cinfo`
###Cooldown: 
`5s` 
###Delete On Use:  
`False`
###Works in DM's: 
`True`
###Usage:  
`chaninfo [chan name]`

#GetOldChans
>
###Description:
Returns a **JSON** containing the **old chans** of the server.
###Aliases:
`None`
###Cooldown:  
`60s`
###Delete On Use:  
`False`
###Works in DM's:  
`False`
###Usage:
`getoldchans`  

---
*These commands are currently closed source.*

