# Changelog

All notable changes to *Life Creation*, newest first.

**Version numbers** follow the form `v0.0.0`. Each part runs from 0 to 9: after `v0.0.9` comes `v0.1.0`, and after `v0.9.9` comes `v1.0.0`.

| Version | Date | Status | Summary |
|---|---|---|---|
| v0.3.1 | 2026-11-13 | Beta | Put tools down where you aim, the printer behind the dish |
| v0.3.0 | 2026-11-13 | Beta | Dish rework: glass lids, see-through agar, sample dishes from the fridge |
| v0.2.1 | 2026-11-12 | Beta | Syringe and spill fixes, US spelling, vial labels that hide behind things |
| v0.2.0 | 2026-11-12 | Beta | UI refresh: new logo, glass HUD, keycaps that press in |
| v0.1.1 | 2026-11-03 | Beta | Ultrawide layout, UI scale and resolution settings, clearer tool states |
| v0.1.0 | 2026-11-02 | Beta | New lab interface and pause menu |
| v0.0.9 | 2026-11-02 | Beta | Fixes for built games |
| v0.0.8 | 2026-11-02 | Beta | Art pass and first ticket fixes |

---

## v0.3.1 · 2026-11-13 · Beta

Small fixes after the dish rework.

### Changes

- Tools go down where you aim: press <kbd>E</kbd> over a clear, flat spot and the syringe, the tweezers or the sample dish is set down right there. Where it can't go, it goes back to where it was, and the hint says **Put back**. Alcohol wipes still go back to their tub.
- A sample dish with samples left can be picked up too, to move it somewhere handier. <kbd>E</kbd> on a sample in the dish picks up the dish. The biohazard bin won't take it until it's empty, and says how many samples are left.
- The report printer sits at the back of the bench, behind the culture dish, so reports come out in plain view.
- The day length setting is gone: every day is as long as it was designed to be.

---

## v0.3.0 · 2026-11-13 · Beta

The dish rework: the dishes look and work like real lab glass, and the culture samples are something you keep stocked.

### Highlights

- The sample dish holds 8 samples, and they don't come back. When it's empty, carry it to the biohazard bin by the sink and press <kbd>E</kbd>: the pedal goes down, the lid flips open and the dish drops in.
- Fresh sample dishes are in the mini fridge. Its door swings open with a light inside, and <kbd>E</kbd> takes one off the stack. The game starts with none out, so your first one comes from the fridge too.
- The agar is a see-through amber gel with no shine.
- Glass dome lids: incubating sets a lid down on the culture dish instead of the purple glow, and every dish on the specimen shelf sits under its dome.
- The sample dish has a flat glass lid that tips open while the tweezers are over it.

### Changes

- An empty sample dish left on the bench for two minutes goes moldy. Bin it in time.
- The biohazard bin starts empty, with a red bag inside, and every dish you throw in stays there, so the pile grows.
- The 8 samples are scattered across the sample dish at random, never touching each other, and the colony dots are gone, so the samples are easier to see.
- How to play has a **Sample dishes** section, and the clipboard says when to get a fresh dish.
- Luminous cultures glow about a quarter less, and the bloom is softer.

### Fixes

- Bleach cleans mold in the sample dish.
- Pouring bleach on a specimen dish lifts its lid first and puts it back on after.
- The crosshair stays on while you hold the sample dish, and the bin shows **[E] Throw the dish away**.
- Closing the pause menu before ever opening Settings no longer leaves the HUD hidden.

---

## v0.2.1 · 2026-11-12 · Beta

Fixes from playtesting.

### Changes

