# Progressive Web App (PWA)

By adding the `manifest.json` file to your project, you can enable PWA features such as: 
 * Mobile and functional enhancements - Install app / Add to homescreen
	* Proper app icons
	* Splash Screen
	* Fullscreen
	* App Shortcuts
	* Protocol Handlers (ie "Open file in Streamstats")
 * Offline support


## Setup

 * Copy the `manifest.json` temlate file to your project.
 * Add it to your project `<head>` with the line `<link href="/manifest.json" rel="manifest">`


 ## Properties

 Read the [Web App Manifest Documentation on MDN](https://developer.mozilla.org/en-US/docs/Web/Manifest) for information on the fields.

## Images

Please modify the example images and icons to differentiate them for your application to avoid users having multiple applications with the same icon on their phone.

## Debugging PWAs

Read this [Chrome Developers Page](https://developer.chrome.com/docs/devtools/progressive-web-apps/) for information on debugging PWA features.

# Service Workers

If your application needs to work offline or send push notifications, read about [Service Workers](https://web.dev/learn/pwa/service-workers/).