# Provisional RID Registry
## Reference Identifier (RID) Table

Context | Reference | Example
--- | --- | --- 
http | //\<host>[:\<port>]\<path>[?\<query>][#\<fragment>] | http://block.science 
https | //\<host>[:\<port>]\<path>[?\<query>][#\<fragment>] | https://block.science  
orn:\<namespace> | (see table below) | (see table below) 

## Object Reference Name (ORN) Table

### **IN ACTIVE USE:**
Namespace | Reference | Example
--- | --- | --- 
slack.workspace | \<team_id> | orn:slack.workspace:TA2E6KPK3
slack.channel | \<team_id>/\<channel_id> | orn:slack.channel:TA2E6KPK3/C0593RJJ2CW
slack.message | \<team_id>/\<channel_id>/\<ts> | orn:slack.message:TA2E6KPK3/C0593RJJ2CW/1731942828.456509
slack.user | \<team_id>/\<user_id> | orn:slack.user:TA2E6KPK3/U04PMMHGERJ

### **PROPOSED:**
Namespace | Reference | Example
--- | --- | --- 
discord.guild | \<guild_id> | orn:discord.guild:845050172501262337
discord.channel | \<channel_id> | orn:discord.channel:845050173074702368
discord.message | \<channel_id>/\<message_id> | orn:discord.message:845050173074702368/1283346875046563891
discord.user | \<user_id> | orn:discord.user:151856436710866944
hackmd.note | \<note_id> | orn:hackmd.note:GL3924k5SOS0EGNLNug8gg
hackmd.team | \<team_path> | orn:hackmd.team:blockscience
hackmd.user | \<user_path> | orn:hackmd.user:lukvmil

## Contribution
*Note: when adding new entries, escape angle brackets by adding a backslash before the "tag" like this: `\<tag>`*

If you are adding a new URI scheme, put in the RID Table, if you are adding a new ORN type add it to the ORN Table. The reference column should show the format of the right hand of the identifier. Use angle brackets `<>` to include variables or fields, and enclose segments in square brackets `[]` if they are optional. This representation is pretty limited and should be replaced by something better when the need arises. This document is intended to coordinate implementation of RID types, not authoritatively define them (yet).
