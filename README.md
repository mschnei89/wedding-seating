# Wedding seating chart

Interactive seating planners for the wedding and the rehearsal dinner. Each page is one self-contained HTML file — no build step to view, no server, no dependencies.

| Page | Link |
| --- | --- |
| Wedding seating | https://mschnei89.github.io/wedding-seating/ |
| Wedding in 3D | https://mschnei89.github.io/wedding-seating/venue.html |
| Rehearsal dinner seating | https://mschnei89.github.io/wedding-seating/rehearsal_dinner.html |
| Rehearsal dinner in 3D (Minturn Saloon) | https://mschnei89.github.io/wedding-seating/rehearsal_venue.html |

## The wedding room

- **Head table** — tables 1–4, connected horizontally, eight seats each (four top, four bottom).
- **Floor** — tables 5–13, three columns of three connected vertically, eight seats each (four left, four right).
- 104 seats, 95 guests.

Floor columns run `5/6/7`, `8/9/10`, `11/12/13`, with the first table in each column nearest the head table.

## The rehearsal dinner (Minturn Saloon)

Laid out from the venue's plan. Every table seats both sides; tables along the back and left walls stand against the green banquette, so the wall side sits on the bench. Tables 10, 16 and 35 are built-in booths the venue won't move — **Move tables** rearranges the rest. Dashed seats are the flex seats at the top of each capacity range.

## Using it

- Click a guest in the left panel, then click a seat. Or drag a name onto a seat.
- Drag seat → seat to swap two people.
- Right-click a seat to lock/unlock it.
- Click a seated guest for their tags, plus Lock and Remove.
- **White** = empty, **black** = filled, **gold** = locked.

Search by name or tag, filter to one tag, group by tag or sort A–Z, and hide guests already seated. Dietary needs show as green tags.

## On a phone

The page turns into an app shell rather than a shrunken desktop toolbar:

- A slim header with your names, the current design underneath — tap it to switch designs — and a single **⋯** menu holding everything else.
- A **Chart / Roster** segmented control. Roster is the fastest way to look someone up.
- Tap **Guest list**, pick a name, and the sheet gets out of the way so you can tap a seat. The button becomes **Cancel** while you're placing, and the bar tells you who you're holding.
- The room opens scaled to fit. The floating pill zooms — go in a couple of steps before tapping seats, since everything is small at full-room scale.

## Designs

Each page opens on its current plan and lets you keep several side by side. **Save as** snapshots the current arrangement under a new name, **New** starts an empty one, and the dropdown switches. Every edit auto-saves.

## Your copy is yours

Edits save to your own browser only — they are not shared with anyone else and they don't change what other people see. Use **Export JSON** to save your arrangement to a file and **Import JSON** to load someone else's. `seating-designs.json` in this repo is the wedding's current set.

**Roster view** lists every table as text, and **Print** hides the sidebar for a clean page.
