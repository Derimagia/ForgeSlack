# ForgeSlack
Connects Minecraft Forge -> Slack

*1.10.2 branch*

## Features
1. Posts Slack Messages when people in-game talk. Thanks to [MCAPI](https://mcapi.ca/), this includes a picture of the User.
2. Posts Slack Messages when people join/leave the server.
3. Posts Minecraft Messages in Slack. 
4. Posts Minecraft Achievements to Slack
4. Posts Minecraft Death messages to Slack

## Installation

1. Place in mods directory. Start/Stop server to generate Config file.
2. Get a token through. Configure the token in the config file. It will start with something like "xoxb-".
3. Create "Outgoing WebHook" on Slack. Configure using the URL of your minecraft server with the port configured in the file. Example: http://33.33.33.33:8085/. Add the Token provided here to the Config file.

## License
MIT