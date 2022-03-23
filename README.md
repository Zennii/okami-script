# okami-script
Scripts for the game Okami in Japanese

The scripts are WIP and far from complete.

NOTE: I chose to keep orochi entirely in hiragana/kanji and no katakana for my own sanity. Issun drives me crazy too but his text is as-is. You can use a hiragana->katakana converter on all of his text to get the original.

# Parsing

I made my raw files with parsing in mind:

`｜` - A newline within the same dialog box. (Keep in mind this pipe is almost always the japanese version pipe.

`/` - A character who is talking as part of the same sequence

`=` - A new sequence/category of dialogs

`\n` (and none of the above) - A new dialog
