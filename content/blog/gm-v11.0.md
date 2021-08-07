+++
title = 'GooseMod v11.0'
date = "2021-08-07"
description = 'GooseMod v11.0 is now out: internal rewrite, error fail-safing, plus a whole bunch of other improvements and tweaks.'
disableComments = true
+++

## **GooseMod v11.0** is now out! Features internal rewrite, error fail-safing, plus a whole bunch of other improvements and tweaks.

### Internal Rewrite
- **GooseMod is now almost half the size as it was before.** Smaller size should help load times and reduces impact of new additions in the future!
- **Better for GooseMod's future.** GooseMod now uses Rollup; this helps developing GooseMod for the future: improving efficiency and speed of development.

### Error Fail-safing
- **GooseMod is now resistant to crashes.** You should experience less crashes! GooseMod now hardens most things plugins patch into to resist crashes and just error out instead.

### Better Debugging
- **GooseMod now is easier and better to debug.** Both plugins and GooseMod itself is now easier to debug. Should let issues be easier to fix in future.

### Patcher API
- **Adding to context menu for messages now also adds to expanded MiniPopover.** Should help web users who don't have right click menus.
- **GooseMod commands autocomplete section no longer adds multiple times when in DMs.**
- **Rewrote ID generation.** Should be a bit faster and more random now.

### Tweaks and Fixes
- **Fixed showing no PGP verification warning when adding repo even if repo did have valid PGP.**
- **Home expanded icon is now stored.**