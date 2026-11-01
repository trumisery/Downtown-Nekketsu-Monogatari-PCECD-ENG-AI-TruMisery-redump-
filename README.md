DOWNTOWN NEKKETSU MONOGATARI
English Translation - Redump Edition
Translation by TruMisery | AI-assisted project
Original Japanese voices and music

ABOUT THIS RELEASE
------------------
An English translation of Downtown Nekketsu Monogatari for PC Engine CD,
based on the Japanese Redump release, serial NXCD3019.

This release translates the game's text and graphics, adds readable English
fonts, repairs dialogue and menu presentation, and includes a restored Sound
Test and an optional new-game bonus code. Japanese voices and the original
music are retained. This release does not contain an English dub.

Release filename:
Downtown Nekketsu Monogatari [PCECD][ENG-AI][TruMisery][redump]

TRANSLATION AND TEXT
--------------------
- English story dialogue, boss conversations, shop dialogue, item-use and
  effect messages, menu text, ending narration, and staff credits.
- Revised dialogue for both player routes, including the Mami rescue scenes.
- Mixed-case English lettering, punctuation, spacing, and line breaks.
- Expanded text storage and repaired pointers and terminators so longer
  English lines do not overwrite neighboring messages or menus.
- Consistent item names across shops, inventory, and dynamic dialogue.
  Abbreviations expanded where the available display space permits.
- Corrected food, medicine, equipment, cassette, magical-item, book, and
  maximum-stat messages, with player and item names inserted correctly.
- Separate wording for learning technique books and reading ordinary books.
  Corrected Uncut Book wording while preserving its original gameplay effect.
- Default Kunio and Riki names retain their intended mixed case after the
  name-entry screen. Custom name entry retains its own keyboard behavior.
- Revised defeat text and varied gang reactions. The existing 27 reaction
  sayings are retained, with alternatives rotated for the same event.

FONTS, MENUS, AND INTERFACE
--------------------------
- Variable-width English text for dialogue, shop and inventory item names,
  and status labels, allowing readable text within the existing windows.
- Full status labels: Punch, Kick, Weapon, Throw, Speed, Defense, Endurance,
  Willpower, and Health, including saved-file status displays.
- Inventory icon, cursor, and name placement adjusted for English text.
  Learned/equipped indicators retained.
- Repaired shop list redraws, including entries without prices, and corrected
  font selection when switching between shops and other screens.
- Text-rendering timing fixes address screen jumping and display corruption
  while preserving the game's interrupt-driven display updates.
- Corrected text-advance arrow placement so it does not overlap item text.
- Shop and inventory result messages remain available for confirmation;
  menus are not slowed by a global text delay.
- Corrected Smart Glasses wording/action selection while preserving its
  original flash/shatter effect.
- Status menu label, Difficulty alignment, and Save/Load/Exit alignment
  refined for the English interface.
- Dialogue allocation repaired to prevent boss text from corrupting item
  prompts and other shared message records.

GRAPHICS AND PRESENTATION
-------------------------
- English title artwork and a visible TruMisery translation credit.
- Title lettering/shadow refinements, restored clock/building details, and
  cityscape artwork preserved beneath the outlined translation credit.
- Translated exterior and interior shop signs, including bookstores,
  bakeries, coffee shops, rice shops, pharmacies, fast-food shops, sushi
  shops, candy shops, fish shops, shoe shops, record shops, toy shops,
  the Mystery Shop, and the bathhouse.
- Original sign frames, wood grain, folded curtains, book illustrations,
  hanging panels, shading, and decorative motifs retained or reconstructed
  around the English lettering. Matching sign copies updated where needed.
- Bathhouse labeling corrected, with entrance pictograms and curtain artwork.
- English garbage/pickup notices and other scenery lettering.
- First-town palette and compressed-map repairs, including road and stray
  tile artifacts; selection-screen pixel repair.
- Ending text and credit data repaired so the ending can advance through
  the credits, publisher screens, and return to player selection.

OPTIONAL NEW-GAME BONUS CODE
---------------------------
On the title/logo screen AFTER the prologue, enter:

    UP, UP, UP, DOWN, DOWN, DOWN

Release the direction between presses. A confirmation chime indicates
acceptance. Press RUN to continue into the game; RUN is not a seventh
directional-code input. Do not enter the code on the prologue text screen.

