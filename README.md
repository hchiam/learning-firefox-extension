# Learning Firefox extensions (Firefox add-ons)

Just one of the things I'm learning. <https://github.com/hchiam/learning>

Tutorial: <https://developer.mozilla.org/en-US/docs/Mozilla/Add-ons/WebExtensions/Your_first_WebExtension>

An example forked from MDN repo: <https://github.com/hchiam/webextensions-examples/tree/master/borderify>

Some steps:

1. Open <about:debugging> in Firefox.
2. Click "This Firefox" if that option exists.
3. "Temporary Extensions": "Load Temporary Add-on..."
4. Select the `.json` file.
5. (If you're running Firefox in incognito, go to <about:addons> -> "Manage" -> "Run in Private Windows": "Allow")

Example Firefox add-on repo: <https://github.com/hchiam/urlvoid-firefox-extension>

## Note:

This template is old – consider using something like https://github.com/GoogleChrome/chrome-extensions-samples/tree/main/functional-samples/tutorial.hello-world or https://github.com/GoogleChrome/chrome-extensions-samples/tree/main/functional-samples

## Useful links:

- <about:debugging#/runtime/this-firefox>

- <about:addons>

- To submit an add-on, you'll need to login to your submissions: <https://addons.mozilla.org/developers/addons>

- Example of sending messages between popup script and content script: <https://github.com/hchiam/urlvoid-firefox-extension/commit/b05c5befabf32ac8438cd555082bb42218a72e96>

## Mobile debugging before deployment:

<https://extensionworkshop.com/documentation/develop/getting-started-with-web-ext/>

and

<https://extensionworkshop.com/documentation/develop/developing-extensions-for-firefox-for-android/>

```bash
# connect Android mobile device via USB
adb devices
web-ext run --target=firefox-android
web-ext run --target=firefox-android --android-device=...
# a new firefox tab should automatically open
```

You can now inspect in Firefox with the URL `about:debugging` on your laptop (e.g. the two I personally found helpful are "Temporary Extensions > Inspect" and "Main Process > Inspect").

## Want to create your own Chrome extension?

Used this template repo as a starting point: <https://github.com/hchiam/chrome-extension-template>
