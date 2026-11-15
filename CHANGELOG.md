# Changelog

All notable changes to *Life Creation*, newest first.

**Version numbers** follow the form `v0.0.0`. Each part runs from 0 to 9: after `v0.0.9` comes `v0.1.0`, and after `v0.9.9` comes `v1.0.0`.

| Version | Date | Status | Summary |
|---|---|---|---|
| v0.5.5 | 2026-11-15 | Beta | Two-handed jobs: your left hand pulls the vial corks and lifts the dish lid |
| v0.5.4 | 2026-11-15 | Beta | The starter shed: a pine workbench, plywood floor, corked vials that pop open as you draw |
| v0.5.3 | 2026-11-15 | Beta | Run and crouch, rebindable keys, a view that leans further, hands that stay out of the bench |
| v0.5.2 | 2026-11-15 | Beta | Hands that feel alive, a view that follows your hand, grass in the yard, things tumble into the bin |
| v0.5.1 | 2026-11-14 | Beta | Liquids that don't mix and slosh, tools stay within reach |
| v0.5.0 | 2026-11-14 | Beta | Hands: your gloved hand holds every tool |
| v0.4.0 | 2026-11-13 | Beta | A waste beaker that fills up, wipes from the tub |
| v0.3.2 | 2026-11-13 | Beta | A 3D yard all around the shed |
| v0.3.1 | 2026-11-13 | Beta | Put tools down where you aim, the printer behind the dish |
| v0.3.0 | 2026-11-13 | Beta | Dish rework: glass lids, see-through agar, sample dishes from the fridge |
| v0.2.1 | 2026-11-12 | Beta | Syringe and spill fixes, US spelling, vial labels that hide behind things |
| v0.2.0 | 2026-11-12 | Beta | UI refresh: new logo, glass HUD, keycaps that press in |
| v0.1.1 | 2026-11-03 | Beta | Ultrawide layout, UI scale and resolution settings, clearer tool states |
| v0.1.0 | 2026-11-02 | Beta | New lab interface and pause menu |
| v0.0.9 | 2026-11-02 | Beta | Fixes for built games |
| v0.0.8 | 2026-11-02 | Beta | Art pass and first ticket fixes |

---

## v0.5.5 · 2026-11-15 · Beta

Your left hand gets to work: it pulls the corks out of the vials and lifts the lid off the sample dish.

### Highlights

- Corks: when you hold <kbd>LMB</kbd> over a vial with the syringe, your left hand reaches in, pinches the cork, pulls it out and sets it down on the rack beside the vial, then goes to the plunger. The syringe waits until the cork is out.
- The cork goes back in only when you haven't drawn for about two seconds, or a moment after you look away from the vial. The hand takes it back and pushes it home with a plop.
- The dish lid: when the tweezers go over the sample dish, your left hand takes the lid by its edge, lifts it open and sets it back down. The lid has a pale rim now, so it's easy to see and to hold.
- The left hand looks natural for these jobs: the fingers curl in, the thumb bends, and the hand comes in from the left, clear of the rack, the bench and your view.

### Changes

- The left hand starts from where the idle hand rests, rather than from your shoulder, and goes back there when the job is done.

---

## v0.5.4 · 2026-11-15 · Beta

The shed gets its starter look: you've just stolen an alien egg and set up in a small shed with leftover equipment, so everything is pine, plywood, tape and cork.

### Highlights

- A budget wooden lab: a pine plank workbench and a shelf screwed to the back wall, a plywood floor, a pine stool with a teal cushion, a pine sink cabinet, a cream bar fridge, and the pegboard and cork board in pine frames.
- The reagent vials have cork stoppers and strips of masking tape with the name written in marker. The Lumen tube matches the others now.
- Drawing from a vial pops its cork out: it flies up along a curve, turning as it goes, and hovers beside the neck, with a pop. Stop and it drops back in with a plop.

### Changes

