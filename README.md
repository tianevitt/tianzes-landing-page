# Tianze's Landing Page
A simple yet flexible landing page for Foundry VTT.

This is a dead-simple mod that provides a landing page designed with flexibility in mind.

## Installation
- Export the two compendiums. One is the landing page scene, and the other is for the journals.

## Compatibility

- It can be used for any game system, but currently has a medieval theme. I am considering creating additional versions for other eras, depending on interest. If you would like to request an additional theme, please open a bug on the github page.
- This particular version supports 4 players. I am planning additional versions for 5 and 6 players. If you would like a version with another number of players, please open a bug on the github page.

## Images
- The foreground and background are both 2000x1500 webps.
- The background currently is currently just a black rectangle, but ideally, you should change it out for a game-specific vignette.
- Crop it to 2000x1500 pixels in order to prevent Foundry from showing a warning every time the scene loads.
- The scene is gridless, which gives me greater design flexibility and makes it easier to precisely place tiles and text.

## PC Actor Tiles
- If you use actors in the Cast of Characters area, you will need to set their elevation to above 20 for them to appear on the overlay.
- Instead, I used tiles that point to the actor token image, as shown in the examples. Otherwise the elevation appears with the actor, and destroys immersion.

## Creature Tokens
- The area for Creatures Defeated does not have an overlay, so you can use regular tokens there. Make sure you are using creatures from your compendium, rather than a module that you may uninstall at some point.
- To keep this module system-agnostic, the sample Creatures are tiles pointing to images that came with Foundry. Just delete them and add your actor tokens.

## Journals
- There is a folder full of example journals, which are included in the scene.
- These folders have the players as owners, so you could actually give these to your players to use.

## Text Drawings
- The example text plus the creature area are drawings that use the "information" drawing role. This way, it is visible on the top layer.

Enjoy!

# Art Credits
- Foreground created with Inkarnate.
- Tiles created with HeroForge and tokenized with Affinity Designer.
