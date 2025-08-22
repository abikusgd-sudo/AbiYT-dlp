
> I will double text, **i didn't maked it up yet.**
> **Wait for updates.**

# [**AbiYT-dlp**](https://github.com/abikusgd-sudo/AbiYT-dlp)
[AbiYT-dlp](https://github.com/abikusgd-sudo/AbiYT-dlp) is a [Python](https://www.python.org/)-based tool for - downloading videos from [**YouTube**](https://youtu.be).
It supports fast downloads of single videos, playlists, and entire channels.
Additional features include format conversion, proxy support, and smooth integration with other tools.

## Basic Usage
Run the executable from the folder where it was built:

abiyt-dlp <URL>

Example:
abiyt-dlp https://www.youtube.com/watch?v=dQw4w9WgXcQ

## Environment Variable
You can also pass the URL through an environment variable:

set download_link=https://www.youtube.com/watch?v=dQw4w9WgXcQ
abiyt-dlp %download_link%

## Common Options
- --format <id>  
  Select video/audio format.
- --proxy <url>  
  Use a proxy for downloading.
- --output <path>  
  Define output file or directory.
- --extract-audio  
  Download and convert video to audio.

## Playlist Example
abiyt-dlp https://www.youtube.com/playlist?list=PL1234567890

## Channel Example
abiyt-dlp https://www.youtube.com/@channel_name

## Help
For a full list of options, run:
abiyt-dlp --help