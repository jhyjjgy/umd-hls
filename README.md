# umd-hls

umd-hls is a simple python tool that you can use to download your favourite movies and series locally on your computer.

note: much of the tool requires a tmdb api key, which is free to obtain here: https://www.themoviedb.org/settings/api

a lot of the tool is vibe-coded, because this was more of a personal project and i don't have the time or extended knowledge in js or css to create something like this, so don't go after me

## install

please install the following requirements using either `pip install -r requirements.txt`, or manually installing:

- requests
- pyperclip
- pywebview
- playwright
- yt-dlp
- rich

after installing the python packages, you may also need to run:

```bash
playwright install chromium
playwright install firefox
playwright install chromium-headless
playwright install firefox-headless
```

if you're on windows, make sure microsoft edge webview2 runtime is installed as well.

## setup

you will need a tmdb api key for a lot of the tool's functionality.

you can get one here:

https://www.themoviedb.org/settings/api

once you have it, place it either inside of the settings page in the app, or inside your config.json file which is generated on first run

## usage

once everything is installed, you can run umd.exe and begin downloading!

## contact

if you have any questions or suggestions for future releases, feel free to contact me on discord:

```bash
jhyjjgy
```
