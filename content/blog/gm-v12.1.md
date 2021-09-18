+++
title = 'GooseMod v12.1'
date = "2021-09-18"
description = 'GooseMod v12.1 is now out: various improvements with Store UI, storage, settings, and more.'
disableComments = true
+++

## **GooseMod v12.1** is now out! Various improvements with Store UI, storage, settings, and more.

### Store
- **Ludicrous speed.** The Store should now be quite faster, especially on low-end hardware.
- **Carousel controls in banner images.** Also made modal opening more obvious via cursor.
- **Search text hints.** Now shows no results text for no results, and hints to go to an other category if there are results in that and not the current category.
- **Improved profile store.** Better and more reliable scrolling down to card and now highlight clears after a short time.

### Parity Storage
- **Heavy reduction in GooseMod wipes / resets.** Sometimes when Discord updates (desktop) GooseMod settings and modules would get cleared due to a Discord client bug. This should now hopefully be eliminated or at least heavily reduced thanks to a new parity storage backup system.

### Tweaks Settings
- **Added tweaks setting section.** Includes new minor changes you can now toggle on or off. New settings (and more will likely be added in future updates):
- **Placeholder Image.** Use a placeholder image in the Store for modules without images.
- **Collapsible Home Category.** Let home category be collapsible via icon.

### Settings
- **Added new setting to give notifications when new modules are added to the Store.**
- **Headers are now not collapsible by default.** Now has to be turned on for individual headers. The experimental section is also now collapsed by default.
- **Rewrote settings context (right click) menu to use ids.** Should no longer open wrong tabs if named the same.

### Themeability
- **Various minor additions to allow for easier theming.** We introduced a variety of small tweaks to help make some of GooseMod easier to theme for theme developers:
- **GooseMod settings sidebar items now have easier ids to grab.** Used to just use label so was reliant on supporting all translations.
- **Added GooseMod class to body so themes know if it's in use.**