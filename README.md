# TDX kickstart

This project template should provide a kickstart for building brochure websites.

## Usage

Change `WEBSITE` with your projects name

1. Run `git clone git@github.com:AGILEDROP/tdx-kickstart.git WEBSITE` to download source files.
1. Run `cd WEBSITE` to got into your new project folder.
1. Run `fin init` to setup local Docksal envirement. This will:
    1. Remove .git folder
    1. Remove previous setting.local.php file
    1. Copy Docksal specifig settings to setting.local.php
    1. Remove any previous Docksal containers **be careful if running init script after you already worked on your project**
    1. Start Docksal local envirement
    1. Run composer install with no interactions
    1. Install Drupal from configuration
1. Visit `http://WEBSITE.docksal/user` and loging with admin:admin and start building.
