# Firefox i3 Theme

![](screenshot.png)

A theme for Firefox meant to emulate [qutebrowser](http://qutebrowser.org) and integrate with the i3 window manager.

## Install & configuration instructions

Before installing the theme:

- Install the [Tridactyl](https://addons.mozilla.org/en-US/firefox/addon/tridactyl-vim/) firefox extension

- Go in the "Customize" section of firefox and set "Density" to "Compact".

- [Enable userChrome.css in about:config](https://www.youtube.com/watch?v=levqpofIJ_k&feature=youtu.be)

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


For best results, install the [Jetbrains Mono](https://www.jetbrains.com/lp/mono/) font

---

CSS based on [0xbiel](https://github.com/0xbiel/)'s dotfiles
