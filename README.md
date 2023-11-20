Only files in the "complete" folder will be checked by the bot.

Name files `boss-name.md`, all lowercase and with hyphens instead of spaces.

Note that the preview on Github **will not necessarily look the same** as the messages posted to Discord.

The bot will automatically remove multiple line breaks, and add a link to the top at the end of the channel. Hyperlinks on their own line with no other text will be posted as individual messages for embed purposes. 

Some markdown is compatible with discord: https://support.discord.com/hc/en-us/articles/210298617-Markdown-Text-101-Chat-Formatting-Bold-Italic-Underline-

Single line comments should start on a new line with `// `

To keep links un-embedded, surround them with <>, e.g. `<https://oldschool.runescape.wiki>`

Embedding images can be done with an image tag of the form `<IMG path/to/image.png>`, where the path starts from the main folder. Relative paths can also be used by starting the path with `~`. Going up directories (with `../`) is not supported.

# TODO
- auto format category/channel names (done i think)
- easily linking to other channels
- check if mp4s are possible to store on github: remove reliance on streamable
- insert emojis (e.g. prayers, spellbook/runes etc. like Petcord)
- sectioned guides / TOC support
- multi line comments?
- easier mentioning people?

# DONE
- ~~easier embed images (`<IMG>` tag so only partial path is needed. `~` for relative too)~~
