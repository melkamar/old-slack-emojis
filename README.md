# Old Slack Emojis

Bring back Android emojis to Slack on Mac!

Forked from [IvyBits's old-slack-emojis](https://github.com/IvyBits/old-slack-emojis). The original project restores Apple emojis, this project does the same but with Google emojis.

## What?
Slack used to offer an option to choose which set of emojis to use in their desktop client. For some 
reason, however, they removed that option and forced Mac users to use the clearly inferior Apple-style emojis.

This fork uses a [Google emoji spritesheet](https://github.com/iamcal/emoji-data/raw/master/sheets-indexed-256/sheet_google_64_indexed_256.png)
and restores the Slack emojis to their former glory.

## Issues, troubleshooting, etc
If you find any issues or need help, please refer to the original project.

## Customization
To customize which emojis to use, edit the [old-slack-emojis.sh](old-slack-emojis.sh) script, namely
the URL in `background-image`. You can supply any spritesheet to that url, but [here](https://github.com/iamcal/emoji-data/tree/master/sheets-indexed-256) is a nice 
starting list.