- The vial rack is plain pine with screws.
- The lab monitor, the report printer and the syringe's plastic are yellowed with age, the printer has tape across its lid, and the biohazard bin has a strip of duct tape on its side.
- The specimen shelf hangs on the back wall, at the same height with the same eight slots. The monitor, which used to clamp to the shelf's post, stands on a steel pole at the bench's back corner.

---

## v0.5.3 · 2026-11-15 · Beta

You can run and crouch now, rebind every key, and lean much further toward what you reach for. Plus fixes from playing v0.5.2.

### Highlights

- Run: hold <kbd>Shift</kbd> while standing, 3.2 m/s against 1.8 walking. The waste beaker sloshes harder as you run.
- Crouch: hold <kbd>C</kbd> to lower your view and creep along at 1 m/s.
- Rebind any key: in Settings > Controls, click a key and press the new one. Letters, <kbd>Space</kbd> and <kbd>Shift</kbd> all work, a key that's already taken swaps places with the one using it, and it's saved with your settings. Every prompt in the game shows your keys, and Reset to defaults puts them back.
- Leaning reaches much further: the view leans up to 65 cm toward what you reach for, sitting or standing, and comes back quicker. Over a vial it rises a little to see the top, and stays with the vial when your aim slips off its edge, so the view no longer jumps.
- Your hands never sink into the bench: an empty hand lifts clear of the surface, and a tool in your hand comes up with it.

### Changes

- Steady hands only works sitting down, and only with the syringe and the tweezers; standing you just run. It has its own row in Settings > Controls, separate from Run, and the two can share a key.
- The sample dish's full shadow shows on the wall, not just its samples.
- Tools can't be set down inside the sample dish or through other things, so the tweezers can no longer get stuck in it. The placement preview glides from place to place.
- The tweezers lie flat on the bench with the curved part up.
- The sink and the alcohol wipes are back within easy reach, so you no longer have to stand too close to the sink to clean the syringe.
- Drawing from a vial, its name panel steps aside and only the other vials' names stay.
- The key rows in Settings > Controls fade in with the rest of the page.
- After pointing at a specimen, your hand eases away to your shoulder in one smooth move instead of stopping at several points, and two sudden jumps as it came in are gone.

---

## v0.5.2 · 2026-11-15 · Beta

Your hands come alive, the view follows them, and the yard gets grass.

### Highlights

- Your hands are no longer stiff: they trail a little behind when you turn and catch up, rise and fall with your breath, and the fingers drift on their own and now and then ripple in and out. A hand holding a tool settles its grip now and then, and the tool takes the same sway.
- Tap the meteorite jar and your knuckles knock twice on the glass, with a clink each time.
- Now and then, looking at a specimen you made, your finger points at it. A docile one is beckoned, a calm one gets a little wiggle, a curious one a slow circle to follow, a feisty one a tap it chases and snaps at, and a vicious one snaps back so you jerk away. The microbe watches your fingertip.
- Grass all over the yard: thick along the fence and round the shed, sparser further out, swaying in a slow breeze.
- Dishes and wipes you throw in the biohazard bin fall in with real physics, tumble onto what's already there and settle with a thud.

### Changes

- Reaching for something far, the view now follows your hand forward (up to 30 cm) instead of your arm stretching, and glides there and back gently. Picking a tool up no longer moves the view.
- Tools only go out to what you look at within about 0.95 m of you; further away, or standing back from the bench, they stay by your hand. Sitting, the far vials and the beaker are still reached by leaning in.
- A syringe with liquid in it stays out over the bench with no ghost. You can set it down with <kbd>E</kbd>, stand up and walk with it. Looking away, a tool with a sample or liquid in it comes along with your view instead of hanging in the air.
- Wipes only go moldy when they're used up. A part-used one on the bench stays clean and says how much is left; only used-up ones count for "Bin used wipes".
- The name tags over the reagent stand only show while you look at a vial.
- Your sleeve and shoulder move forward with your hand, so your arm never looks longer than a real arm.

---

