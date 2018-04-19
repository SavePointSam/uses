# SavePointSam/uses

A collection of all the tools I use and their settings.

## Table of Contents

* [keyboard](#keyboard)
  * [primary](#primary)
  * [gaming](#gaming)
  * [mats](#mats)
* [mouse](#mouse)
  * [macOS](#macos)
  * [Windows / Linux](#windows--linux)
  * [gaming](#gaming-1)
* [headphones](#headphones)
  * [primary](#primary-1)
  * [secondary](#secondary)
* [terminal](#terminal)
  * [shell](#shell)
  * [emulator](#emulator)
* [fonts](#fonts)
  * [ASCII](#ascii)
  * [non-ASCII](#non-ascii)
* [text editor](#text-editor)
* [utilities](#utilities)
  * [macOS](#macos-1)

## keyboard

### primary

[WASD Keyboards - CODE 104-Key Mechanical Keyboard - Cherry MX Blue](http://www.wasdkeyboards.com/index.php/products/code-keyboard/code-104-key-mechanical-keyboard-2744.html)

* black case
* 0.4mm Travel Reduction, 40A-R Blue O-Rings

[Razer Ergonomic Keyboard Rest - Standard Fit](https://www.razer.com/Accessories/Razer-Ergonomic-Keyboard-Rest-/p/RC21-01020100-W3M1)

### gaming

[Razer - BlackWidow Chroma V2](https://www.razer.com/gaming-keyboards-keypads/razer-blackwidow-chroma-v2)

### mats

[Inked Gaming - Panoramic Desk Pad - Custom](https://www.inkedgaming.com/products/panoramic-desk-pad-36-x-11)
[Corsair - MM300 Anti-Fray Cloth Gaming Mouse Pad — Extended](https://www.corsair.com/us/en/Categories/Products/Gaming-Mousepads/Cloth-Textile-Surface-Mousepads/MM300-Anti-Fray-Cloth-Gaming-Mouse-Pad-%E2%80%94-Extended/p/CH-9000108-WW)

## mouse

### macOS

[Apple - Magic Mouse 2 - Space Gray](https://www.apple.com/shop/product/MLA02LL/A/magic-mouse-2-silver)

### Windows / Linux

[Logitech - Marathon Mouse M705](https://www.logitech.com/en-us/product/marathon-mouse-m705)

### gaming

[Corsair - Sabre RGB](https://www.corsair.com/ww/en/Categories/Products/Gaming-Mice/MOBA-Strategy-%26-Action-Mice/Sabre-RGB-Gaming-Mouse/p/CH-9303011-NA)

## headphones

### primary

[Apple - AirPods](https://www.apple.com/shop/product/MMEF2AM/A/airpods)

### secondary

[Bose - SoundSport® in-ear headphones – Apple devices - Frost](https://www.bose.com/en_us/products/headphones/earphones/soundsport-in-ear-headphones-apple-devices.html)
[Beats Pro Over-Ear Headphones - Black](https://www.apple.com/shop/product/MHA22AM/B/beats-pro-over-ear-headphones-black)

## terminal

### shell

[fish](https://fishshell.com/) with [oh-my-fish](https://github.com/oh-my-fish/oh-my-fish) using the [pure](https://github.com/oh-my-fish/oh-my-fish/blob/master/docs/Themes.md#pure) theme.

### emulator

I use iTerm2 and my [profile.json](settings/iTerm2/profile.json) is loaded as a [dynamic profile](https://www.iterm2.com/documentation-dynamic-profiles.html). This profile uses my [fonts](#fonts).

I change the display margin as well.

```diff
# Preferences > Advanced > General

- Width of left and right margins in terminal panes = 5
+ Width of left and right margins in terminal panes = 10
- Height of top and bottom margins in terminal panes = 2
+ Height of top and bottom margins in terminal panes = 10
```

The theme is a port of [base16-cupcake](http://chriskempson.com/projects/base16/).

## fonts

I set my line height to 1.5 and use font size 16.

### ASCII

[Monoid](https://larsenwork.com/monoid/)

* Alternatives: $ 0 1
* LineHeight: M
* Tracking: ½Tight
* Ligatures: On

### non-ASCII

[Roboto Mono for Powerline](https://github.com/powerline/fonts/tree/master/RobotoMono)

## text editor

[Atom](https://atom.io/) using the default One Dark themes with the following plugins:

```shell
~
❯ apm list --installed
Community Packages (11) ~/.atom/packages
├── busy-signal@1.4.3
├── file-icons@2.1.18
├── highlight-selected@0.13.1
├── intentions@1.1.5
├── language-babel@2.84.0
├── language-graphql@0.9.0
├── linter@2.2.0 (disabled)
├── linter-ui-default@1.7.1
├── nuclide@0.275.0
├── pigments@0.40.2
└── prettier-atom@0.53.0
```

I also have a couple extra [keybindings](settings/atom/keymap.cson) to make multi-cursor work a lot easier. I also have a few [custom styles](settings/atom/styles.less) to hide things I do not use from the UI.

## utilities

`can't live without`

[1Password](https://1password.com/) for cross-platform password storage using the (now unavailable) non-cloud version via the dropbox sync utility.

[Spotify](https://www.spotify.com/us/) for music. I also use [Google Play Music](https://play.google.com/music/listen) from time to time.

[Apple Notes](<https://en.wikipedia.org/wiki/Notes_(Apple)>) the only thing that my iCloud account syncs.

### macOS

`can't live without`

[Spectacle](https://www.spectacleapp.com/) for window management in harmony with [Spaces](<https://en.wikipedia.org/wiki/Spaces_(software)>).

[Apple Emoji Picker](https://support.apple.com/kb/PH25337?locale=en_US)

Quicktime Player for screen recordings.

`make life easier`

[Day-O 2](https://shauninman.com/archive/2016/10/20/day_o_2_mac_menu_bar_clock) as a replacement for the native clock to allow me quick access to a calendar like on Windows.

[Boom 3D](https://www.globaldelight.com/boom/index.php) to as a software EQ when listening to music.

[CloudApp](https://www.getcloudapp.com/) for annotating screenshots.
