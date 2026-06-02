# Disable Rounded Corners

A comprehensive Zen Browser mod that removes rounded corners from the entire browser UI.

## What it disables

- **Web view** - content area corners
- **Tabs** - tab backgrounds, stacks, pinned tabs, essentials
- **Navbar** - URL bar, search bar, toolbars
- **Sidebar** - sidebar box, panels, icons wrapper
- **Popups & Panels** - context menus, notification popups, panel UI
- **Buttons** - all toolbar buttons, download button, badge stacks
- **Workspaces** - workspace buttons, indicators
- **Compact mode** - title bar and nav bar in compact mode
- **Find bar & Status bar** - bottom bars
- **Scrollbars** - scrollbar elements
- **Notifications** - notification boxes

## Installation

1. Open Zen Browser
2. Go to `about:config` and ensure `toolkit.legacyUserProfileCustomizations.stylesheets` is set to `true`
3. Go to `about:support` and click **Open Profile Folder**
4. Create a `chrome` folder inside if it doesn't exist
5. Copy `chrome.css` into the `chrome` folder
6. Restart Zen Browser

To enable the mod, go to `about:config` and create a boolean pref named `zen.corners.disable` and set it to `true`.

### Individual toggles

You can also selectively disable corners for specific areas by creating boolean prefs:

- `zen.corners.disable-webview` - Web content area
- `zen.corners.disable-tabs` - Tabs
- `zen.corners.disable-nav` - Navbar & URL bar
- `zen.corners.disable-sidebar` - Sidebar
- `zen.corners.disable-popups` - Menus & popups
- `zen.corners.disable-buttons` - Toolbar buttons
- `zen.corners.disable-workspaces` - Workspace buttons
- `zen.corners.disable-compact` - Compact mode

Set any of these to `true` in `about:config` to disable corners for that specific area.
