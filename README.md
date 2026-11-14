# roll-20-images

Public image assets for the rpg-vaults Roll20 games. Roll20 fetches these by raw URL from chat and tokens.

## vfv/reels

The three spinning-reel GIFs the V for Victory Orb Drop Generator (a Roll20 Mod) embeds in its chat cards: `colour.gif`, `domain.gif`, `move.gif`. Rendered from the VT323 font by `tools/make-reels.py` in the `dungeon-heart-roll20` repository; regenerate there and copy here. Served as

    https://raw.githubusercontent.com/rpg-vaults/roll-20-images/main/vfv/reels/<name>.gif

## wicked

The Infernal Contract character sheet's art: `seal.png` (the Dominion's wax seal with its cords, shown at 100px wide) and `border-seamless.gif` (the "Animated Fiery Ornate Border", 9 frames at 110 ms, transparent middle, with its side strip mirrored once to 437x538 so it tiles down a page without a seam; the sheet lays it over itself as a `border-image` at its own size). The untouched 437x399 original `border.gif` is hosted too, unused. Hosted but no longer used by the sheet: the fire frame cut from the sheet's mockup (`frame-top-left.png`, `frame-top-right.png`, `frame-bottom.png`) and the two flame flourishes `flame-left.png` / `flame-right.png` from the "Wax Seal and Fiery Flourishes Set". Sources in `wicked/sheet/design/art/` in the `dungeon-heart-roll20` repository; copy here. Served as

    https://raw.githubusercontent.com/rpg-vaults/roll-20-images/main/wicked/<name>