Both player records receive:
- 99,900 yen.
- All eight base stats set to 63.
- Current and maximum stamina set to 127.
- Mach Kick and Western Boots in inventory.

The technique and boots are not automatically learned or equipped. Use them
through the inventory. Rewards apply during new-game initialization.
Starting without the code retains the normal starting loadout.

RESTORED SOUND TEST
-------------------
At the title screen, press SELECT to open Sound Test.

SELECT       Cycle CD / BANK / VOICE / PSG modes.
LEFT/RIGHT   Change the selection by 1.
UP/DOWN      Change the selection by 16.
I or II      Play the selection, or load the selected BANK.
RUN          Stop playback and return to the title screen.

To hear voices, select BANK and press I or II to load it first. Then select
VOICE, choose a clip, and press I or II to play it. Voices are Japanese.
Selection numbers are hexadecimal. Ranges: CD 00-14, BANK 00-2B, PSG 00-7F.
Voice counts vary by bank; some original PSG IDs are unused or silent.
Previously unreachable original audio may be accessible through this menu.

REQUIRED ORIGINAL DISC
----------------------
Title:       Downtown Nekketsu Monogatari (Japan)
System:      NEC PC Engine CD / TurboGrafx CD
Edition:     Original
Serial:      NXCD3019 (NXCD-3019 on the disc)
Redump:      http://redump.org/disc/66296/
Track count: 23 (21 audio tracks and two Mode 1 data tracks)
BIN total:   397,927,824 bytes / 169,187 sectors of 2,352 bytes

Use the split-track Redump BIN/CUE set. The patch applies ONLY to Track 02.
Keep Track 01 and Tracks 03-23 unchanged. Track 23 does not need a patch.
The original track lengths, stored pregaps, and CUE indices are preserved.

Required Track 02:
Downtown Nekketsu Monogatari (Japan) (Track 02).bin
Size:   5,748,288 bytes
CRC32:  9960efd9
MD5:    b449972ca1b9c34af1e9672b860f2527
SHA-1:  e765643133ef17ee6fb26f0bd19b79cdf8de9200

PATCHING WITH DELTA PATCHER
--------------------------
1. Make a separate working copy of the original 23-track BIN/CUE set.
2. In Delta Patcher, select the original Japanese Track 02 BIN as the
   Original file. Select this patch as the XDelta patch:

   Downtown Nekketsu Monogatari [PCECD][ENG-AI][TruMisery][redump].xdelta

3. Apply the patch to the working copy of Track 02. Keep checksum validation
   enabled. A mismatch means the input is not the required source file.
4. To use the included translated CUE, name the patched output:

   Downtown Nekketsu Monogatari [PCECD][ENG-AI][TruMisery][redump] (Track 02).bin

5. Copy all 22 unchanged original BINs beside the patched track and rename
   them with the same release prefix and their respective track numbers:

   Downtown Nekketsu Monogatari [PCECD][ENG-AI][TruMisery][redump] (Track NN).bin

   NN runs from 01 through 23. Only Track 02 contains patched data.
6. Put the included translated CUE in that folder. Verify that every FILE
   entry matches its BIN filename exactly, then load the CUE to play.

Alternative: keep the original Redump filenames in the working copy,
replace only Track 02 with the patched output under its original name,
and use the original Redump CUE. Renaming files does not change their hashes.

Do not select the CUE, an audio track, a CHD, a 2,048-byte-sector ISO, or a
merged full-disc BIN as the patch input. This patch expects the raw Redump
Track 02 including its stored pregap.

COMMAND-LINE ALTERNATIVE
------------------------
With xdelta3 available, run the following as ONE line from a working folder
containing the original Track 02 and the patch:

xdelta3 -d -s "Downtown Nekketsu Monogatari (Japan) (Track 02).bin" "Downtown Nekketsu Monogatari [PCECD][ENG-AI][TruMisery][redump].xdelta" "Downtown Nekketsu Monogatari [PCECD][ENG-AI][TruMisery][redump] (Track 02).bin"

Then copy/rename the unchanged tracks and add the matching CUE as above.

PLAYING AND TROUBLESHOOTING
--------------------------
Keep all 23 BINs with the CUE and open the CUE, not an individual BIN.
Use an emulator or hardware configuration capable of running the original
Japanese PC Engine CD game.

