# Learning Firefox extension

Just one of the things I'm learning. <https://github.com/hchiam/learning>

Tutorial: <https://developer.mozilla.org/en-US/docs/Mozilla/Add-ons/WebExtensions/Your_first_WebExtension>

An example forked from MDN repo: <https://github.com/hchiam/webextensions-examples/tree/master/borderify>

Some steps:

1. Open <about:debugging> in Firefox.
1. Click "This Firefox" if that option exists.
1. "Temporary Extensions": "Load Temporary Add-on..."
1. Select the `.json` file.
1. (If you're running Firefox in incognito, go to <about:addons> -> "Manage" -> "Run in Private Windows": "Allow")

Example Firefox add-on repo: <https://github.com/hchiam/urlvoid-firefox-extension>

## Extra notes:

- Example of sending messages between popup script and content script: <https://github.com/hchiam/urlvoid-firefox-extension/commit/b05c5befabf32ac8438cd555082bb42218a72e96>

- To submit an extension, you'll first need to login at <https://addons.mozilla.org/firefox> and then go to your submissions at <https://addons.mozilla.org/developers/addons>
