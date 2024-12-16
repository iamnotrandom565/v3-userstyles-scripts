# README thing

## FAQ

- Q: How do I install userstyles?
- A: First, go to your preferred browser extensions store (Chrome Web Store for Chromium, Mozilla Add-ons for Firefox), search up "Stylus", click on the first result, and click install. Then, go to a preferred userstyle here, click on the "view raw file" button, and it should bring you to Stylus' userstyle installation page, click install.

- Q: This userstyle doesn't work!1!
- A: Do you have Vorapis 3? Then install it from [here](https://vorapis.pages.dev) and follow the instructions. Some of my userstyles also require StarTube. But to install that, you need to install [TamperMonkey](https://www.tampermonkey.net), or any other userscript manager that you like. Then, search "StarTube" on [Greasyfork](https://www.greasyfork.org/en), click on the first or second result, and click "install". Then it should bring you to the userscript installation page, click install, and you're done.

- Q: Can you make this userstyle???
- A: I'll consider it, but if you spam that, then unfortunately I won't.

  

## yt2007player.user.css

This userstyle is supposed to bring back the YouTube player from late 2006 to early 2008.

It doesn't require StarTube to function, but I recommend doing so, for simplicity and looks.

If you find a bug, which are probably many, first check at the bottom of the code if I already found it, then report it to the Issues tab.

Also, HUGE thanks to EricKrouss for making the [HTML5 2007 YouTube video player](https://github.com/EricKrouss/2007-YouTube-Player-HTML5/tree/main)! Without it, this userstyle won't exist.

### Version History

*The current version is: Alpha 11216 (December 16 2024)*

- ### Alpha 11215
> First version

- ### Alpha 11216
> A minor update
- When the scrubber is hovered, it turns red.

## ytchannels1.user.css (previously channels2a.user.css)

This user style is supposed to bring back Channels1, used from mid 2006 to late 2009.

This userstyle requires StarTube. Follow the instructions at the top, then open the StarTube settings, and enable channels3 by either clicking on a layout that's early 2013 and below, or going to "Channel layout" and enablind channels3 from there.

If you find a bug, which are probably many, first check at the bottom of the code if I already found it, then report it to the Issues tab.

### Version history

_The current version is: Alpha 11215 (December 15 2024)._

- ### Alpha 1116
> First version

- ### Alpha 11130
> Added similar customizations to ytchannels2.user.css
>
> Plenty improvements

- ### Alpha 11130.1
> Gone base64

- ### Alpha 11215
> Renamed to ytchannels1.user.css

## ytstargazerplayer.user.css

This user style is supposed to bring back YouTube's Stargazer video player (used from early 2008 to mid 2010).

This userstyle doesn't require StarTube, but for simplicity and looks, I recommend doing so.

If you find a bug, first check at the bottom of the code if I already found it, then report it to the Issues tab.

### Version history

_The current version is: Alpha 1116 (November 6 2024)._

- ### Alpha 1111
> First version

- ### Alpha 1111.1
> Added proper credit

- ### Alpha 1116
> Gone base64

- ### Alpha 11129
> Made the video settings accurate (you have to enable it through the settings)
>
> Also made the timestamps when you scrub the video accurate
>
> Fixed some bugs

## ytchannels2.user.css (previously ytaozorachannels.user.css)

**Note that I'm currently rewriting this userstyle from the ground up to fix bugs and compatibility issues, sorry for the lack of updates.**

This user style is supposed to bring back the YouTube Channels 2.0 layout (from late 2009 to early 2012).

This userstyle requires StarTube. Follow the instructions at the top, then open the StarTube settings, and enable channels3 by either clicking on a layout that's early 2013 and below, or going to "Channel layout" and enablind channels3 from there.

If you find a bug, first check at the bottom of the code if I already found it, then report it to the Issues tab.

### Version history

_The current version is: Alpha 11215 (December 15 2024)._

- ### Alpha 1713
> First version

- **Alpha 1715**
> Added channel search (non functional)

- **Alpha 1717**
> Search now works!
>
> The videos sidebar is now more accurate

- **Alpha 11013**
> Finally a new update after idk how long lol
>
> Added options to modify the channel's colors
>
> Modified some other things in the code to make it compatible with the new V3 and StarTube updates

- **Alpha 11215**
> Renamed to ytchannels2.user.css

## yt2010comments.user.css

**After StarTube version 2.2 came out, this userstyle is now obsolete**

This user style file is supposed to bring back the style of the old YouTube comments section style (around 2010 to 2012).
It requires the Vorapis 3 extension to function, and it works best with StarTube's Aozora, Epic Panda or Cosmic Panda layouts with expCommentsFullWidth turned off.

### Version history

_The current version is: Dev 1715 (15 July 2024)._

- ### Alpha 1206
> First version

- **Alpha 1206.2** Added a bunch of changes under the hood (note that it has a bug that places the reply button to the bottom)
  
- **Alpha 1621**
> The version numbering has been changed;
>
> The reply button position bug (refer to the post in Issues) has been fixed;
> 
> Buncha more changes to make it more accurate.

- **Alpha 1621.2**
> The like & dislike thread icons are now similar to their 2010 counterparts;
> 
> A new settings menu has been added, although it doesn't do anything _yet_.

- **Alpha 1622**
> You can finally comment properly (sorta);
>
> Comment & reply boxes are now finally resizable;
>
> The cancel and comment buttons have been changed to their 2011 counterparts;
>
> Your channel profile picture is no longer visible in the topbar.



- ### Dev 1626
> The user style is now out of the alpha phase!
> 
> Fixed A BUNCH of bugs
> 
> Cosmic Panda AND Epic Panda layouts have been added! (even though they're the same)
> 
> Added more options in the settings
> 
> Removed live chat (for now)

- **Dev 1626.2**
> Some changes that I forgot to make before
>
> Live chats can be enabled by clicking a button in the settings

- **Dev 1626.3**
> Changed part of a line of code
>
> That's it!

- **Dev 1627**
> Solved a bug mentioned in Issues

- **Dev 175**
> Replaced "Share your thoughts" to "Respond to this video..."

- **Dev 177**
> Fixed a bug

- **Dev 1712**
> Changed the copyright
> 
> Changed "Up Next" to "Suggestions"
> 
> Cancel and Post buttons don't overlap with other comments

- **Dev 1715**
> Comments can now be longer than 500 characters (enabled by default)
>
> You can now replace the mail icon with something else (only Mail works)

## ytcosmicchannels.user.css

**Please note that since the next StarTube update will include Cosmic Panda-styled channel pages, this will become obsolete soon.**

**Please also note that it's really unfinished, please report bugs in Issues**

This userstyle makes channel pages look like their 2012 counterparts.
It requires Vorapis 3 to function, and works best with StarTube's Cosmic Panda layout.
_The current version is: 174._