## v0.5.1 · 2026-11-14 · Beta

Fixes and polish from playing v0.5.0, and a waste beaker whose liquids keep their own colors.

### Highlights

- The waste beaker no longer mixes everything into one color: each reagent keeps its own color and folds through the others in slowly drifting bands.
- Carry the beaker and its liquid sloshes like water: the surface tilts away from the way you move it, rocks back and forth and settles, with ripples on top.

### Changes

- Tools only go down on the half of the bench nearest your stool, or back on their own spot. Aim further away and they land at the nearest spot you can reach.
- Pressing <kbd>E</kbd> where a tool can't go puts it at the nearest place it can, shown by the light-blue ghost, instead of sending it back across the lab.
- The view leans in more gently when you draw from a vial, so it's no longer a quick lurch.
- Only the syringe and the tweezers shake in your hand now; the bleach, beaker, wipe and sample dish are held steady.

---

## v0.5.0 · 2026-11-14 · Beta

You have hands now: a gloved hand in a lab-coat sleeve holds every tool.

### Highlights

- Light-blue nitrile gloves under a white lab-coat sleeve. Every tool has its own grip: the syringe with your thumb on the plunger, the tweezers held like a pen that closes as you squeeze, the bleach bottle and waste beaker round the middle like a mug, the wipe pinched by its gathered middle, the sample dish carried like a plate, and a relaxed hand when you hold nothing.
- Drawing from a vial, your left hand comes in to pull the plunger out, and goes away when you stop.
- Looking at bare bench, or at something the tool can't be used on, the tool waits by your hand and a light-blue ghost shows where <kbd>E</kbd> would set it down. It still goes out to whatever you can use it on, or while you hold the left mouse button.
- Sitting at the bench with a tool, the view leans in toward things that are too far to reach.
- With a sample in the tweezers, they stay out over the bench with the aim marker, so you can see where it would land, and you can't stand up or walk off with it.

### Changes

- The sample dish and the waste beaker turn with you, so they stay put in your hand.
- A wipe goes to the ghost spot, and stays in your hand with a message if there's nowhere to put it. Looking at the biohazard bin with a wipe says "Throw the wipe away".
- A sample that falls on the floor goes back to its dish, dirty.
- Your sleeves fade out just behind the cuff, so your arms don't run the whole length of the view.

---

## v0.4.0 · 2026-11-13 · Beta

The waste beaker and the alcohol wipes are things you look after now, like the sample dishes.

### Highlights

- The waste beaker fills up with what you squirt into it, and the colors mix. The paper clumps are gone.
- When it's nearly full, carry it to the biohazard bin and press <kbd>E</kbd> to pour it in. Then rinse it under the tap before it takes more.
- Keep squirting into a full beaker and it runs over the side, leaving a spill to clean up.
- <kbd>E</kbd> on the wipe tub gives you a fresh wipe. Used wipes stay where you put them and go moldy if you leave them out: throw them in the biohazard bin.

### Changes

- The biohazard bin fills up with the waste you pour in, and what you throw in after that lands on top.
- The waste beaker and the wipes can be put down anywhere, like the other tools. A wipe drops right where you let go, and a clean one goes back in the tub with <kbd>E</kbd>.
- Waste isn't allowed down the sink.
- New notices when the beaker is nearly full or overflowing, when it needs a rinse, and when a used wipe is left out or goes moldy.
- The clipboard's clean-up list asks you to empty the waste beaker and bin used wipes, and How to play has a Waste beaker section.

---

## v0.3.2 · 2026-11-13 · Beta

The view out of the window is a real 3D yard now, all around the shed.

### Changes

- Grass all around the shed, inside a white picket fence with a gap at the front for a gate.
- Trees, bushes and lavender beds in the yard. From the stool, a pink blossom tree and a tall slim tree frame the window and the middle of the view stays open. Stand at the window to see the flower bed and the yard up close.
- The painted trees and fence are gone, and the painted hills and clouds sit further back, behind the yard.

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

