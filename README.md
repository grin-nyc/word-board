# Word Building Board

A free, single-page word building board for structured literacy (Orton-Gillingham style) lessons. Students build words with letter tiles, map sounds to spellings in sound boxes, work through word chains, and mark syllables with scoops and dividers.

It runs in any modern browser on a smartboard, laptop, Chromebook, or tablet. There is nothing to install and no account to create, and nothing students do leaves their device.

---

## Contents

1. [What's included](#whats-included)
2. [Quick start](#quick-start)
3. [The screen at a glance](#the-screen-at-a-glance)
4. [The tile tray](#the-tile-tray)
5. [Building words on the Board](#building-words-on-the-board)
6. [The Orthographic Mapper](#the-orthographic-mapper)
7. [Silent e](#silent-e)
8. [Word chains](#word-chains)
9. [Scooping and dividing syllables](#scooping-and-dividing-syllables)
10. [Drawing and erasing](#drawing-and-erasing)
11. [Colored markers and the heart](#colored-markers-and-the-heart)
12. [Toolbar reference](#toolbar-reference)
13. [Keyboard shortcuts](#keyboard-shortcuts)
14. [Tile colors](#tile-colors)
15. [Saving and privacy](#saving-and-privacy)
16. [Putting it on GitHub Pages](#putting-it-on-github-pages)
17. [Updating to a new version](#updating-to-a-new-version)
18. [Troubleshooting](#troubleshooting)

---

## What's included

| File | What it is |
|---|---|
| `index.html` | The whole app: page, styles, and code in one file (about 75 KB). |
| `README.md` | This guide. |

The only outside resource is two fonts from Google Fonts (Andika for tiles, Lexend for buttons). If they can't load, the board falls back to similar fonts that are already on the computer and keeps working.

---

## Quick start

1. Open the board in a browser.
2. Tap a letter in the tray at the top. It appears on the board.
3. Keep tapping letters. Each one lands right after the last, so they join into a word.
4. Drag tiles around to rearrange them. Drag a tile back up to the tray to remove it.
5. Tap **Mapper** in the bottom toolbar to switch to sound boxes.
6. Tap **Chains** to run a word chain lesson.

---

## The screen at a glance

```
┌──────────────────────────────────────────────┐
│  Tabs: Basic Tiles · Glued Sounds · ...      │  ← Tile tray
│  [a][b][c] ...  [sh][th] ...  [e]  ♥ ■ ■ ■   │
├──────────────────── ^ ───────────────────────┤  ← Arrow tab: hide or show the tray
│                                              │
│              Board or Mapper                 │  ← Work area
│                                              │
├──────────────────────────────────────────────┤
│ Board Mapper Chains │ Move Draw Erase ...    │  ← Toolbar
└──────────────────────────────────────────────┘
```

- **Tile tray (top):** all the tiles, grouped into tabs.
- **Arrow tab:** the small tab under the tray. Tap it to fold the tray away so the board gets the whole screen. Tap it again (it turns green and points down) to bring the tiles back.
- **Work area (middle):** either the free-form **Board** or the **Mapper** with sound boxes.
- **Toolbar (bottom):** screen switch, drawing tools, pen colors, tile actions, undo, size, and board color.

---

## The tile tray

Tap a tab to see its tiles. The tray always keeps the same height, so the board doesn't jump when you switch tabs.

| Tab | Tiles |
|---|---|
| **Basic Tiles** | Letters a–z (qu as one tile); digraphs and endings (sh th ch wh ph tch dge ff ll ss zz ck); silent e; markers. The **Show Initial and Final Blends** button adds blends (bl cl fl gl pl sl spl br cr dr fr gr pr tr scr sk sn sm sp sw tw str; nd nt mp ft st ct). |
| **Glued Sounds** | Letters, glued sounds (ing ang ong ung ink ank onk unk), digraphs, silent e, markers, and the same blends button. |
| **Advanced Vowels** | Vowel teams (ee ea ai ay oa ow oe oo ie igh ou oi oy au aw ue eu), r-controlled (ar or er ir ur air ear oar ore our oor), silent e. |
| **Prefixes, Roots & Suffixes** | Prefixes (re de pre pro un in mis dis con sub non mid trans inter anti); roots (ject tract rupt struct sist gress sect port form tort cur fer mote spect vis vid); suffixes (s es ing ed er est ful less able ible ish ive ly en ness ment al); advanced suffixes ((t)ion (s)ion (c)ian (t)ious (c)ious (x)ious (t)ient (c)ient (t)iate (c)iate ture). The letter in parentheses is the one that comes before the suffix. |
| **Capital Letters** | A–Z (QU as one tile). |
| **Syllable Labels** | Pill-shaped labels: closed, open, magic e, vowel teams, r-controlled, consonant le, with short on-screen instructions. |

**Adding tiles:**

- **Tap** a tile to place it after the last tile you added (or in the first open space).
- **Drag** a tile from the tray and drop it exactly where you want it.
- **Type** a letter on a keyboard to add it (see [Keyboard shortcuts](#keyboard-shortcuts)).

---

## Building words on the Board

The **Board** is a free-form workspace with a light grid.

- **Move a tile:** drag it.
- **Snap together:** drop a tile near another tile in the same row and it slides flush against it, so letters join into a word.
- **Select a tile:** tap it. A dashed blue outline appears and the **Rotate**, **Copy**, and **Remove** buttons turn on.
- **Remove a tile:** drag it up onto the tray (the tray turns pink and says "Let go to remove the tile"), or select it and tap **Remove**.
- **Rotate:** turns the selected tile a quarter turn each tap.
- **Copy:** places a duplicate right next to the selected tile.
- **Bigger / Smaller:** changes the size of every tile (four sizes).
- **Yellow / Green:** changes the board color.
- **Several hands at once:** on touch screens, more than one student can drag tiles at the same time.

---

## The Orthographic Mapper

Tap **Mapper** in the toolbar. The Board and the Mapper each keep their own tiles and drawings, so you can switch back and forth without losing work.

The Mapper has three rows:

1. **Sound boxes:** one box per sound (phoneme).
2. **Dots:** one under each box. Students tap a dot as they say each sound, and it turns dark.
3. **Write it:** handwriting lines (top line, dashed middle line, bottom line) for writing the word with the pen.

The steps line across the top reads: **1** Say it · **2** Tap a dot for each sound · **3** Put a tile in each box · **4** Write it · **5** Read it.

### A typical routine

1. Say a word, for example "ship." Students repeat it.
2. Set the number of sound boxes with **Fewer** and **More** (the number between them shows the count). "Ship" has 3 sounds: /sh/ /i/ /p/.
3. Students tap a dot for each sound while saying it.
4. Students put one tile in each box: **sh** · **i** · **p**. Tapping or typing a tile fills the next empty box. Dragged tiles snap into the nearest empty box.
5. Students tap **Draw** and write the word on the lines.
6. Students read the word.
7. Tap **Next word** to clear the tiles, writing, and dots for the next word.

### Tips

- A digraph like **sh** or a team like **igh** goes in **one** box, because it spells one sound. This is the key idea of orthographic mapping.
- Colored markers can go in the boxes too: map sounds with colors first, then with letters.
- Tiles shrink automatically when needed so all the boxes and lines fit the screen. Fold the tray away (arrow tab) for bigger tiles.

---

## Silent e

The **silent e** tile is gray with a dashed border, so it looks different from an e that makes a sound. It's in the Basic Tiles, Glued Sounds, and Advanced Vowels tabs.

On the Mapper, silent e **does not go in a sound box**, because it makes no sound. It goes in the dashed **"silent e, no sound"** spot after the last box, which has no dot under it. Once it's placed, a red arrow jumps from the e, over the consonant, back to the vowel, showing that the e makes the vowel say its name.

Example, "phone": **ph** · **o** · **n**, three boxes and three dots, with **e** in the silent spot and the arrow pointing to **o**.

On the Board, silent e is a regular movable tile.

---

## Word chains

A word chain is a list of words where each word changes **one sound** from the word before, for example:

> ship → shop → chop → chip → chin → thin

Students keep their tiles and swap only the tile that changed. That makes them listen for what's different instead of rebuilding the word from scratch.

### Starting a chain

1. Tap **Chains** in the toolbar.
2. Pick a ready-made chain, or one of **My chains**:

| Chain | Words |
|---|---|
| Short vowels | sat sit sip tip top hop hot hat ham him |
| Digraphs | ship shop chop chip chin thin this with wish fish |
| Blends | lap clap clip slip slap flap flat flag lag lap |
| Glued sounds | sing sang rang ring rink sink sank tank thank think |
| Silent e | hop hope rope robe rob rod rode code cone phone |
| Vowel teams | see bee beet meet meat heat seat sat sail rail |

Starting a chain clears the current screen. **Undo** brings the old work back if you need it.

### The chain bar

A dark bar appears at the top left of the board:

| Control | What it does |
|---|---|
| Chain name | Which chain is running (hidden on small screens). |
| **‹** | Go back one word. |
| Word | Hidden as • • • by default, so students work from what they hear. |
| 2 / 10 | Position in the chain. |
| **Show / Hide** | Reveal or hide the word. |
| **Next ›** | Go to the next word. Shows "Last word" at the end. |
| **✕** | End the chain. |

When you move to the next word:

- **Tiles stay** on the board.
- The writing and dots clear.
- On the Mapper, the **number of sound boxes changes** to fit the new word.

The Mapper's **Next word** button also moves the chain forward. On the last word, it ends the chain and clears the board.

### Making your own chain

1. Tap **Chains**.
2. Under **Make your own**, give it a name (optional), for example "Short o week 3."
3. Type the words in order, separated by spaces, commas, or arrows: `hop, hope, rope` or `hop → hope → rope`.
4. Tap **Save & start**.

Your chain appears under **My chains** next time. Tap **✕** next to a saved chain to delete it.

### How sound boxes are counted

The board counts sounds from the spelling. It treats digraphs, vowel teams, r-controlled spellings, double letters (ff ll ss zz ck), and **ng** as one sound each, and drops a final silent e in vowel-consonant-e words. A few examples: ship = 3, phone = 3, thank = 4, train = 4, care = 2.

Unusual spellings can come out wrong. **To set the count yourself, type the word with dashes between the sounds:**

```
t-r-ai-n    (4 boxes)
b-o-x       (3 boxes)
```

The dashes are hidden when the word is shown.

---

## Scooping and dividing syllables

These tools support syllable work on either screen.

### Scoop

Tap **Scoop**, then drag under a syllable from its first letter to its last. A smooth arc appears. Students say the syllable as they draw it.

**Why scoop?** It helps students see a long word as a few small chunks they already know how to read, instead of guessing from the first letters. A common routine for "rabbit":

1. Build **r a b b i t**.
2. **Divide** between the two b's.
3. Label each syllable **closed** (Syllable Labels tab).
4. **Scoop** "rab" and "bit" separately, reading each one.
5. Draw one long scoop under the whole word and read "rabbit."

### Divide

Tap **Divide**, then tap between two tiles. A straight line drops into the gap, as tall as the tiles. You can also drag up or down to draw a divider of any length anywhere.

Scoops and dividers use the current pen color (black or red) and work with **Erase**, **Undo**, and **Wipe ink**.

---

## Drawing and erasing

| Tool | Use |
|---|---|
| **Draw** | Freehand pen. |
| **Black pen / Red pen** | Pen color. Choosing a color also switches to Draw (unless Scoop or Divide is on). |
| **Erase** | Wide eraser for ink, scoops, and dividers. It doesn't remove tiles. |
| **Wipe ink** | Removes all drawing on the current screen and leaves the tiles. |

While any drawing tool is on, a dark message appears at the bottom right with a **Move tiles** button to go back.

**Moving a tile while drawing:** press and hold the tile for about half a second, then drag it.

---

## Colored markers and the heart

**Colored squares** (green, yellow, red, orange, blue, purple, pink) are for sound work without letters. Each color stands for one sound:

- "ship" = 3 squares, because there are 3 sounds, even though there are 4 letters.
- The same color used twice shows a repeated sound, as in "dad."
- Swapping one square shows which sound changed: cat → cap changes only the last square.

Doing this before adding letters keeps spelling from getting in the way of hearing the sounds. The squares can go in the Mapper's sound boxes.

The **heart** marks the irregular ("learn by heart") part of a heart word. Place it above the tricky letters. It never goes in a sound box.

---

## Toolbar reference

| Group | Button | What it does |
|---|---|---|
| Screen | **Board** | Free-form workspace. |
| | **Mapper** | Sound boxes, dots, and writing lines. |
| | **Chains** | Opens the word chain menu. |
| Sound boxes *(Mapper only)* | **Fewer / More** | 1 to 8 sound boxes. The number between them shows the count. |
| | **Next word** | Next word in a chain, or clears the board for a new word. |
| Mode | **Move** | Drag and select tiles (default). |
| | **Draw** | Freehand pen. |
| | **Erase** | Eraser. |
| | **Scoop** | Syllable arcs. |
| | **Divide** | Syllable dividers. |
| Pen color | **Black pen / Red pen** | Ink color for Draw, Scoop, and Divide. |
| Selected tile | **Rotate / Copy / Remove** | Act on the selected tile. |
| History | **Undo / Redo** | Up to 150 steps, separate for each screen. |
| View | **Full screen** | Fills the whole screen. Hidden if the browser doesn't allow it. |
| Clear | **Wipe ink** | Removes drawing only. |
| | **Clear all** | Removes tiles and drawing. Tap twice to confirm ("Tap again"). Undo brings it back. |
| Tile size | **Smaller / Bigger** | Four tile sizes. |
| Board color | **Yellow / Green** | Board background. |

---

## Keyboard shortcuts

| Key | Action |
|---|---|
| **a–z** | Add that letter tile. |
| **Shift + letter** | Add a capital letter. |
| **q** | Adds **qu** (Shift + Q adds **QU**). |
| **Arrow keys** | Nudge the selected tile. Hold **Shift** for bigger steps. |
| **Delete / Backspace** | Remove the selected tile. |
| **Ctrl/Cmd + Z** | Undo. |
| **Ctrl/Cmd + Shift + Z** or **Ctrl + Y** | Redo. |
| **Esc** | Deselect, return to Move, or close the Chains menu. |
| **Tab**, then **Enter / Space** | Add a tray tile, or select a board tile, without a mouse. |

Typing letters doesn't add tiles while you're typing in the Chains menu.

---

## Tile colors

| Color | Used for |
|---|---|
| Black | Consonants, digraphs, blends |
| Red | Vowels and vowel teams (each team is one vowel sound) |
| Blue | Glued sounds |
| Purple | R-controlled vowels |
| Gold (gold group) | Prefixes |
| Green (green group) | Roots |
| Red (pink group) | Suffixes |
| Dark red | Advanced suffixes |
| Gray, dashed | Silent e |

---

## Saving and privacy

- Everything saves automatically in the browser's local storage: tiles, drawings, box count, saved chains, the open tab, tile size, board color, and whether the tray is folded.
- Saves are kept **per browser, per device, per website address.** A board on your laptop won't appear on a classroom tablet, and the GitHub copy and any other copy keep separate saves.
- Clearing the browser's history and site data, or using a private or incognito window, starts fresh.
- No accounts, no tracking, and no server. Nothing students build is sent anywhere.

---

## Putting it on GitHub Pages

1. Sign in to GitHub and create a new **public** repository, for example `word-board`.
2. Tap **Add file → Upload files**, add `index.html` and `README.md`, and tap **Commit changes**.
3. Open **Settings → Pages**.
4. Under **Build and deployment → Source**, choose **Deploy from a branch**.
5. Under **Branch**, choose `main` and `/ (root)`, then tap **Save**.
6. Wait a minute or two. The site is live at:

```
https://<your-username>.github.io/word-board/
```

Bookmark that address on classroom devices, or add it to the home screen on a tablet.

---

## Updating to a new version

1. In the repository, tap **Add file → Upload files**.
2. Upload the new `index.html`. It replaces the old one because the name is the same.
3. Add a short description of what changed and tap **Commit changes**.
4. The site updates within a minute or two. If you still see the old version, refresh the page (on a computer, Ctrl+Shift+R or Cmd+Shift+R).

Saved boards and chains on the GitHub site carry over, because the address stays the same. Older saved boards open on the Board screen.

---

## Troubleshooting

| Problem | Fix |
|---|---|
| The board looks empty after I come back | Saves are per browser and device. Check you're on the same device, browser, and address, and not in a private window. |
| Tiles are very small on the Mapper | Fold the tray with the arrow tab, use **Full screen**, or use fewer sound boxes. Tiles shrink to make the boxes fit. |
| I can't move a tile | A drawing tool is probably on. Tap **Move tiles** in the bottom-right message, or press and hold the tile. |
| Tapping letters doesn't add tiles where I expect on the Mapper | All the boxes are full. Tap **More** for another box, or remove a tile. |
| The sound box count is wrong for a chain word | Type the word with dashes between the sounds, for example `t-r-ai-n`. |
| No Full screen button | The browser or the page it's embedded in doesn't allow full screen. Use the browser's own full screen (F11 on Windows, Ctrl+Cmd+F on Mac). |
| Fonts look different | Google Fonts may be blocked on your network. The board still works with fallback fonts. |
| I cleared the board by mistake | Tap **Undo**. It works right after Clear all, Next word, and starting a chain. |
