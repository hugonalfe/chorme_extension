# How to create a Chrome extension with Bubble

# Step 1: Download and unzip the files
[extension.zip](https://github.com/hugonalfe/chorme_extension/files/8241336/extension.zip)

# Step 2: Add URL and customize the popup size

Open `popup.js` with any text editor. Replace [https://nalfe.com](https://nalfe.com/) with your app’s URL. (Make sure all iframe is enabled. If you are not sure, go to the bubble editor. Settings > General > Allow to render the app in a frame/iframe (X-Frame-Options). Select “Allow all iframes”.)

You can also edit the `width` and `height` to customize the size of the popup.

# Step 3: Customize extension icon, name, and description

Open the folder `images`. You can place your own icon images here. 

Open `manifest.json` with any text editor. Replace the path of the icons.

You can also edit the `name` and `description`. 

# Done!

![082636](https://user-images.githubusercontent.com/101536870/158095309-43f60922-8771-4b86-8b4d-ed57c01ebce8.png)

Your extension is ready. You can load your unpacked extension to test ([https://developer.chrome.com/docs/extensions/mv3/getstarted/#unpacked](https://developer.chrome.com/docs/extensions/mv3/getstarted/#unpacked)) or upload it to the Chrome Web Store ([https://developer.chrome.com/docs/webstore/publish/](https://developer.chrome.com/docs/webstore/publish/)).

It usually takes 1-2 days for the extension to be approved.
