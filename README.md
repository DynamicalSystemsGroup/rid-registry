# Provisional RID Registry
### **ACTIVE:**

Type | Reference | Example
--- | --- | --- 
http | //\<host>[:\<port>]\<path>[?\<query>][#\<fragment>] | http://www.dynamicalsystemsgroup.com 
https | //\<host>[:\<port>]\<path>[?\<query>][#\<fragment>] | https://www.dynamicalsystemsgroup.com  
orn:koi-net.node | \<name>+\<hash> | orn:koi-net.node:coordinator+a19c00ac35408bd21e75a7c044d9a05f7193184a19e24e2428dd012b311eda1f
orn:koi-net.edge | \<id> | orn:koi-net.edge:4a1620d3d703aa07ba0852839c8f95173e44b87e40309fbb71e74fd8021f5b85
orn:slack.workspace | \<team_id> | orn:slack.workspace:TA2E6KPK3
orn:slack.channel | \<team_id>/\<channel_id> | orn:slack.channel:TA2E6KPK3/C0593RJJ2CW
orn:slack.message | \<team_id>/\<channel_id>/\<ts> | orn:slack.message:TA2E6KPK3/C0593RJJ2CW/1731942828.456509
orn:slack.user | \<team_id>/\<user_id> | orn:slack.user:TA2E6KPK3/U04PMMHGERJ
hackmd.team | \<team_path> | orn:hackmd.team:dynamicalsystemsgroup
orn:discord.guild | \<guild_id> | orn:discord.guild:845050172501262337
orn:discord.channel | \<channel_id> | orn:discord.channel:845050173074702368
orn:discord.message | \<channel_id>/\<message_id> | orn:discord.message:845050173074702368/1283346875046563891
orn:discord.user | \<user_id> | orn:discord.user:151856436710866944

### **PROPOSED:**
Type | Reference | Example
--- | --- | --- 
hackmd.user | \<user_path> | orn:hackmd.user:lukvmil

## Contribution
*Note: when adding new entries, escape angle brackets by adding a backslash before the "tag" like this: `\<tag>`*

If you are adding a new URI scheme, put in the RID Table, if you are adding a new ORN type add it to the ORN Table. The reference column should show the format of the right hand of the identifier. Use angle brackets `<>` to include variables or fields, and enclose segments in square brackets `[]` if they are optional. This representation is pretty limited and should be replaced by something better when the need arises. This document is intended to coordinate implementation of RID types, not authoritatively define them (yet).
