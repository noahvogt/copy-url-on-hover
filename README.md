# Copy URL on Hover
This is an extension for both chromium-based and firefox-based browsers, so you can hover over a link and hit Y to yank it *like a real vim user*! For feedback, a pop sound will be played after copying.

If you need to copy link addresses more than once, you know how annoying it is. You need to right-click, find the "Copy link address" menu item, and click it. I find this not very efficient and overly complicated, which is why I use this extension for copying links.

*Note:* This project is a fork from [dhruvtv/copylinkaddress](https://github.com/dhruvtv/copylinkaddress).

## Installation

### Chromium
To try the latest dev version of the extension follow the steps below.

1. Download the source (either hit the 'ZIP' button you see at the top of the page, or use `git clone`) and extract it to a directory.
2. In your chromium-based browser, launch `chrome://extensions`
3. Enable 'Developer Mode'.
4. Click 'Load Unpacked Extensions' and point to the above directory.

I will see when a chrome web store version will be available, as i don't want to show give google my ID and pay them 5 USD via credit card.

### Firefox
You can add the newest via the [firefox add-on on store](https://addons.mozilla.org/en-US/firefox/addon/copy-url-on-hover).

As you cannot persistently add add-ons to vanilla firefox without using a file that is signed from mozilla, this makes it very much unusable to install a dev version. You would have to install the firefox 'developer edition', and set some about:config flags.

## Known Issue
For my this bug is not really a problem, but for you it may be one: ***Hovering over a link will make focused text input fields lose focus*** (sometimes only temporarily - focus should be restored when you move away from the link). This fault is not yet resolved due to my very limited JavaScript Skills, but if you claim to be a "modern web developer" you are happily invited to fix this issue, of course.
