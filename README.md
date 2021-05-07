# chief-chrome-extension-sites

## Usage
In `sites.json`, add the reference, name, and image name of the link that you want to add. The items listed in `sites.json` are ordered the same way as in the chrome extension. Ensure that any new items are in correct JSON format. 

Next, add the image reference to `./assets/`. The ideal image size is 30 pixels by 30 pixels.

### After updating, it may take a while for the extension to update due to client side and server side caching
To serve the most recent content, the chrome extension uses the GitHub raw content link, which is updated when `sites.json` is. It has a five minute cache.

## About
This serves as a list of sites for the Chief Chrome Extension (private repo).

**Confused? Check out the !(chrome extension repository)[https://github.com/Chief-Ent/chief-chrome-extension].**
