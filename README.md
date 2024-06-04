# Firefox Styling

This is my styling for Firefox. It is designed to work with the [Sidebery extension](https://addons.mozilla.org/en-US/firefox/addon/sidebery/).

## Installation

1. Install the [Sidebery extension](https://addons.mozilla.org/en-US/firefox/addon/sidebery/).
2. In the Sidebery settings, in the 'Styles editor', add the contents of `sidebery.css` to the editor.
3. Go to `about:support` in Firefox.
4. Click on the `Open Folder` button next to `Profile Directory`.
5. Create a folder called `chrome` in the profile directory.
6. Copy the contents of this repository into the `chrome` folder.
7. Go to `about:config` in Firefox.
8. Search for `toolkit.legacyUserProfileCustomizations.stylesheets` and set it to `true`.
9. Restart Firefox.

## Changes

- Remove the tab/title bar - Tabs are now displayed in the sidebar.
- Sidebery sidebar now minimizes to a smaller size, and expands again on hover. (Based on https://github.com/Redundakitties/colorful-minimalist)
