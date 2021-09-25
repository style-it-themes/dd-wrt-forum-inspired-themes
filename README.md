<p align="center">
  <img alt="style-it-themes-logo" src="https://raw.githack.com/style-it-themes/style-it-themes-logos/master/style-it-themes-logo-full.svg" width="580">
</p>
<br>
<h1 align="center"><strong>DD-WRT Forum Inspired Themes</strong></h1>
<p align="center">
  <a href="./LICENSE">
    <img src="https://img.shields.io/badge/License-MIT-blue.svg?longCache=true&style=for-the-badge" alt="LICENCE">
  </a>
</p>
<p align="center">
  <a href="https://discord.gg/EpdGSfH">
    <img src="https://img.shields.io/badge/style--it--themes-discord%20channel-blue.svg?style=for-the-badge" alt="Style-It Themes (sit) Discord Channel">
  </a>
  <a href="https://github.com/style-it-themes/dd-wrt-forum-inspired-themes/releases">
    <img src="https://img.shields.io/github/tag/style-it-themes/dd-wrt-forum-inspired-themes.svg?label=Current%20Version&style=for-the-badge" alt="Current version">
  </a>
  <a href="https://david-dm.org/Style-it-Themes/dd-wrt-forum-inspired-themes?type=dev">
    <img src="https://img.shields.io/david/dev/style-it-themes/dd-wrt-forum-inspired-themes.svg?label=devDependencies&style=for-the-badge" alt="devDependencies">
  </a>
</p>

