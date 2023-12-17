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
