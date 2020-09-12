# Firefox i3 Theme

![](screenshot.png)

A theme for Firefox meant to emulate [qutebrowser](http://qutebrowser) and integrate with the i3 window manager.

## Install & configuration instructions

Before installing the theme:

1. Install the [Tridactyl](https://addons.mozilla.org/en-US/firefox/addon/tridactyl-vim/) firefox extension

2. Go in the "Customize" section of firefox and remove the new tab button from the navigation bar, and also set "Density" to "Compact".

To install the theme:

1. Go to `about:support` in Firefox.

2. Application Basics > Profile Directory > Open Directory.

3. Open directory in a terminal.

4. Create a chrome directory if it doesn't exist:

```
mkdir -p chrome
cd chrome
```

5. Copy the `userChrome.css` file from this repository to that folder

---

CSS based on [0xbiel's dotfiles](https://github.com/0xbiel/dotfiles/blob/master/userChrome.css)
