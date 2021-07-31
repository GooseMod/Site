+++
title = 'GooseMod v10.1'
date = "2021-07-26"
description = 'GooseMod v10.1 has been released, featuring internal rewrites, new profile store, and lots of tweaks and fixes.'
disableComments = true
+++

## **GooseMod v10.1** has been released! Features internal rewrites, new profile store, and lots of tweaks and fixes.

### Internal Rewrites
- **Rewrote logger output to use text and nicer colors.** Now easier to look at and filter.
- **Rewrote React utils library.** Now supports new React used in Discord Canary and now a bit more efficient.
- **Rewrote Webpack library.** Additionally also now a bit more efficient and generally better.

### Profile Store
- **Developer's GooseMod modules are now listed under a category in their user profile.** Added as a new neat way of discovering modules and developers.

### Main Settings
- **Separated experimental settings into their own category.** Now your settings is even tidier.

### Home
- **GooseMod home category now stays collapsed after a refresh if it was collapsed previously.**
  
### Tweaks and Fixes
- **Fixed custom color picker in settings not appearing.**
- **Removed excess old debug logging.** Clearing up your console since 2021.
- **Fixed custom name and footer for GooseMod changelog.**
- **Fixed repeated class name in home injection container.** No one would have noticed but we fixed it anyway:tm:.
- **Fixed commands (Canary-only).** Now using built-in instead of a GooseMod category due to internal update changing a lot of things.