Boot fresh after patching. Emulator save states contain executable code,
graphics, and RAM from the build that created them and may restore old text
or artifacts. Use a fresh new game when checking the bonus code.

If patching fails, check the original Track 02 size and SHA-1 above. If the
game cannot find tracks or audio is missing, check the CUE filenames and
that every unchanged original track was copied. Preserve the CUE's modes,
indices, and pregaps.

VERIFICATION
------------
All 23 source tracks were verified against Redump sizes, CRC32, MD5, and
SHA-1 values. This release changes 225 data sectors on Track 02. All changed
sectors pass Mode 1 EDC and P/Q ECC checks. The supplied xdelta patch was
applied to the original Redump Track 02 and reproduced the release output
byte for byte. Audio tracks and Track 23 remain identical to Redump.

Development checks included selected Geargrafx checks of the ending routes,
title code and normal starts, menu navigation, and representative Sound Test
functions. These checks do not constitute a complete playthrough or a claim
of full hardware compatibility. No new emulator or hardware playtest was
performed for this packaged Redump release.

PATCH AND OUTPUT HASHES
-----------------------
Patch size: 175,089 bytes
Patch SHA256:
690bc185f2a75482ea86890b3c82ed74b352ce07d6e9919a4173d5191be6ba06

Patched Track 02 size: 5,748,288 bytes
Patched Track 02 MD5:
ee80e8ffc1b34e53158c8febffbd344d
Patched Track 02 SHA-1:
ae73c0e31bd2211ba82af9ffefb04a5bbb006add
Patched Track 02 SHA256:
c3b7256def37ae0638144582a64cc3f9d0da7e70fa4c756b64aec1772c3554e6

ORIGINAL REDUMP TRACK CHECKLIST
------------------------------
These are ORIGINAL Japanese source hashes. After patching, only Track 02
uses the translated hash above; every other track still uses this table.

Track  Size (bytes)  SHA-1
01        6355104    5302e485643e3123bd5a076f115784b296aa5004
02        5748288    e765643133ef17ee6fb26f0bd19b79cdf8de9200
03        4802784    e6e58b5bb100cc47a086fa85d71c39a65df1aaea
04        3234000    d3e5a9f8b60017bc07662d4daf1790715572786c
05        1853376    da7809a506c3e2938b56edc00c90694bf0065767
06       21828912    46e7eee4b25265a046302087bcd533113c652772
07        8050896    7f4999b3cffdb362495474059a82dab0d4c1f523
08       36733536    5e89c20da385484363d6b77cbdb37dda8a6dd745
09       23642304    967840554ce96bb68c7136b40f704e476fad30e8
10       16428720    5845b5adce695065f356b057de9fcab56a50fbca
11       33005616    e0de2cba29ac93a32936287ba9a562cc4422fd37
12       28315728    7c8853da8a4492dd3937f5c1eca7e26eb5f260f1
13       34922496    6e30339c51a71f706ed691e958caa6a2b6bdf3f7
14       31627344    849ae313c7b334cd643ee12b223046c805b3fbc5
15        8979936    5e13f79390c795f5bd053ff922727c17dcc5ff5a
16        6293952    de8bc95f210604a9ed2214c2893f697c59caaba8
17       28670880    d667eb2bfcf4dc16a8619119c9d9e3eb3e768047
18       21090384    47f5001c98ca1967677872b222efad3a71a336ec
19        5927040    4a7925e119c4c3c339c9e371b5bdcd1b0f75db3b
20       29752800    d9d76e9e2bfc883b4381cceba9602a5483c7587f
21        8645952    a0c43137ac8e4375dfea70eb445dda8d1fef1e33
22       26619936    eafb0f9db20e5adbfc7eb663da6301e4e1f3bea4
23        5397840    96f3ed541a9c33312fef9038e30a7b5b1238c15e

CREDITS
-------
TruMisery - translation project, editing, graphics direction, review,
            and testing.
AI assistance - translation support, programming, analysis, and asset work.
Original game staff - original game, artwork, music, and Japanese voices.
Redump contributors - disc identification and preservation checksums.

This is an unofficial fan translation. The patch requires the original
Japanese game files and does not contain a complete playable game.
