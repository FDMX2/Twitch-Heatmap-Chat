# Twitch Heatmap Chat
Single file website to check check often used messages in a twitch chat
<br>
## How it works:
  1. Enter the name of a twitch channel into the inputfield.
  2. Press connect.
  3. Wait till messages from the channels chat arrive and get sumed up.

You can switch between darkmode and lightmode with the sun/moon icon.

## Settings:
You can add a channelname at the end of the url with # to autoconnect to it like:
```
  index.html#channelname  
```

You can listen on multiple channels by seperating them with ; like:
```
  channelname1;channelname2;channelname3  
```
You can download the index.html and edit to change some presets.

## It uses:
  - bootstrap (https://getbootstrap.com/) for design 
  - twitch-js (https://github.com/twitch-devs/twitch-js/tree/master) for connection to twitch chat
  - jquery (https://jquery.com/) just cause
  - mustache.js (https://github.com/janl/mustache.js/) to escape templates for messages

## License

The MIT License

Copyright (c) 2022 FDMX2 @ github
<br>
<br>
Twitch Heatmap Chat is not affiliated, associated, authorized, endorsed by, or in any way officially connected with Twitch, or any of its subsidiaries or its affiliates. The name "Twitch" as well as related names, marks, emblems and images are registered trademarks of Twitch.