- The syringe meter always shows the whole syringe. Holding <kbd>Shift</kbd> no longer zooms it in or shows a FINE tag; the amount still reads to the thousandth.
- A used syringe shows a badge with the reagent still inside it, until you rinse it.
- Spilled liquid never disappears. It runs down walls and the sides of things, drips from the needle when nothing is in reach, and pools on whatever is below. Puddles grow much bigger, and there's no limit on how much you can spill.
- An old puddle stays a murky puddle when there's no room for more mold, instead of vanishing.
- A wider, softer shadow under white text.
- All game text uses US spelling: mold, center, color.
- The jar on the fridge now just says **Meteorite**, without quotes.
- Vial labels hide behind things in front of them, and fade out as you walk away from the bench.

---

## v0.2.0 · 2026-11-12 · Beta

The UI refresh: a new look for every screen.

### Highlights

- A new logo on the pause and start screens, and the title is now just **Life Creation**.
- The HUD sits on glass: the hint bar, the name under the cursor, the vial labels and the version number.
- Frosted keycaps and mouse icons that press in when you press the real key.
- Glossy new buttons with a hex pattern, a slow glow and a swoosh when you point at them.
- Notifications are coloured banners that slide in and out.

### Changes

- Pause menu: metal panel frames, panels that swing in from the sides, and **Back to the lab** on glass.
- Settings: chunky tabs with icons on a rail with a DNA detail, plus new sliders, toggles, value boxes and drop-down list.
- Title plates with their badge built in, on Settings (with the close button) and How to play.
- How to play: a new header with the <kbd>H</kbd> key, an icon for each section, and the card slides in and out. When it's hidden, a small **How to play** tag waits at the top of the screen.
- When you press a key shown in a hint, the hint stays a moment longer so you can see the key press in.
- Vial labels sit in staggered rows, so they no longer overlap.
- Mouse icons are the same height as the keycaps everywhere, including **Settings → Controls**.
- The specimen shelf header is on glass.
- Navy Settings and **Lab today** panels, flat pause panels and a fainter DNA on the Settings card.

---

## v0.1.1 · 2026-11-03 · Beta

An early build of the lab, for testing.

### Highlights

- Menus and the HUD fit any screen shape, including ultrawide monitors.
- New UI scale setting (80–120%) under **Settings → Graphics**.
- Resolution is a drop-down with common sizes, plus your screen's own size.
- A **Dirty** badge on the tool card when a tool needs rinsing, and **Tainted** when the syringe still holds another reagent.

### Changes

- The tweezers bar changes colour with your squeeze: blue when open, amber when loose, green in the right grip, red when too tight.
- The clipboard is easier to read: matte paper, larger text and darker pencil.
- Mouse icons in the controls screen are all the same size.
- Hand shake is no longer a setting.
- The jar on the fridge no longer shows a notification; it still glows and makes its sound.
- Dragging up or down on a specimen in the shelf viewer now tilts it the other way.

---

## v0.1.0 · 2026-11-02 · Beta

The new lab interface and pause menu.

### Highlights

- A new **Hex Lab** interface, laid out to keep the bench clear.
- Baloo 2 and Nunito fonts throughout.
- Syringe meter with tick marks, a target notch and a **FINE** zoom (hold <kbd>Shift</kbd>).
- Vials show holographic labels and, when you look at one, a panel with its name, dose and effect.
- Pause menu (<kbd>Esc</kbd>) with resume, settings and a **Lab today** summary.
- Settings are saved between sessions.

---

## v0.0.9 · 2026-11-02 · Beta

Fixes for built games.

### Highlights

- The UI works in built games: the how-to card, the name under the cursor and most of the HUD now appear.
- New frosted UI look with a bright edge, soft shadow and lavender accents.
- The lab monitor keeps its bright screen colours.

---

## v0.0.8 · 2026-11-02 · Beta

Art pass and first ticket fixes.

### Highlights

- Softer three-tone shading, painterly surface detail and soft contact shadows.
- Repainted walls, floor and yard, plus trim, a rug, a cutting mat and fairy lights that glow at night.
- The window now shows the backyard, and the stool swivels to look out.
- Sharper printed reports, cleaner on-screen controls and a wider shelf view.
- Version number shown in the corner of the game.

---

