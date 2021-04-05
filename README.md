# Nuking Discord Server Bot/Nuke Bot
* ZETO is a nuke bot. All commands will be focused on nuking-related.

* We have combined threading, queue, requests, and discord.py API to make the commands run as fast as possible. If you are seeing rate limiting logged in your console while using this script, then that is simply because <ins>it runs too fast</ins>.

* Python version 3.8.0 or higher is required if you are going to run the file from source code.


## Check list for setting up everything
1. Download the whole thing as a zip.
2. Get a discord profile(token) for the bot.
3. Make a configuration file with `BuildingKIT.html`.
4. Drag the configured json file next to the executable file(The prebuilt verison)
5. Run the executable, and it should give you a bot invite link after the bot is ready. If the console closed by itself that means there's something wrong with the code and please report the issue to this github page.
6. (Optional) If the bot is asking for a path-to-the configuration file, you enter a local path or full path for the config file.


## Common errors

1. PrivilegedIntentsRequired (non-selfbot users only)
[![9977.png](https://i.postimg.cc/9fjCQNsh/9977.png)](https://postimg.cc/gx4fM4YS)
Solution: Turn on the required 2 buttons . https://i.imgur.com/XJvizxO.png

2. Unreadable json formatting
[![886.png](https://i.postimg.cc/766cH3P4/886.png)](https://postimg.cc/PLgKK88V)
Solution: This error means that you have an/multiple error(s) in your default.json file, it can be caused by missing/extra commas, brakets, quotes, and the like. You can use https://jsonlint.com/?code= to check your `default.json` file.

3. Litterary crashed when opening ZETO.exe
Causes: It might be caused by anti virus that quarantined this program, old versions of python (needs to be v3.8.0 or higher), old versions of packages (update your discord.py with pip!), didn't install any required packages at all.
Solution: Update everything to the latest version, and try turning off anti virus. If you are still having an issue, you should report it in this github page right away.

# Disclaimer
## I, am in no way responsible for any actions that you may make using this software or if something happends with your discord account. You take full responsibility with any action taken using this software. Please take note that this application was designed for educational purposes and should never be used maliciously. By downloading the software or source to the software, you automatically accept this agreement.
