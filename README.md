<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="canto-mark-dark.png">
    <img src="canto-mark.png" alt="" width="110">
  </picture>
</p>

<h1 align="center">Canto</h1>

<p align="center">Your pack's own lore, told over Wolvden · an add-on for Twill</p>

<p align="center"><b>In beta</b></p>

---

Every pack has its tales. Canto lets you write yours in one file and see it on
[Wolvden](https://www.wolvden.com/): your own words softly underlined with their meanings,
your bloodlines glowing on your den, families named when two lines meet, a calendar in your
own season names, and the names you've saved for pups waiting beside the rename box.

Canto is an add-on for [Twill](https://trashgremlinx.github.io/Twill/), so Twill needs to be
installed first. Like Twill, it only reads the page you already have open.

**Canto will never play the game for you. We leave that to you.**

**[Read the full write up, and how to install it &rarr;](https://trashgremlinx.github.io/Canto/)**

**[Field Guide: Canto, the tester introduction &rarr;](https://trashgremlinx.github.io/Canto/changelog.html)**

## Install

1. Have [Twill](https://trashgremlinx.github.io/Twill/) installed and working. Its stag sits in
   the corner of every Wolvden page.
2. Click **[canto.user.js](https://trashgremlinx.github.io/Canto/canto.user.js)** and press
   **Install** when Tampermonkey asks.

Then open Wolvden. Canto's campfire sits just above Twill's stag. Click it, or press `Alt+C`.
In **Files**, load your lore file, start a new pack, or try the sample
[Hollowmere pack](hollowmere-lore.md).

Updates happen by themselves after that, the same way Twill's do. Nothing you have written is
lost when it updates. If you installed version 0.1.0, click the install link once more: versions
from 0.1.1 on keep themselves up to date.

## What is in it

Five tabs in Canto's hub, and the pieces it adds to your own Wolvden pages.

| | |
|---|---|
| **Language** | Your pack's own words, softly underlined on your den and your own wolves. Hover or tap one for its card: the word, how to say it, what kind of word, its meaning |
| **Bloodlines** | A card under Twill's Lore panel with the wolf's line, its role and its lore birth, all changeable right there. On your den each wolf shows its line's colour in the style you pick (a glow, an edge, its name bar and more), and the **Show** bar lights one bloodline at a time. Studs you borrow from other players go under **Outside studs** |
| **Families** | Two lines meet to make a named family, which is a line of its own and can meet another later. On a pup's Family page, Canto asks you to name the family when its parents' lines have never met |
| **Calendar** | Count your pack's years by Wolvden's seasons or by one wolf's age, give the seasons your own names, and add events that happen every year or just once. What's coming shows on the wheel and at the top of the hub |
| **Names waiting** | Names saved for future pups, optionally for a line. Offered on a pup's card and beside Wolvden's rename box: tap to copy. Crossed off once a wolf wears one, with an undo |
| **Files** | Keep a lore file for each pack and switch between them. **Save my lore file** writes a fresh copy, **Copy what changed** gives just the new lines to paste |
| **Help & About** | Report a problem, ask a question or suggest an idea, with the form filled in for you. Links to learn more, and everything about Canto |

And a **look** of its own in bark and ember, or one that follows your Twill theme.

## Your lore file

One plain text file per pack, written in Markdown. Every section is optional, and anything
Canto doesn't recognise is kept and written back untouched.

```
# Hollowmere Pack
Kept by Fallowe

## Language
Ashvenn: the hour the fire is let burn low, when the last tale of the night is told.
  Say: ASH-ven. Kind: noun. See also: Emberwake

## Lines
Hollow: #3fc5a0, the first wolves of the valley
Ashen: #d9dee6, from the burnt ridge

## Families
Hollow + Ashen = Emberfall

## Wolves
Ashpaw (12345678): Emberfall, Healer, born late Greening, Year 4

## Outside studs
Ravenmoor (18822101): Ashen

## Roles
Alpha, Healer, Scout, Storykeeper

## Calendar
Count: seasons from 2026-09-04
Seasons: Greening, Longlight, Ashfall, Deepcold
Every year, late Ashfall: the Ember Walk

## Names
Hollow: Fern, Ash, Bramble
Rook, Wren, Tallow
```

## What it will not do

- It **never loads a page for you**. No randomly opened tabs.
- It **never clicks, submits or fills a form for you**. Names waiting are copied for you to paste
  yourself.
- It **never refreshes** anything on a timer.
- It **sends nothing anywhere**. No server, no account, no tracking, no analytics. The only thing
  it loads is its two fonts, Eczar and Commissioner, from Google Fonts.
- It **does not gather up the site**. It keeps what you write, plus the parent ID numbers of
  wolves whose Family page you open, and the age of one wolf if you choose to count your years
  by it.

These are facts about the source rather than promises. There is no `fetch`, `XMLHttpRequest`,
`sendBeacon`, `WebSocket`, `setInterval`, `.submit()` or `location.href` anywhere in the file,
and the script runs with `@grant none`.

## Your data

Everything lives in your own browser's `localStorage`, under keys prefixed `canto:`, and never
leaves your machine. Clearing site data removes it, so use **Save my lore file** in Files to
keep a copy, especially before moving computers.

## Telling us what you find

Bugs, ideas and questions are all welcome, with or without a Discord account. Use the form at
the bottom of the [Field Guide](https://trashgremlinx.github.io/Canto/changelog.html#report),
or post in **#beta-test** under the Twill category on the Society of Fur Discord.

## Thanks

**Wolvden, by Lioden Ltd**, for the game, the art and the team behind it. This is an unofficial
fan tool and is not affiliated with or endorsed by them.

**The Society of Fur**, and everyone testing Canto, for thoughts, wishes and feedback throughout.

## Licence

Canto is a free, world building specific add-on for Twill that works in conjunction with the
modules and your own lore files and libraries. Keep the credit where it is, and do not sell it or
hand on a copy you have edited. An edited copy could break every promise above while still
wearing this name, which is the one thing that cannot be allowed to happen.

**[Read the licence](LICENCE.md)**

## Come say hello

- [Join us on Discord](https://discord.gg/ZQDz8ANTUR)
- [The guild on Wolvden](https://www.wolvden.com/g/society/991)

Bugs, ideas and requests are all welcome. By [Fallowe](https://www.wolvden.com/profile/145906).
