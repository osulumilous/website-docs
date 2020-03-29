---
title: "เชื่อมต่อไปยับ osu!lumilous บนระบบ IRC"
reference_version: 3665844157b5cc0e576c7a671de0f50e
---

(ยังไม่พร้อมสำหรับตอนนี้)

### A quick note
Please note that IRC support may vary depending on the client you're using. Plus, our IRC server only handles **basic commands** at the moment, such as PASS, NICK, USER, PRIVMSG, NOTICE, JOIN, PART and QUIT.  
We've tested our IRC server with [HexChat](https://hexchat.github.io), a free and open source IRC client, and it turned out to work pretty well. For iOS, Mutter works just fine.

### Multiple clients and SSL support
With a recent update, we've added the ability to connect from the game and an IRC client at the same time. You can also connect with multiple IRC clients. We've also added SSL support.

### Setting up your IRC client
<br>
Once you've installed an IRC client, you can connect to o!lumilous with these settings:  

- **Host:** `osuirc.lumilous.pw`  
- **Port:** `6697` with SSL (recommended) or `6667` (without SSL)  
- **Nickname and username:** Your o!lumilous username. <u>If you have spaces in your name, replace them with underscores. For example,</u> `- Zino -` <u>becomes</u> `-_Zino_-`  
- **Server password:** Your IRC token, you can get it [here](/irc).  

There's no authentication system (SASL/NickServ, none of that). Your IRC token must be sent with the /PASS (Server Password) method. This is for backwards compatibility with the official server.

### And now?
If you have connected successfully to o!lumilous's IRC server, you can start chatting in public channels by typing `/JOIN #channel` (eg: `/JOIN #osu` to join the main channel). `/list` should show all available channels.
