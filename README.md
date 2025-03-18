# give-money-bot
Aiogram3 bot for give MusteryWorld`s money
- download [mcc](https://github.com/MCCTeam/Minecraft-Console-Client/releases)
- open .exe
- close it
- open MinecraftClient.ini
- go to end
- change
```
# Remotely control the client using Web Sockets.\n# This is useful if you want to implement an application that can remotely and asynchronously execute procedures in MCC.\n# Example implementation written in JavaScript: https://github.com/milutinke/MCC.js.git\n# The protocol specification will be available in the documentation soon.
[ChatBot.WebSocketBot]
Enabled = true
Ip = "127.0.0.1"                            # The IP address that Websocket server will be bound to.
Port = 8043                                 # The Port that Websocket server will be bounded to.
Password = ""                               # A password that will be used to authenticate on thw Websocket server (It is recommended to change the default password and to set a strong one).
DebugMode = true                            # This setting is for developers who are developing a library that uses this chat bot to remotely execute procedures/commands/functions.
AllowIpAlias = false                        # Allow IP aliases, such as "localhost" or if using containers then the container name can be used...
```
- save & close it
- open .exe
- go to your server
- start bot.py
