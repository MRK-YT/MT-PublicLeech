# MT-PublicLeech

##### Torrent 
##### YouTube Leecher 🤖


**A Torrent, youtube-dl Leecher, and Uploader!**

[![Deploy](https://www.herokucdn.com/deploy/button.svg)](https://heroku.com/deploy?template=https://github.com/SpEcHiDe/PublicLeech)


##### Optional Configuration Variables

* `SHOULD_USE_BUTTONS`: because, [BlameTelegram](https://t.me/c/1494623325/5603)

* `ARIA_TWO_STARTED_PORT`: The port on which aria2c daemon must START. This should be an integer, between 1001 and 65535.

* `EDIT_SLEEP_TIME_OUT`: The number of seconds to sleep after editing a Telegram message.

* `MAX_TIME_TO_WAIT_FOR_TORRENTS_TO_START`: The number of seconds to wait before auto-cancelling a dead link.

* `FINISHED_PROGRESS_STR`: any character(s) that might be displayed in the progress string.

* `UN_FINISHED_PROGRESS_STR`: any character(s) that might be displayed in the progress string.

* `TG_OFFENSIVE_API`: ~~DO NOT USE THIS~~.

* `R_CLONE_CONF_URI`:
![a help, maybe](https://telegra.ph/file/073bcbc0b69b03d75ea04.jpg)

* `R_CLONE_DEST`: Destination folder for rclone copying. Set your path starting with '/'. Or just leave '/' to set root folder

* `DOWNLOAD_LOCATION`: optional download directory, where the temporary downloads should ideally reside.

* `MAX_FILE_SIZE`: The maximum file_size allowed by Telegram [BOT API](https://core.telegram.org/bots/api), kept for [legacy purposes](https://t.me/c/1235155926/33801).

* `TG_MAX_FILE_SIZE`: The maximum file_size, allowed by Telegram [API](https://core.telegram.org/api).

* `FREE_USER_MAX_FILE_SIZE`: The file_size that was [supposed to be allowed](https://t.me/c/1331081386/147445) by the bot.

* `MAX_TG_SPLIT_FILE_SIZE`: The file_size at which it should be splitted if the file_size is greater than  `TG_MAX_FILE_SIZE`.

* `CHUNK_SIZE`: ~~not used~~, kept for [legacy purposes](https://t.me/c/1235155926/33801).

* `MAX_MESSAGE_LENGTH`: The maximum message length, allowed by [Telegram](https://t.me/c/1097142020/1224).

* `PROCESS_MAX_TIMEOUT`: ~~not used~~, kept for [legacy purposes](https://t.me/c/1235155926/33801).

* `SP_LIT_ALGO_RITH_M`: allowed values can be `hjs` or `rar`.
  - VIDEO files are not affected based on this value.

* `DIS_ABLE_ST_GFC_COMMAND_I`: setting this to ANYTHING will enable `/exec` and `/eval` commands.

## Credits, and Thanks to

* [Mrk YT](https://github.com/MRK-YT/MT-PublicLeech)
* [SpEcHIDe](https://GitHub.com/SpEcHIDe/PublicLeech)
