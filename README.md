# Twitch Pin Favorites
Pin your favorite Twitch channels to the top of the navigation bar so you can easily see when they're live.

![Image of navigation bar](docs/sample.png)

This bypasses the default order sorted by viewcount so your favorite smaller channels can appear near the top.

## Install

[Firefox](https://addons.mozilla.org/en-US/firefox/addon/twitch-pin-favorites/)

## Usage

Go to the add-on's options page and enter in the channel names, then refresh Twitch.

`ctlr-shift-a` -> Twitch Pin Favorites -> Options

## Develop

Go to `about:debugging#/runtime/this-firefox` and load as temporary add-on.

### Libraries

[DOMPurify 2.0.17](https://github.com/cure53/DOMPurify/blob/2.0.17/dist/purify.min.js) to sanitize HTML inputs.

## Todo

- [x] Reduce cpu cycles
- [x] Allow import/export list of channel names
- [ ] Style options page
- [ ] Port to Chrome
