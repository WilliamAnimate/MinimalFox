<!-- markdownlint-disable MD041 MD026 -->

![hero](docs/hero.png)

*Pictured: Minimal Fox, [Catppuccin-mocha-pink](https://addons.mozilla.org/en-US/firefox/addon/catppuccin-mocha-pink/) and [Catppuccin-latte-pink](https://addons.mozilla.org/en-US/firefox/addon/catppuccin-latte-pink/) respectively*.

# A minimalist's Firefox.

MinimalFox removes most of the clutter in your toolbar, even tabs.

## Table of contents

- [Who is this for?](#who-is-this-for)
- [Installation](#installation)
- [Further configuration](#further-configuration)
- [Attribution](#attribution)

## Who is this for?

MinimalFox is targeted at tiling window manager users, since they already control what they see with the keyboard in the first place.

## Installation

If you do not know where to put `userChrome.css` and `userContent.css` files, try following this guide: [https://www.howtogeek.com/334716/how-to-customize-firefoxs-user-interface-with-userchrome.css/](https://www.howtogeek.com/334716/how-to-customize-firefoxs-user-interface-with-userchrome.css/)

## Further configuration

Decluttering your toolbar further can be done with built-in Firefox UIs:

1. Right click any of the icons on your toolbar.
1. Select `customize toolbar`.
1. Drag and drop items as needed.

Should you want to enable a larger drag space, you will have to configure the `userChrome.css` file, as follows:

1. Locate `--minimalfox-dragspace: 0px;` in the new `userChrome.css` file. This is usually at the top.
1. Change the value, for example: `--minimalfox-dragspace: 7px;`.
1. Close and reopen your browser until you find a comfortable fit.

> [!NOTE]
> On Windows, any dragspace lower than `7px` may not be draggable.
>
> If you use KDE Plasma, you can try holding the `super` key while dragging any part of the application instead.
>
> If you use tiling window managers, there is no point in changing this.

## Attribution

Attribution can be found within the css files themselves, usually linking to where I got that specific style from. The rest were made by myself with the browser toolbox.
