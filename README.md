# Car Finance 247 redesigns

One page that links to the redesign prototypes and A/B test designs, each with a live, scaled-down preview window. Four cards per row on a laptop screen, with tabs for Prototypes and A/B tests (`#abtests`), a count on each tab, and a search box that filters both lists.

Live at https://louis-b-work.github.io/redesigns/

## Adding or changing a design

Edit the `DESIGNS` list (prototypes) or the `AB_TESTS` list near the bottom of `index.html`. Each entry has a `title`, a one-line `description`, the page `url`,
an `added` date and time (for example `"2026-11-17T15:30"`) and a `size` (`[width, height]`) that the page is laid out at before it is scaled into its window. The page sorts by `added`, newest first, so a new entry can go anywhere in the list.

## How the previews work

Each card embeds the real page in an `iframe` and scales it down with a CSS transform. The previews are not clickable; the
whole card is the link. The prototypes open a welcome dialog on load, which is hidden inside the previews with an injected
style (nothing is clicked). This works because all the prototypes are on the same origin, `louis-b-work.github.io`.
