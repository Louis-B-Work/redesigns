# Car Finance 247 redesigns

One page that links to the redesign prototypes, each with a live, scaled-down preview window.

Live at https://louis-b-work.github.io/redesigns/

## Adding or changing a prototype

Edit the `DESIGNS` list near the bottom of `index.html`. Each entry has a `title`, a one-line `description`, the page `url`
and a `size` (`[width, height]`) that the page is laid out at before it is scaled into its window.

## How the previews work

Each card embeds the real page in an `iframe` and scales it down with a CSS transform. The previews are not clickable; the
whole card is the link. The prototypes open a welcome dialog on load, which is hidden inside the previews with an injected
style (nothing is clicked). This works because all the prototypes are on the same origin, `louis-b-work.github.io`.
