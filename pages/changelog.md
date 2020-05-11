# Changelog

[Back to home](../index.md)

## Version 2.4.4

- Changed site link in !crest command.

## Version 2.4.3

- Fixed an issue that would allow anyone to add/delete ignores, rather than just moderators.

## Version 2.4.2

- Fixed an issue that would cause requesters to be picked twice via priority requests.

## Version 2.4.1

- Fixed an issue that would cause the request list to crash if trying to override a bias setting.
- Fixed an issue that would suck the request list into the void if app was updated after saving requests.
- Added new website to CREST > About menu.
- Added badge for donators (it doesn't do anything yet don't worry).
- Most probably added a bug somewhere for Zantor to find on stream and expose.
- Fixed an issue causing purge to ignore moderators and vips.
- Fixed an issue causing whitelist button to not work with multiple selections.

## Version 2.4.0

- Resolved issues involving self-updating not updating or restarting properly.
- Resolved configuration importing issues.

## Version 2.3.0

- App should now restart to latest version, restart if not...

## Version 2.2.3

- Fixed settings upgrade issue, you'll have to manually copy the user.config file from %localappdata%/CREST to the root of the CREST folder as "last.config" for it to upgrade to this version, everything else will be automatic.
- If this confuses you, just set everything back up, future upgrades should be seamless.

## Version 2.2.2

- Fixed !list not showing link properly.
- Updated server-side list displaying requests properly.
- Fixed an issue that would prevent new lines from being written in news.
- Fixed an issue preventing hotkeys enabled checkbox being ticked on startup.
- Hopefully fixed an issue preventing settings from upgrading.
- Moved new release notifications to a publicly visible channel in the discord.
- Moved badges to their own subitem, which fixes the next 3 issues:
- Fixed an issue that allowed mods/vips/subs to request multiple times.
- Fixed an issue where purging would make mods/vips/subs get selected for deletion despite being in chat.
- Fixed an issue preventing users from removing requests.

## Version 2.2.1

- Hopefully fixed an issue where updating would still start old version.
- Fixed an issue where clicking save will ask if you wanted to... save.
- Added randomizer smart bias, each 1 in settings is an extra 10% chance of getting picked first (multiple badges do not stack).

## Version 2.2.0

- Added save confirmation dialogs for settings that are closed without pressing save.
- Added option to ignore phrases in requests.
- TTFAF is automatically ignored*.
- *not really.
- Added !crest command that provides the setup link for the bot.
- Added !list command, on a 10 minute cooldown, will generate a webpage that displays current list of requests.
- Added menu for upcoming features, so that A: I can't forget them and B: you can get hyped / give feedback.
- Fixed hotkeys not showing as enabled in menu.
- Added submenus for settings for more clarity (you can still click on the menu item itself).
- App will load previous requests (handy in case of crashes) unless specified when closed.
- Replaced inactive About menu item with changelog & news.

## Version 2.1.9

- Fixed pausing being inverted in chat.
- Reworked update method to actually show you this news!
- Fixed ignoring users actually ignore them.
- Enabled hotkey settings and actually use them.
- Fixed an issue that would cause news display to crash.
- Bot will now send crash log to staff discord.
- Made menu item change depending on twitch connection status.

## Version 2.1.6

- Fix space in help message.
- Added temp hotkeys (+/-)

## Version 2.1.5

- Added everything up to bias settings.
- List command disabled.

## Version 2.1.1

- Auto-updates.
- Split confusing settings into their own forms, much cleaner.
- Added clear all / purge requests for requests from people who are no longer in chat.
- Added links to twitter and personal discord, rather than the inactive one.

## Version 2.0.5

- Tweaked updating message.

## Version 2.0.4

- What's new will now show before restarting the app.

## Version 2.0.3

- CREST will now actually start...

## Version 2.0.2

- CREST will now warn you when updating and restart to always be running on the latest version.

## Version 2.0.1

- Fixed icon in installed applications.

## Version 2.0.0

- Initial release.
