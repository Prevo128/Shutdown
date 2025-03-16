# Shutdown
This macOS app lets you promplty shutdown your mac.
# Prerequisites
Xcode Command Line Tools have to be installed.
You can install them using:
```bash
xcode-select --install
```
Move the app to ```/Applications``` and sign Shutdown using:
```bash
xattr -cr /Applications/Shutdown.app && codesign --force --deep --sign - /Applications/Shutdown.app
```
# Usage
Simply click on Shutdown, wether it is on your dock or in the ```/Applications``` folder. Shutdown promptly shuts down your mac.
# Contributors
[@Prevo128](https://github.com/Prevo128): Lead Developper;
# Donate
Shutdown is a free app! Support its development with a [donation](https://www.paypal.com/donate/?hosted_button_id=TYNCAD4LZJYBL). Your contribution helps me enhance and maintain the app. Thank you for your support!
