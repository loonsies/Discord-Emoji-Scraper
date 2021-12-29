# Discord-Emoji-Scraper
Scrapes emojis of a discord server/guild and downloads them to your machine, in case you lost the original emojis for your own server or would like to download emojis for any other server to use elsewhere. Supports animated and standard emojis.

To use the program simply download the repo, extract the zip file, make sure you have python 3.9 installed, then run the .py script-: python3 emojiscraper.py. Then follow the instructions.

If you have any questions create an issue in the github repo.
If you are facing any errors, bugs or having suggestions, create an issue in the GitHub repo.
If you would like to work on any of the TODO points in the code, feel free to work on them and add a PR

**NOTE ABOUT STICKERS:** Stickers can be both static and animated picture aswell, however animated pictures use the APNG format (Animated PNG), animated stickers will end under the ".anpg", you should use convert them to gif/webp if you want to use them OR when prompted to convert stickers from apng to gif then accept it.

# WARNING! READ THIS BEFORE USING
Using this tool will break the Discord TOS since you will be scraping their website.
By using this tool, you agree that the creator of this tool has no responsibility for any action taken
against your account or against you legally.
I strongly recommend you to use an alt account's token with this tool.
I strongly recommend you to use Tor, VPN or a proxy along with this tool.

# TODO
- [x] Error handling
- [x] Add cooldown for x seconds after x amount of emoji(s) were downloaded
- [x] Sticker support
- [x] (Stickers only) Automatic conversion to conver APNG format to GIF/WEBP
- [ ] Add support for all guilds of a uid, or selection from guilds
- [ ] Built-in proxy support
- [ ] Add versions compiled to executables (like .exe for Windows, elf binaries for Linux, etc) (A GitHub deployment workflow could work here)
- [ ] UI support?
- [ ] Rewrite the code itself to be much more cleaner
- [ ] Merge both emoji and sticker scraper in a single python file

# Tutorial videos on some stuff
- How to get guild ID: https://youtu.be/6dqYctHmazc
- How to get discord account token: https://youtu.be/YEgFvgg7ZPI
