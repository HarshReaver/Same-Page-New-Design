# Same Page, New Design: Chai Adda

A small experiment: one made-up café website, built twice with identical words.

- `before.html` - the page built the ordinary way, with no design skill.
- `after.html` - the same page redesigned using the Impeccable design skill. Only the design changed; every word is the same.
- `prompts.md` - the two prompts used.

**See them online:** [before.html](https://harshreaver.github.io/Same-Page-New-Design/before.html) and [after.html](https://harshreaver.github.io/Same-Page-New-Design/after.html)

Chai Adda is an imaginary café near a college in Mumbai. The page has a hero with a button, an about section, a six-item menu, opening hours, location and contact, and a footer.

## The 3 most important design changes

1. **A Mumbai look instead of a generic one.** The brown block and cream background became taxi yellow and ink black, with a black-and-yellow checker band and big signboard lettering (Bungee for headings, Hind for text). Why it helps: the old page could have been for any café anywhere. The new one looks like it belongs in Mumbai, and the name Chai Adda is the loudest thing on the screen. The detector had also flagged the old Arial text and cream background as generic.
2. **A menu that reads like a chai-stall board.** Six identical bordered boxes became a ruled list on a dark board, each item with a dotted line leading to its price in large yellow numbers. Why it helps: a student can scan names and prices in one glance, and the price is no longer the quietest thing in the row.
3. **The button now leads to something worth seeing, and the page works with a thumb.** "See today's special" scrolls to a bold yellow ticket that pulses when you arrive. The phone number and email are tap-to-call and tap-to-mail, buttons and links are at least 44px tall, and the layout is a single column on a phone that becomes two or three columns on larger screens. Why it helps: the main action pays off clearly, and the page is usable one-handed, which is how students will open it.

## Done when

- [x] Both files exist: `before.html` and `after.html`.
- [x] The words in both match (checked by extracting the visible text and page title from each file and comparing: 199 words, no differences).
- [x] The redesign works on a phone (single-column layout, fluid type sizes, tap targets of 44px or more, tap-to-call and tap-to-mail links, no fixed widths). Checked at 375 px phone width in the browser: no sideways scrolling.
- [x] 3 design changes named (above).
