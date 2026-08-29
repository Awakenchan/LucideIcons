# LucideIcons

PNG copies of the [Lucide](https://lucide.dev) icon set, at 420x420, laid out for direct
fetching by URL.

    icons/lucide/<icon-name>.png

`icons/lucide/_index.json` maps every icon name to the Roblox asset id it came from.

## Why these exist

Roblox scripts that want Lucide icons normally reference them by asset id. That works until
the executor refuses to show an asset it has no local copy of, and fetching one over HTTP
needs a logged-in Roblox session that a script does not have. Serving the pictures from here
sidesteps both: a plain URL, no session, nothing to resolve first.

## Use

    https://raw.githubusercontent.com/Awakenchan/LucideIcons/main/icons/lucide/house.png

## Credit

Icons are from Lucide, under the ISC licence, which is a community fork of Feather Icons.
The renders were produced from the Roblox asset ids published by
[Footagesus/Icons](https://github.com/Footagesus/Icons).
