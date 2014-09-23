notiwatch
=========

Watch a file and send a notification when there are new data in this file.

# Dependencies:

- libnotify-bin (notify-send): `sudo apt-get install libnotify-bin`.

# Installation:

```bash
npm -g install notiwatch
```

# Usage:

```bash
notiwatch [file path]
```

It will display the text appended to the specified file to the standard output, and send a desktop notification indicating this event (might be used to watch over a log file).
