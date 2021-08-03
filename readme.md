# Marketbuddy

Plugin for XivLauncher/Dalamud to help with your day-to-day market operations.

## How to get

1. Dalamud settings -> Experimental
2. Add `https://raw.githubusercontent.com/Chalkos/Marketbuddy/main/repo.json` and enable it
3. Install from the plugin list

## Commands

* `/mbuddy` does nothing useful (yet)
* `/mbuddyconf` plugin config gui

## Features

Simplifies updating one price:
* Click adjust price as per usual
  * The window to change price, the list of current items on the market and history of sales for that item open at once
  * Click one of the current items on the market
  * You price will be set 1 gil below and you'll be back at your items list
  * (the set price will be copied to clipboard)

Simplifies updating more items with the same price:
* Click adjust price, while holding CTRL
  * The value from the clipboard will be used for that item

Each feature can be configured in the plugin config.

Holding SHIFT prevents some automation, but you're better off just disabling whatever you don't want in the config.