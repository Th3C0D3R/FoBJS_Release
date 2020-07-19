
# Forge of Empires Bot [![Build Status](https://travis-ci.com/Th3C0D3R/FoBJS.svg?token=RwyETmryp2rK95JJsgYq&branch=master)](https://travis-ci.com/Th3C0D3R/FoBJS)


## Sadly, I have currently no time to work on it. As mentioned in 1.2.4beta changes: RL stuff and other projects (FoE-Helper extension)

Since some time I worked on a Forge of Empire Bot to interact with the game while doing something other and not looking on production progress and motivate/polish others.

So after looking at the foe-decrypter which decrypt the Adobe Flash version of the game ([foe-decryption](https://github.com/m3talstorm/foe-decryption)) and this Bot ([foe-bot](https://github.com/m3talstorm/foe-bot))
I decided to try myself to get to a point where I can send my own requests.

tldr;

Here is my Bot made with the ElectronJs Framework (Javascript, HTML and CSS of course.

Its not perfect (most likely because I suck in HTML, CSS and Javascript) but the it is working, its all about the working stuff, right? Right?

## How to use (precompiled)

1. download the Bot from the [release](https://github.com/Th3C0D3R/FoBJS_Release/releases) section.
There will be a linux (fobjs_linux.rar) and windows (fobjs_windows.rar) version
2. extract the containing folder to a destination of your choice
3. - On Windows: run the fobjs.exe
    - On Linux: ***Instruction to be added***
4. If you run the Bot the first time, or after you logged out of the Bot, it asked you to select your server where you are playing on. Just enter the corresponding letters (de for german server, beta, for beta-server and so on...)
5. Enter your login credentials, first ***Username***, hit "Return", enter your ***Password***, hit "Return" again. It will log you into Forge of Empires and collect the worlds your are playing on.
6. After that you have to enter the world you want to bot on. just enter the WorldID (de5/en6,etc) or the world name (it will display both and accept both)
7. The Bot will load and request all data from the server and will prepair the bot.
8. If everything was successfull loaded, you should see the Overview just like in the pictures below

## How to use ([source](https://github.com/Th3C0D3R/FoBJS/) )

1. Clone Repo,
2. install all deps using 'npm i .'
3. build exe or run from source (running from source with: "electron ." (the dots are needed)
4. profit

## Support

If you have problems with the bot, please consider open Issue with the following information:
* Which Server are you playing on (de/en/beta(zz)/...)
* What OS you run
* Are there any errors on the screen
* Expected behavior
* Actual behavior

Then I can help 

## Preview

#### Overview
![Overview](https://github.com/Th3C0D3R/FoBJS_Release/blob/master/imgs/Overview.png?raw=true)
#### Other Players
![Other Players](https://github.com/Th3C0D3R/FoBJS_Release/blob/master/imgs/Other%20Players.png?raw=true)
#### TaverInfo
![Other Players](https://github.com/Th3C0D3R/FoBJS_Release/blob/master/imgs/Taverninfo.png?raw=true)
#### Bots
![Bots](https://github.com/Th3C0D3R/FoBJS_Release/blob/master/imgs/Bots.png?raw=true)
#### Production
![Production](https://github.com/Th3C0D3R/FoBJS_Release/blob/master/imgs/Production.png?raw=true)
#### Manually
![Manually](https://github.com/Th3C0D3R/FoBJS_Release/blob/master/imgs/Manually.png?raw=true)

## Translation

If the language in your mother tongue is missing.
Please clone the project, create a new JSON-File with the language code (de -> german, en -> english, fr -> french and so on) and make a Pullrequest with the new one.
If you dont know how to do it, just open a Issue with the title:
[TRANSLATE"] [*your language code*]
and no more text.
I will contact you back.

### Donation
Just to support my work. All donations are going to keep up the server were I test the Bot 24/7.


| Paypal |
| ------ |
| [![](https://www.paypalobjects.com/en_US/i/btn/btn_donateCC_LG.gif)](https://www.paypal.com/cgi-bin/webscr?cmd=_s-xclick&hosted_button_id=G2D7BK2E7WJZY) 

License
-------
Copyright 2020 - Th3C0D3R
