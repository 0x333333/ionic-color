Before start ionic-color, run this:

```bash
make mobile
```

To run stoic.ionic in emulator, some plugins need to install:

```bash
# Add iOS platform
cordova platform add ios

# Add android platform
cordova platform add android

# Add device plugin
cordova plugin add org.apache.cordova.device

# Add camera support
cordova plugin add org.apache.cordova.camera

# Add contacts support
cordova plugin add org.apache.cordova.contacts

# Add statusbar plugin
cordova plugin add org.apache.cordova.statusbar

# Add inAppBrowser plugin
cordova plugin add https://git-wip-us.apache.org/repos/asf/cordova-plugin-inappbrowser.git

# Build project and run in emulator
cordova build ios
cordova emulate ios
```

It's crucial the plugins are installed properly or the effect won't work.