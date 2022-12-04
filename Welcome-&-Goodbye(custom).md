---
# Custom Welcome & Good-Bye for Specific Groups.
---

- ***To turn on events(welcome & good-bye) in Specific Group.***

- It's off by default.
```
.act events
```
- ***To turn off events(welcome & good-bye) in Specific Group.***

```
.deact events
```
- ***To set custom Welcome.***
- use:
   @user => mention user
   @gname => Group Name
   @count => Member count
   @pp => for adding profile picture in welcome.
```
.setwelcome @pp
Hey @user
Welcome in @gname
Member count @count
```
- ***To turn off events(welcome & good-bye) in Specific Group.***

```
.setgoodye @pp
Uh @user,
Left @gname
Member count @count
```
