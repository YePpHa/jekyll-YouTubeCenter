---
layout: default
title: FAQ
permalink: /faq/
---

###I have an issue. Where can I report it?
If you have an issue please first check if someone else have the same issue as you.
If not then create a new issue at the [Issue Tracker](https://github.com/YePpHa/YouTubeCenter/issues).

###Why are some video quality settings not appearing?
This is caused by YouTube limiting the availability of qualities when __DASH Playback__ is disabled.
DASH playback is available for the flash player, but is more limited for the HTML5 player.
The HTML5 player needs MSE (Media Source Extensions) to be available otherwise DASH playback would
be disabled. MSE is disabled in Firefox, but can be enabled in Firefox 31 (see [this guide]
(http://www.ghacks.net/2014/05/10/enable-media-source-extensions-firefox/) on how to enable MSE).

###When will the next version of YouTube Center get released?
A new version of YouTube Center will get released when I think that it's ready. If you're impatient
you can try the [developer version](https://yeppha.github.io/developer-version.html).

###How do I install YouTube Center on Chrome?
If you're not against using a third-party extension to load YouTube Center, you can also use [Tampermonkey]
(https://chrome.google.com/webstore/detail/tampermonkey/dhdgffkkebhmkfjojejmpbldmpobfkfo) to install the
[userscript version](https://yeppha.github.io/downloads/YouTubeCenter.user.js).

If none of the options above works for you, you can also unpack the extension and load it through the developer mode.

1. Unpack the `.crx` file by using [7-zip](http://www.7-zip.org/) or some other tool. Please note that you will have
   to choose a place where the extension would be saved at as it will be used by Chrome.
2. Visit `chrome://extensions` in your Chrome browser and make sure that the Developer mode is enabled.
3. Click on the `Load unpacked extension...` and select the folder you unpacked ealier.
4. YouTube Center should then be installed and to update YouTube Center you just have to download the `.crx` file and
   unpack it at the same location, where you then just have to click on `Reload (Ctrl + R)` link in the `chrome://extensions`
   page to make sure that Chrome loads the updated version.