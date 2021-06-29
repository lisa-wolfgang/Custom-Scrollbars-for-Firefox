# Custom Scrollbars for Firefox
Custom Scrollbars for Firefox is an extension for the Firefox browser that allows websites to use their own scrollbar settings (as they appear in Safari and Chrome) instead of Firefox's default appearance. For example, Discord uses the custom scrollbar capability of Safari and Chrome to make nice-looking rounded scrollbars; however, since Firefox doesn't support this level of scrollbar customization, the scrollbars are still mostly Firefox's default appearance. With this extension installed, the scrollbars look the same in Firefox as they do in Safari and Chrome, which is the way it should be.

### To install from Firefox Add-ons
Release versions will become available on the Firefox Add-ons store soon after a full version is released.

### To install from source
First, you should know a few things about the repository's branch structure:
- Branches labeled with future version numbers are development branches with new features or fixes not publicly released yet. For example, if the current version is x.4, the `x.5` branch is a development branch. Note that while you might get useful features early, these branches may have bugs not present in release versions, so install with caution.
- The `master` branch is used to create releases for the Firefox Add-ons store. It's great for browsing the source of the latest version, but relatively pointless to install from.
- Previous versions are available on their respective branches. For example, version 1.0 is available on the `1.0` branch. These branches don't change once the next version has been released, so if there are old bugs in those versions, they'll still be present.

Once you know which branch you want to install from, follow these steps:
1. Click on the `master` branch button, which is on the left side of the toolbar with the green button. Use the menu that appears to find your branch and select it.
2. Click on the green `Code` button with the download icon. In the menu that pops up, click `Download ZIP`.
3. Save the ZIP file somewhere you'll remember, then extract it using the Extract feature of your file explorer.
4. In Firefox, go to `about:debugging#/runtime/this-firefox`. (Copy the link and paste it into your address bar.)
5. Click on the `Load Temporary Add-on...` button and navigate to the folder that you extracted earlier. Inside the folder, select the `manifest.json` file and open it.

If you have the Firefox Add-ons store version installed, you should disable it while you're using the source version to avoid double scrollbars and other problems.
