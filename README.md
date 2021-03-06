### About

Auto-lock Topics Extension for phpBB 3.2.x

[![Build Status](https://img.shields.io/travis/AlfredoRamos/phpbb-ext-auto-lock-topics.svg?style=flat-square&maxAge=3600)](https://travis-ci.org/AlfredoRamos/phpbb-ext-auto-lock-topics) [![Latest Stable Version](https://img.shields.io/github/tag/AlfredoRamos/phpbb-ext-auto-lock-topics.svg?label=stable&style=flat-square&maxAge=3600)](https://github.com/AlfredoRamos/phpbb-ext-auto-lock-topics/releases) [![License](https://img.shields.io/github/license/AlfredoRamos/phpbb-ext-auto-lock-topics.svg?style=flat-square)](https://raw.githubusercontent.com/AlfredoRamos/phpbb-ext-auto-lock-topics/master/license.txt)

### Dependencies

- PHP 5.6 or greater
- phpBB 3.2 or greater

### Installation

- Download the [latest release](https://github.com/AlfredoRamos/phpbb-ext-auto-lock-topics/releases)
- Decompress the `*.zip` or `*.tar.gz` file
- Copy the files and directories inside `{PHPBB_ROOT}/ext/alfredoramos/autolocktopics/`
- Go to your `Administration Control Panel` > `Customize` > `Manage extensions`
- Click on `Enable` and confirm

### Usage

It will run automatically using phpBB's cron functionality.

### Preview

[![Forums](https://i.imgur.com/aBjwVBpt.png)](https://i.imgur.com/aBjwVBp.png) [![Forum settings](https://i.imgur.com/mBCEbSft.png)](https://i.imgur.com/mBCEbSf.png) [![Topics loked](https://i.imgur.com/uM7dkoGt.png)](https://i.imgur.com/uM7dkoG.png) [![Admin log](https://i.imgur.com/PIOhYf7t.png)](https://i.imgur.com/PIOhYf7.png)

*(Click to view in full size)*

### Configuration

- Go to your `Administration Control Panel` > `Forums` > `Manage Forums`
- Select a category and then a forum
- Click on the `Edit` button (green gear)
- Scroll down to `Auto-lock settings`
- Edit the settings as you like
- Click on `Submit`

### Uninstallation

- Go to your `Administration Control Panel` > `Customize` > `Manage extensions`
- Click on `Disable` and confirm
- Go back to `Manage extensions` > `Auto-lock Topics` > `Delete data` and confirm

### Upgrade

- Uninstall the extension
- Delete all the files inside `{PHPBB_ROOT}/ext/alfredoramos/autolocktopics/`
- Download the new version
- Install the extension
