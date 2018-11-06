# Monterail Blue
_Monterail Blue, a Thunderbird theme inspired by the mockup of Monterail_

## Oother Monterail inspired themes: 
- [Monterail Dark](https://github.com/conema/monterail-dark)
- [Monterail Full Dark](https://github.com/conema/monterail-fulldark)
- [Monterail by Paenglab](https://addons.thunderbird.net/en-US/thunderbird/addon/monterail/)

## What is this?
This is a full theme for the Thunderbird e-mail client, inspired by [Monterail](https://monterail.com/blog/2016/the-power-of-email-clients-why-did-we-redesign-thunderbird) mockup and by [spymastermatt](https://github.com/spymastermatt/thunderbird-monterail)'s dark theme. As opposed to the spymastermatt's version, this theme can be **installed easily and quickly with an addon** and it's **fully compatible with Thunderbird 60.x**.

## Installation
### Manual (from source)
The first step is to [download](https://github.com/toolstack/monterail-blue/archive/master.zip) the theme, unzip the contents and re-create a zip only with the content of "monterail-blue" folder. Change the extension of the archive to ".xpi". An extensive guide for install the xpi file can be found [here](https://support.mozilla.org/en-US/kb/installing-addon-thunderbird) on the Mozilla support site, starting from "A slightly less ideal case". The Addon Manager can be found by clicking the menu icon ![menu](https://prod-cdn.sumo.mozilla.net/uploads/gallery/images/2017-10-22-15-37-15-18c775.png) (on the right, next to the search bar) followed by Add-ons and click on the Themes panel on the left.

### Theme market (**not yet released to the market**)
The theme can be directly downloaded from the Thunderbird Add-on market, it can be found by searching "Monterail Dark" directly in the add-on page of thunderbird or [there](https://addons.thunderbird.net/en-US/thunderbird/addon/monterail-dark/).

## Screenshots


## FAQ
* Installation fail/Theme didn't change in Thunderbird 60<br>
This seems a know issue of Thunderbird 60 [[1]](https://bugzilla.mozilla.org/show_bug.cgi?id=1484393) [[2]](http://forums.mozillazine.org/viewtopic.php?f=39&t=3041219). With this workaround it'll work:
  1. Go where your application data are stored, they usually can be found in:
    - Windows: `C:\Users\[your windows user]\AppData\Roaming\Thunderbird\Profiles\[(literally) random letters and numbers].default/`
    - Linux: `/home/[your linux user]/.thunderbird/[(literally) random letters and numbers].default/`
    - MacOS: `/home/[your macos user]/Library/Thunderbird/Profiles/[(literally) random letters and numbers].default/`
  2. Go to the "extensions" folder, here there should be a file named "MonterailDark@conema.me.xpi"
  3. While Thunderbird is opened in background, delete the "MonterailDark@conema.me.xpi" file.
  4. Restart Thunderbird and reinstall the theme
  5. Restart Thunderbird again, the theme now should work


* With which versions of Thunderbird can I use this theme?

For now only **60.x** has been tested.

## Credits
This addon is based on [Monterail by Paenglab](https://addons.thunderbird.net/en-US/thunderbird/addon/monterail/), source code is included.

Also based on [Monterail Dark](https://github.com/conema/monterail-dark).