# TOC
  * [About](#about)
  * [Features](#features)
  * [Installing](#installing)
    * [Requirements](#requirements)
    * [Install This Style](#install-this-style)
    * [Additional Userstyles](#additional-userstyles)
  * [I Found a Bug](#i-found-a-bug)
  * [Engaging with the Project](#engaging-with-the-project)
    * [Contribution Guidelines](#contribution-guidelines)
    * [Development Scripts](#development-scripts)
  * [Screens](#screens)
  * [Thanks](#thanks)

## About

The *DD-WRT Forum Inspired Themes* style is designed the ancient DD-WRT phpBB Forum.

The default boards are old, look old, feel old, so here are a couple of coats of paint.

It's made for my personal use only, and shared because... Why not.

This style leverages the _awesome_ v2 [stylus lang color generator](https://github.com/vednoc/stylus-color-generator) by @vednoc

## Features

The *DD-WRT Forum Inspired Themes* style has optional and built in redesigns that fix,
modernize or allow consistence styling through all accessible areas.
if you wish to view complete list click below.

<details>
  <summary>Click to Expand</summary>
 
 ### Preset styles

 * Custom colors (within reason and sane choices users can make up own color schemes)
 * Dracula
 * Duo Cocoa
 * Material
 * Material Darker
 * Solarized Dark
 * Twilight
 * The Matrix
 * Ubuntu

 ### Color Adjustments

 * Optionally darken/lighten to some extent the background, foreground and accent colors. 

 ### Redesigned Inputs

 * Redesigned input styling for checkboxes, radio, dropdown and other interactable elements.
 
 You can optionally choose the checkbox size, however not all sizes will look or align well.

 ### Inverted gif buttons
  
  The post/reply and such buttons had to be inverted so the poor quality of the gifs edges dont assault my retinas.
  There is no simple way to replace the bad quality buttons with better quality, phpbb at least this old version looks like spaghetti.
  This job would best be done directly into the source code.
 
</details> 

## Installing

### Requirements

* Stylus - install the addon for [Firefox](https://addons.mozilla.org/en-US/firefox/addon/styl-us/), [Chrome](https://chrome.google.com/webstore/detail/stylus/clngdbkpkpeebahjckkjfobafhncgmne) or [Opera](https://addons.opera.com/en-gb/extensions/details/stylus/).

### Install This Style

[![CLICK TO INSTALL WITH - STYLUS](https://img.shields.io/badge/Install_directly_with-Stylus-21d1d0.svg?longCache=true&style=for-the-badge)](https://github.com/style-it-themes/dd-wrt-inspired-themes/raw/main/dd-wrt-inspired-themes.user.styl)  
*Click to install directly from this repository*.

### Limitations of this Project

 Some areas like moderator areas and admin areas are likely showing old styles and broken,
 if you want these fixed, there are two options:
 
 1) Report bugs on via GitHub issues with inpected stylesheets and show me what they are.
    Read below [I Found a Bug](#i-found-a-bug).
 
 2) Give me moderator/higher access so I can do this work myself. This wont happen (I dont really want it) anyway so GOTO 1) 

 *Regarding text colors:*
 phpBB uses many colors users/mods/admins can select from drop down menu when making posts,
 these ARE NOT dark style friendly so they are essentially overriden in style for something that has better contrast, however given anyone can add whatever colors they want, Im not going to hunt them down in 2 trillion posts.
 
 I have overriden the obvious colors found on most help text signatures by community helpers.<br>
 If you find something you cant read; read below [I Found a Bug](#i-found-a-bug).

### Additional Userstyles

  Style-It Themes (and I) recommends *Stylus Wardrobe* and the *Global Overlay Scrollbars* can be used all together without issues.
  These add unapparelled consistent experience and extend customizations options for other areas of your browsing live.
  
  Save your retinas from the burn!

* [Overlay Scrollbars](https://github.com/StylishThemes/Overlay-Scrollbars)
* [Stylus Wardrobe](https://github.com/style-it-themes/stylus-wardrobe)

## I Found a Bug

At the first instance of finding a bug, have a look if there is already an open issue, if so add the required information as described in the [issue template](.github/ISSUE_TEMPLATE.md).

If your issue is new, please [open an issue](https://github.com/style-it-themes/dd-wrt-forum-inspired-themes/issues/new/choose) and report your problem.

You will need to be familiar with browser development tools.

[Firefox development tools](https://developer.mozilla.org/en-US/docs/Tools)
[Chrome development tools](https://developers.google.com/web/tools/chrome-devtools)

## Engaging with the Project

There are many ways to engage with the project, all contributions types are most welcome and encouraged, e.g. ask for your fav color schemes, fix some typo(s), add documentation, prettify any included portions, provide feedback or ask a question, even help out with support/questions from other users, to name just a few ways you can engage with this project.

Open a pull request or [ticket](https://github.com/style-it-themes/dd-wrt-forum-inspired-themes/issues/new/choose) to start the ball rolling.

For Git related contributions you will need:

1. [Fork](https://github.com/style-it-themes/dd-wrt-forum-inspired-themes/fork) the project.
2. Install dev-dependencies `npm i --only-dev`
3. Edit the desired files according to current requirement below, commit changes, run fix script `npm run fix` and push changes.
4. Open a pull request

## Contribution Guidelines

After any changes and before opening a PR please run both development scripts below.
Then push your changes and open a PR.

If your contribution includes dependencies updates, ensure this is done as a separate commit.

Thank you in advance for any contributions.

### Development Scripts

* `npm run authors`: Regenerate the AUTHORS file based on Git history
* `npm run fix`: Runs editorconfig via ECLint with `--fix` on the styl file.

For dependencies updates;

* `npm run update`: Update development dependencies.

### For internal use Only

Releases are for internal use only, so remember to not include version bumps with your contributions 

* `npm run major`: Creates a semantic major release.
* `npm run minor`: Creates a semantic minor release.
* `npm run patch`: Creates a semantic patch release.

> Note: Dependencies updates can be submitted as part of any contribution that is a separate commit
>       from main contribution, or as a standalone contribution.

## Screens

# COMING SOON

More screenshots available in [screens directory](/screens) for your perusal.

## Thanks

@vednoc kudos and thanks, for showing me another way to save retinas from the burn.

[Openstyles](https://github.com/openstyles/stylus) for developing Stylus. The best userstyle extension on all the web.

[:arrow_up: UP :arrow_up:](#readme)
