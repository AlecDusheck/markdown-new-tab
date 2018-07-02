# Markdown New Tab

[![Build Status](https://img.shields.io/travis/plibither8/markdown-new-tab/master.svg?style=flat-square)](https://travis-ci.org/plibither8/markdown-new-tab)
[![Chrome Webstore Users](https://img.shields.io/chrome-web-store/v/demppioeofcekpjcnlkmdjbabifjnokj.svg)](https://chrome.google.com/webstore/detail/markdown-new-tab/demppioeofcekpjcnlkmdjbabifjnokj)
[![Chrome Webstore Users](https://img.shields.io/chrome-web-store/users/demppioeofcekpjcnlkmdjbabifjnokj.svg)](https://chrome.google.com/webstore/detail/markdown-new-tab/demppioeofcekpjcnlkmdjbabifjnokj)
[![Licence](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)

[![Made_with_love_in India](https://img.shields.io/badge/Made_with_love_in-India-DC3545.svg)](https://madewithlove.org.in/)

> Take down notes 🗒️, save reminders ⏰, paste links 🔗, create checklists ☑️ or tables, all using markdown... directly in your 'New Tab' page! Markdown New Tab is a replacement for the default 'New Tab' page on Google Chrome 🆕 🎉.

<a href='https://chrome.google.com/webstore/detail/shufflepaper/demppioeofcekpjcnlkmdjbabifjnokj?utm_campaign=PartBadge'><img alt='Get it on the Chrome Webstore' src='https://developer.chrome.com/webstore/images/ChromeWebStore_BadgeWBorder_v2_206x58.png' height="58px"/></a>

![Demo GIF](/assets/demo.gif)

## About

Markdown New Tab allows you to take down important notes, thoughts or anything else you need to jot down or paste quickly, directly into your New Tab page... via the markdown syntax.

Markdown will allow you to easily create headings, subheadings, links, styled texts, checkboxes, tables, lists, images and much more... just by a simple syntax. To get the hang of it, check this [brilliant cheat sheat](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet)

Markdown New Tab is complete with the ability to store revisions of the markdown content you made, so if you ever need to look back at previous versions of your content, check the revision history!  

## Development

1. Clone this repo:

```sh
$ git clone https://github.com/plibither8/markdown-new-tab
```
2. Open Chrome and go to `chrome://extensions`
3. Enable 'Developer Mode' by checking the tickbox (on the top of the page).
4. Click the 'Load Unpacked Extension' button and select the `dist/` folder of the cloned repository.
5. The extension should be loaded now and the 'New Tab' page should be Markdown New Tab. 🎉

## Usage

You can edit and save the texts either by pressing the buttons on the top right, or by using the shortcuts <kbd>Ctrl</kbd> + <kbd>X</kbd> to edit the text and <kbd>Ctrl</kbd> + <kbd>S</kbd> to save the text.

The code makes use of `localStorage()` to save the raw text and the time and date of when the edit has been made.

## To do

* Enable user to change colors/add themes
* Implement user-defined markdown rendering
* Other gimmicks to make it less minimalistic (?)


## License

Copyright (c) Mihir Chaturvedi. All rights reserved.

Licensed under the [MIT](LICENSE) License.