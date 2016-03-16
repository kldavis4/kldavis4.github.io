---
layout: post
title: Pro Mode for YouTube Video Editor
---

![PM Logo](/images/icon128.png)

[Pro Mode for YouTube Video Editor](https://chrome.google.com/webstore/detail/pro-mode-for-youtube-vide/aenmbapdfjdkanhfppdmmdipakgacanp) is a Chrome browser extension that aims to significantly improve the existing video editor provided by YouTube.

The existing [editor](https://www.youtube.com/editor) is conceptually a great idea. You can upload all of your raw video directly from your device(s) and then go back later and produce final polished and edited videos. It is a good video editing option if you happen to be using a Chromebook. The problem with it is that it becomes unwieldy as your videos become longer and more complex. The first thing you notice when you start using it is that every time you do something the preview video player will start playing. This leads to having to click pause on the player whenever you make any changes. When you edit a clip and close it, the player will automatically start playing from the beginning which can cause you to lose your place. Aside from this, the editor requires a lot of clicking around to do any editing and doesn't provide much in the way of keyboard support. The Pro Mode extension aims to correct these deficiencies and add additional functionality where it makes sense.

## Playback Control

The Pro Mode extension takes control of the preview player and maintains a separate playback state that is controlled via a separate playback button (or the spacebar) and a slider. The extension will intercept any playback events and keep the player in a paused state until the user hits the play button. The slider also controls scrolling of the clip timeline. This allows the user to position the timeline and it will remain locked there while making changes. The slider will also seek the player when playing back the video preview.

## Keyboard Hotkeys

### UI Controls
 - The `c` key will close the currently selected clip.
 - Numbers `1-6` on the keyboard will select from the various editor tabs (Video Clips, Audio, Transitions, etc).
 - `s` will alphabetically sort the photos on the photo tab. This comes in handy after adding new photos or reloading the page (which causes the photos to get out of order).

### Navigation

 - The arrow keys can be used to navigate forward and backward on the clip timeline.
 - The `.` key selects the next clip on the timeline. If no clip is currently selected, it will select the first clip.
 - The `,` key selects the previous clip on the timeline. If no clip is currently selected, it will select the first clip as well.
 - The `[` and `]` will scroll the timeline to the first and last clip, respectively.
 - If a clip is currently selected, the `p` key will scroll the timeline to the beginning of that clip. Pressing it again will scroll to the end of the selected clip. This is most useful when you are zoomed in on the timeline and the current clip's start or end is not visible.

### Editing

 - The `k` key will toggle the Pan & Zoom effect on the currently selected clip.
 - The `+` key increase the currently selected clip's length by 1 second. This is most useful for photo clips, as video clips can't be increased beyond their original duration.
 - The `-` key decreases the currently selected clip's length by 1 second.

## Some Caveats

The existing YouTube video editor appears to be largely forgotten and may be replaced or removed at anytime. When that happens the Pro Mode extension will likely stop working. If they make any changes (such as an HTML5 preview player) the extension will probably be affected as well. Ideally, Google would continue to improve the product and make the Pro Mode extension unnecessary. For now the Pro Mode extension makes the editor into quite a viable cloud video editing platform.

If you are interested in seeing how it works, please check out the demo video below:

[![Pro Mode Extension Demo](http://img.youtube.com/vi/5FshFrRcFrw/0.jpg)](http://www.youtube.com/watch?v=5FshFrRcFrw)
