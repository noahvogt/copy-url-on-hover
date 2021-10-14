# Copy URL on Hover
This is an extension for chromium-based browsers, so you can hover over a link and hit Y to yank it *like a real vim user*! For feedback, a pop sound will be played after copying.

If you need to copy link addresses more than once, you know how annoying it is. You need to right-click, find the "Copy link address" menu item, and click it. I find this not very efficient and overly complicated, which is why I use this extension for copying links.

*Note:* This project is a fork from [dhruvtv/copylinkaddress](https://github.com/dhruvtv/copylinkaddress).

## Installation
To try the latest dev version of the extension follow the steps below.

1. Download the source (either hit the 'ZIP' button you see at the top of the page, or use `git clone`) and extract it to a directory
2. In your chromium-based browser, launch `chrome://extensions`
3. Enable 'Developer Mode'.
4. Click 'Load Unpacked Extensions' and point to the above directory.

## Known Issue:
For my this bug is not really a problem, but for you it may be one: ***Hovering over a link will make focused text input fields lose focus*** (sometimes only temporarily - focus should be restored when you move away from the link). This fault is not yet resolved due to my very limited JavaScript Skills, but if you claim to be a "modern web developer" you are happily invited to fix this issue, of course.
