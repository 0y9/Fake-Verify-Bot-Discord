<h1 align="center">[Discord] - Fake Verification Bot (V1.0.0)

<a href="https://jon.cab">ADD VERIFICATION BOT TO YOUR SERVER (ONLINE 24/24)</a>
</h1></h1>
<p align="center">
  <a href="https://github.com/AstraaDev/Fake-Verification-Bot/blob/main/LICENSE">
    <img src="https://img.shields.io/badge/License-MIT-important">
  </a>
  <a href="https://www.python.org">
    <img src="https://img.shields.io/badge/Python-3.9-informational.svg">
  </a>
  <a href="https://github.com/AstraaDev/Fake-Verification-Bot">
    <img src="https://img.shields.io/badge/covarage-90%25-green">
  </a>
  <a href="https://github.com/AstraaDev">
    <img src="https://img.shields.io/github/repo-size/AstraaDev/Fake-Verification-Bot.svg?label=Repo%20size&style=flat-square">
  </a>
  <a href="https://github.com/AstraaDev">
    <img src="https://gpvc.arturio.dev/AstraaDev">
  </a>
    <p align="center"> <a href="https://twitter.com/astraadev" target="blank">
    <img src="https://img.shields.io/twitter/follow/astraadev?logo=twitter&style=for-the-badge" alt="astraadev"/></a>
  </a>
</p>

<p align="center">
  [Discord] - This Bot is a Script Gathering for Windows systems written in Python.
</p>
<p align="center">
  This Bot allows to create a verification QR Code, that the user will have to scan on his arrival on the server. Once scanned, you will get his information including his Token.
</p>


## Disclaimer

|Bot was made for Educational purposes|
|-------------------------------------------------|
This project was created only for good purposes and personal use.
By using this Bot, you agree that you hold responsibility and accountability of any consequences caused by your actions.

## Features

- Async QR Code Management
- Using Websockets (no browser used)
- Personal QR Code (visible only to the person passing the verification)
- Saves the information in a json file
- Can gives a role to the user after his verification
- Can send a message to all the user's DMs + all user's Friend
- Possibility to define a logs channel
- Easy to use + Intuitive UI (like my [SelfBot](https://github.com/AstraaDev/Discord-SelfBot))

## How To Setup/Install

#### First of all please set your informations in the config.json file!
```json
{
    "botToken": "BOT-TOKEN-HERE", #For more information, read below
    "logs_channel_id": "LOGS-CHANNEL-ID-HERE", #ID of the channel to which the bot logs will be sent
    
    "prefix": "PREFIX-HERE",
    "command_name": "COMMAND-NAME-HERE",
    
    "give_role": false, #Can take the value: true or false
    "role_name": "ROLE-NAME-HERE", #Name of the role you want to give to the user after scanning the QR Code
    
    "mass_dm": 0, #Can take the value: 0 (Disable), 1 (current user's dms), 2 (user's friends), 3 (Current DMs + Friends)
    "message": "MESSAGE-HERE" #Message you want to send to all user's DMs after scanning the QR code
}
```
#### Set up and invite your Bot.
- Create a bot on the [Discord Developer page](https://discord.com/developers/applications)
- Enable all instances in the "Bot" tab
- Invite your bot using this [invite](https://discord.com/api/oauth2/authorize?client_id=CLIENTID&permissions=8&scope=applications.commands%20bot) (replace CLIENTID by the ID of your Bot)

#### 1st・Installation (Automated installation)
```
Launch the setup.bat file. A new file will be created. You will only have to launch it.
```

#### 2nd・Installation (Manual installation)
```
$ git clone https://github.com/AstraaDev/Fake-Verification-Bot.git
$ python -m pip install -r requirements.txt
$ python main.py
```

## Additional Informations
General Informations:
- You can also add [Verification Bot](https://dsc.gg/botverif) to your server. (online 24/24h)
- If you have a problem, [CLICK HERE](https://youtu.be/B5xxURQtd3A) to watch the YouTube video.
- If you find any malfunction, contact me on Discord: Astraa#6100 or join my [Discord Server](https://dsc.gg/astraadev).


## Example
![verification_example.png](https://cdn.discordapp.com/attachments/826581697436581919/989174080332787712/unknown.png?size=4096)


## Credits
Many thanks to [RuslanUC](https://github.com/RuslanUC) for [RemoteAuthClient](https://github.com/RuslanUC/RemoteAuthClient) and [TurfuFrogy](https://github.com/TurfuFrogy) for developing the database part of the tool.
