# Changelog

## v1.2.4beta -> v1.2.6beta
* Fixed Version Number Regex

## v1.2.3beta
* Translation: added more translation areas.
* Production Bot: Now working like expected. After Production finished, the page reloads 2-3 times which I can't prevent because its necessary.
* Next Bot I implement is the Incident-Bot:
	* Will have a Setting to customize the minimum incidents which should be availible until the bot collects it

## v1.2.2beta
* Production: now shows timer how long its running until finished (CPU usage reduced by 100%)
* Overview: Executiontime is back in the hood. How long did the Bot run again?
* Translation completed in German and English
* Bots: Currently the Bot is under development. Currently, if you activate him, he will start new production as soon as you collect them. I am on it to fix the problems I have with a working bot. After fixing this Bot, I will work on the next one (which will be one for Recurring-Quests, but can take a long time, because I will keep some sort of customization with out adding to much complexity)

If the language in your mother tongue is missing. Please clone the project, create a new JSON-File with the language code (de -> german, en -> english, fr -> french and so on) and make a Pullrequest with the new one. If you dont know how to do it, just open a Issue with the title:
[TRANSLATE] [*your language code*]
and no more text.
I will contact you back.

## v1.2.0beta
* temporary fixed high CPU usage (due to updating frontend from backend)
	* to this fix, I had to remove the timers which updated the "Running since" and "Productionstate"
	* I am working on a better way of implementing this again

## 1.1.0beta
* Added international server choice
	* Select the server where you are playing on at the start (en,de,beta(zz),...)
## 1.1.0beta
* Initial Release
