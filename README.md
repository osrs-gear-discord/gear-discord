Only files in the "complete" folder will be checked by the bot.

Name files `boss-name.md`, all lowercase and with hyphens instead of spaces.

Note that the preview on Github **will not necessarily look the same** as the messages posted to Discord.

The bot will automatically remove multiple line breaks, and add a link to the top at the end of the channel. Hyperlinks on their own line with no other writing will be posted as individual messages. 

Some markdown is compatible with discord: https://support.discord.com/hc/en-us/articles/210298617-Markdown-Text-101-Chat-Formatting-Bold-Italic-Underline-

Single line comments should start on a new line with `// `

To keep links un-embedded, surround them with <>, e.g. `<https://oldschool.runescape.wiki>`

To embed images, find the link in the repo e.g. `https://github.com/osrs-gear-discord/gear-discord/blob/main/from-discord-to-update/god%20wars%20dungeon/7LedMPc.png` and add `?raw=true` to the end. Bot will automatically do this in future.

# TODO
- auto format category/channel names
- easily linking to other channels
- easier embed images (parse file ending, add `?raw=true` if its an image on github). check if mp4s are possible too: remove reliance on streamable
- insert emojis (e.g. prayers, spellbook/runes etc. like Petcord)
- sectioned guides / TOC support
- multi line comments?
- easier mentioning people?
