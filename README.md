# backpack.tf Bot Utilities

This user script provides various TF2Autobot (and TF2-Automatic) utilities on [backpack.tf](https://backpack.tf/).

If you have any suggestions or bug reports, please create an [Issue](https://github.com/Bonfire/bptf-bot-utilities/issues).

If this script helped you out, please feel free to support me by doing the any of the following:

- Become a [⭐Stargazer⭐](https://github.com/Bonfire/bptf-bot-utilities/stargazers)
- Become a [❤️Sponsor❤️](https://github.com/sponsors/Bonfire)

## Features

**All of the below buttons copy their respective commands to your clipboard**

- "Item SKU" button on item hover
- "Add to pricelist" button on item hover
- "Update pricelist" button on item hover
- "Remove from pricelist" button on item hover
- "Pricecheck item" button on item hover
- "Match listing" button on item hover
  - **Note: Current key prices are fetched automatically. Please be sure to double-check item prices before sending the command to your bot! I will not be held responsible for incorrect item prices as a result of this command!**

## Installation

To use user scripts you need to first install a user script manager. Here are managers for various browsers:

- [Greasemonkey](http://www.greasespot.net/) - Firefox
- [Tampermonkey](https://tampermonkey.net/) - Chrome, Microsoft Edge, Safari, Opera, Firefox (also with support for mobile Dolphin Browser and UC Browser)
- [Violentmonkey](https://violentmonkey.github.io/) - Chrome, Firefox, Maxthon, Opera

To install this user script, simply navigate to [this link](https://github.com/Starbucksbot/bptf-bot-utilities/raw/master/bptf-bot-utilities.user.js) and click "Install".

You can also install this script by manually pasting the code found in the above link into a new user script.

**Note: To receive automatic updates when this script updates, please be sure to enable automatic update checking for this script on your preferred User Script Manager.**

## Example

![Item Hover Buttons](https://i.imgur.com/lhlzfRy.png)

_Newly added buttons for easily copying commands are highlighted above_

## Changelog

**1.0.18**

Fixed:

- Issue with stale KeyData from previous versions

**1.0.17**

Updated:

- Automatic key price fetching to use the autobot.tf API instead of the now-obsolete prices.tf API
- KeyData storage logging

Fixed:

- KeyData storage

**1.0.16**

Fixed:

- Issue where sometimes the copy command buttons would not copy the commands to the clipboard

**1.0.15**

Added:

- Automatic fetching and storage of current key prices for the "Match Listing" command

**1.0.14**

Fixed:

- Refactored event code to be outside element definition code. Should prevent some rare cases where commands would return "undefined"

**1.0.13**

Added:

- Match listing command to match buy/sell order prices

**1.0.12**

Fixed:

- SKU generation for Chemistry Sets - [@Preport](https://github.com/Preport)

**1.0.11**

Fixed:

- SKU generation for Unusualifiers - [@Preport](https://github.com/Preport)

**1.0.10**

Fixed:

- SKU generation for War Paints - [@Preport](https://github.com/Preport)

**1.0.9**

Added:

- Add SKU generation support for Strangifiers - [@Preport](https://github.com/Preport)
- Add SKU generation support for Kit Fabricators - [@Preport](https://github.com/Preport)

**1.0.8**

Fixed:

- Stock item mapping for the "Construction PDA"

**1.0.7**

Fixed:

- Stock item mapping for the "Sapper"

**1.0.6**

Fixed:

- Wrong def index mapping for stock items

**1.0.5**

Improved:

- Add "Target" item attribute to SKU lookup

**1.0.4**

Improved:

- "Pricecheck item" button on item hover (Reverted)
- Removed text from SKU button and condensed text for Pricecheck button
- Add "Australium" item quality to SKU lookup
- Add "Crate Series" item attribute to SKU lookup

**1.0.3**

Added:

- "Item SKU" button on item hover - [@idinium96](https://github.com/idinium96)

Removed:

- "Pricecheck item" button on item hover (due to very niche use cases)

**1.0.2**

Added:

- "Pricecheck item" button on item hover - [@luigia](https://github.com/luigia)

**1.0.1**

Improved:

- Moved pricelist buttons to above the search link buttons

**1.0.0**

Added:

- "Add to pricelist" button on item hover
- "Update pricelist" button on item hover
- "Remove from pricelist" button on item hover

## Credits

- Thank you to [@NetroScript](https://github.com/NetroScript) for their [similar project](https://github.com/NetroScript/backpack.tf-miscellaneous-extensions/) of which I used as a great reference for interacting with the backpack.tf UI.
