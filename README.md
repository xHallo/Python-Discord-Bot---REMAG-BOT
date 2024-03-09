# REMAG BOT
A Discord Bot for your events/competitions on Discord

## Developing
To start, clone this repository, then branch out by opening a terminal and typing the following in your project folder (in the terminal):
```bash
git checkout -b <branchname>
```
Where <branchname> is the name of your branch (enter it without enclosing your branch name in the <>)

Next, you need to install the `discord-py` module, which can be downloaded by running `pip3 install discord-py` or `pip install discord-py`

Then, see the instructions below on how to run the bot for testing purposes

## Running the Bot:
This bot looks for a bot token (which can be created [on the Discord Developer Portal](https://discord.com/developers/applications)) in a file named `bot-token` in the root directory of the folder. Just paste your bot token into that file, then run `main.py` with Python 3 to run your bot. 

Instructions on how to generate a Discord Bot token can be found here: [https://discordtickets.app/getting-your-bot-token/](https://discordtickets.app/getting-your-bot-token/)

## Utilising music function.
 1. Type pip install ffmpeg and install web version of ffmpeg. Note down the full directory of the bin/ffmpeg file that you downloaded
 2. replace the executable destination in line 93 of music py with this directory in the format of D:\\?\\?\\bin\\ffmpeg
 3. Type pip install PyNaCl 
 4. Type pip install yt-dlp 4. 
 5. Run the bot and you can utilise the music functions
 6. When playing music, either paste the link of your youtube video or simply type keywords to automatically search up videos on youtube.

#
