# Copy URL on Hover
This is an extension for both chromium-based and firefox-based browsers, so you can hover over a link and hit Y to copy (yank) the link address *like a real vim user* - or hit X to copy the link text! For feedback, a pop sound will be played after copying.

If you need to copy link addresses more than once, you know how annoying it is. You need to right-click, find the "Copy link address" menu item, and click it. I find this not very efficient and overly complicated, which is why I use this extension for copying links.

This project is a originally a fork from [dhruvtv/copylinkaddress](https://github.com/dhruvtv/copylinkaddress), but now does have nearly no overlap of code anymore.

## Installation

### Chromium
To try the latest dev version of the extension follow the steps below.

1. Download the source (either hit the 'ZIP' button you see at the top of the page, or use `git clone`) and extract it to a directory.
2. In your chromium-based browser, launch `chrome://extensions` (note: instead of 'chrome' it could be something different like 'brave')
3. Enable 'Developer Mode'.
4. Click 'Load Unpacked Extensions' and point to the above directory.

I will see when a chrome web store version will be available, as I don't want to show google my ID and pay them 5 USD via credit card.

If you use Arch Linux, you can check out the following packages in the AUR.

- source-based AUR package: [chromium-extension-copy-url-on-hover](https://aur.archlinux.org/packages/chromium-extension-copy-url-on-hover/)
- binary AUR package: [chromium-extension-copy-url-on-hover-bin](https://aur.archlinux.org/packages/chromium-extension-copy-url-on-hover-bin/)

### Firefox
You can add the newest via the [firefox add-on on store](https://addons.mozilla.org/en-US/firefox/addon/copy-url-on-hover).

As you cannot persistently add add-ons to vanilla firefox without using a file that is signed from mozilla, this makes it very much unusable to install a dev version. You would have to install the firefox 'developer edition', and set some about:config flags.

## Known Issue
For my this bug is not really a problem, but for you it may be one: ***Hovering over a link while having focused text input fields will not block your input of pressing X or Y*** . This is a design choice, in previous versions of this software the input was blocked, but the text field lost their focus. The current design is also not considered optimal, and may be subject to change, but it is perceived as the more intuitive behaviour. If you have a better idea, please contact me.

## Roadmap

- find a cleaner solution for the above mentioned known issue
- migrate to manifest v3
- show a popup notification when copying a link address/text
- add settings panel to toggle the sound and notification
