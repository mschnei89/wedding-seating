# Wedding seating chart

An interactive seating planner for our reception. One self-contained HTML page — no build step, no server, no dependencies.

**Live:** https://mschnei89.github.io/wedding-seating/

## The room

- **Head table** — tables 1–4, connected horizontally, six seats each (three top, three bottom).
- **Floor** — tables 5–16, four columns of three connected vertically, six seats each (three left, three right).
- 96 seats, 94 guests.

Floor columns run `5/6/7`, `8/9/10`, `11/12/13`, `14/15/16`, with the first table in each column nearest the head table.

## Using it

- Click a guest in the left panel, then click a seat. Or drag a name onto a seat.
- Drag seat → seat to swap two people.
- Right-click a seat to lock/unlock it.
- Click a seated guest for their tags, plus Lock and Remove.
- **White** = empty, **black** = filled, **gold** = locked.

Search by name or tag, filter to one tag, group by tag or sort A–Z, and hide guests already seated.

## On a phone

The page turns into an app shell rather than a shrunken desktop toolbar:

- A slim header with your names, the current design underneath — tap it to switch designs — and a single **⋯** menu holding everything else.
- A **Chart / Roster** segmented control. Roster is the fastest way to look someone up.
- Tap **Guest list**, pick a name, and the sheet gets out of the way so you can tap a seat. The button becomes **Cancel** while you're placing, and the bar tells you who you're holding.
- The room opens scaled to fit. The floating pill zooms — go in a couple of steps before tapping seats, since everything is small at full-room scale.

## Designs

The page opens on a set of saved designs and lets you keep several side by side:

| Design | Idea |
| --- | --- |
| **Mark 1** | **The plan — everyone in their seat. This is what opens by default.** |
| Head table (locked) | The confirmed head-table picks, nothing else placed |
| Option A — by circle | Earlier draft: each table is one community, kept intact |
| Option B — mix & mingle | Earlier draft: every table bridges two circles |
| Option C — concentric | Earlier draft: distance from the head table tracks closeness |

Use **Save as** to snapshot the current arrangement under a new name, **New** for an empty one, and the dropdown to switch. Every edit auto-saves.

## Your copy is yours

Edits save to your own browser only — they are not shared with anyone else and they don't change what other people see. Use **Export JSON** to save your arrangement to a file and **Import JSON** to load someone else's. `seating-designs.json` in this repo is the current set.

**Roster view** lists every table as text, and **Print** hides the sidebar for a clean page.
