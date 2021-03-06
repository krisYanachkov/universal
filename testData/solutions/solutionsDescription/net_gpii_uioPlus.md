# UIO Plus

## Details

* __Name__: UIO+
* __Id__: net.gpii.uioPlus
* __Platform__: Tested on MS Windows and GNU/Linux (it should also work on Mac OSX)
* __Contact__: Justin Obara <obara.justin@gmail.com>

## Description

UIO+ is a browser extension; currently only supported in Chrome. This extension establishes a connection with GPII to get the active preferences. These preferences are used, by the extension, to adapt the web content within the browser.

Useful links:

  * [Chrome extensions developer documentation](https://developer.chrome.com/extensions)
  * [Source code at github.com](https://github.com/GPII/gpii-chrome-extension)

## Installation

Install the latest version from the [Google Chrome Web Store](https://chrome.google.com/webstore/detail/ui-options-plus-uio%20/okenndailhmikjjfcnmolpaefecbpaek).


## Testing

For manual testing, please follow the "Installation" steps above. After the browser extension is installed, you can click the blue gear extension icon in the browser's chrome to open the UIO+ panel. Changing the settings here should affect the content of the page. Any pages that are opened before the extension is loaded/installed will need to be reloaded before changes will properly apply.

Another option for manual testing is to login to the GPII with a preference set containing preferences supported by the extension. A profile with a set of Needs & Preferences has been provided in order to properly perform the tests.

### uioPlusCommon

preference set located at universal's testData/preferences/uioPlusCommon.json
