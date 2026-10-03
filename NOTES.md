# The Old Shelf mock notes

Visible name: **The Old Shelf**. PK picked this name. The domain he named is theoldshelf.com. It is not registered here, and it is not used in any canonical.

## What this is

A browse catalog in the vein of a consumer front door. People look things up by country and linger on pictures. It is not a shop, not a marketplace, and not a community. No prices, cart, or checkout. A “Remember” toggle stays in the browser only.

The point of the page is visits: country shelves, specific objects, click into a detail view.

## UX lock

- Main page is a thumbnail grid, country by country.
- India, Japan, China, and the United States have a “First look” row, then “Also on this shelf.”
- Mexico, Brazil, South Korea, Russia, Turkey, and Nigeria are shorter next-wave rows.
- Click a thumbnail: an in-page detail view with every related still in that set.
- No video. None was collected with a license we would embed, so the detail says stills only and does not fake a player.
- Germany, Indonesia, Philippines, and the UK are not in this mock. Pakistan is not its own shelf.

## Visual system

Paper and cream, faded ink, one label red. Type is Fraunces for titles (a printed-catalog nod) and Source Sans 3 for body, both stored next to the CSS so the file opens offline. Corners are square. Country lines are written as memory (“the gully and the kitchen shelf”), not as a product pitch.

## India

First look, in order: WIMCO and other matchbox labels, a Met silver pichkari, the Radhika cassette inlay (no pencil in the frame), a wooden top that is not labeled Indian, a Rooh Afza bottle, and crown caps.

The tape-ball and brick-wicket slot is empty of its own photo. Caps occupy that grid place and are not captioned as a tape ball.

Also: badminton at Ganesha Ghat (net game), Mangharam enamel sign and a 1947 Parle Gluco ad (old ads, not film posters), Parle-G, a Frooti shop display, a lacquer tiffin that is not Indian steel, a masala dabba, an unlit Virginia sparkler, and a hopscotch photo that does not say India.

Not found cleanly, so omitted rather than faked: Camlin tin, Rasna, a patang with no manjha, kanche as an Indian-labeled marble, lit Diwali, manjha.

## Japan, China, United States

Japan first look: Ramune, kendama, beigoma, illustrated paper menko (not lead), dagashi jars. Also: a tin nagegoma. No Sakuma tin. No Nintendo, Sanrio, Doraemon, or Peko.

China first look: White Rabbit wrapper, a Jianlibao shop display (not a vintage glass bottle), slogan enamel mugs (not floral). Also: Flying Pigeon, Bee & Flower (photographed in Canada), Pechoin. Subor keyboard was dropped because the photograph puts the machine on an anime mousepad. No firecrackers, no comic pages.

United States first look replaces the old NES and VHS row: Abbotts milk bottle, View-Master Model G with no reel, glass marbles (country not stated), wooden yo-yo. Also: painted tin buckets (not a plain pail), Slinky, Wiffle, wax bottles, Polaroid Supercolor 1000, a grey rotary phone. No jacks, no character pogs, no candy cigarettes, no lunchbox art.

## Next wave

Partial on purpose. Each card is a real Commons file. See CREDITS.md for stand-ins.

## Photo rule

One object where we had it. Trademarks stay on the package in the photo and are not redrawn in the interface. No scraped film posters, no game screens, no lit fireworks.

## Open

- Whether The Old Shelf stays the public name once Lena reviews the files.
- Dan’s list will keep growing; empty slots should stay empty until a clean photo exists.
- Whether scenes (badminton, hopscotch, Karagöz shadow) stay beside objects.
- A tape ball, a real lattu, a Sakuma tin, a floral enamel mug, and a plain pail still need photographs we can license.

## URLs and SEO

Static files match the paths. Trailing slash, one relative canonical (`./`) on each page, no query strings. Canonicals stay relative (`./`) and every page stays noindex. theoldshelf.com is not written into a canonical.

Frozen set slugs come from the category and stay put if a title changes. Cassette is `radhika-cassette` as locked. Examples: `/india/`, `/india/matchbox-labels/`, `/india/pichkari/`, `/india/rooh-afza/`, `/japan/ramune/`, `/united-states/view-master/`.

Home, country, and set pages are real HTML. Header, country index (including Mexico, Brazil, South Korea, Russia, Turkey, Nigeria), and every card are `<a href>` in the first HTML. Hashes are not the URL. No page was made for an empty gap. No Product or Offer schema. Pages send `noindex`.

Lena must check these files before anything goes live. A preview before real URLs must stay noindex.

## Paper

The ground is a generated worn-paper tile (`css/paper.jpg`): uneven tone, fiber lines, and faint stains. Cream, ink, and label red are unchanged.
