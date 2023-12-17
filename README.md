# minecraft_bedrock_server_tips
This contains tips and trick concerning minecraft bedrock server and cross platform play

# Issues
* compression snappy does NOT seem to work for Nintendo Switch client, do not use it
* local LAN server will be NOT visible in Nintendo Switch client, even if it is visible in Windows Minecraft Bedrock client
  * there is no way around it
* local LAN server will appear and disappear in Windows Minecraft Bedrock client depending on weather and moon position
  * so sometimes it is visible and sometimes not
  * probably it has something to do with the value of the second opened UDP port
  * solution: restart the server a few times, until it appears

# Use
* on Windows Minecraft Bedrock client (and maybe Xbox too), the IP can be just added, and server can be connected
  * sometimes the server just appears in the second tab "Friends" (as LAN-Games, but not always)
* Nintendo Switch client due some really annoying reasons has access to only 5 servers, and no other can be added, it also does not see the LAN-Games
  * there are relatively easy ways to do DNS workaround
  * there are some external DNS servers allowing connection to any server (I do not like to use external services)
  * I will describe my simple approach later
