# EurKEY Ultra—Multilingual European and Symbolic Keyboard Layout

EurKEY Ultra is a keyboard layout based off of EurKEY 1.3 beta by Steffen Brüntjen. At first, I was just looking for a keyboard to type German characters ä, ü, ö, and ß without having to use the Windows emoji picker menu. I tried the US international keyboard layout built into Windows and hated it because of the way it handles the quote and grave keys. Then I found EurKEY, which is a lot better because it doesn't get in your way and also has access to more symbols than the standard US international keyboard. EurKEY is a great layout, but I felt like there were some mistakes and missed opportunities in it. This got me interested in the idea of multilingual typing and led me to a quest to find the ultimate European keyboard. There's also Eumak, but that's only available for Linux. I couldn't find anything else that could type most European languages that use Latin-based characters (but later did find some; see the "Alternatives to EurKEY Ultra section at the end), so I decided to try making one. The first version took a few days to make, and then I kept adding more letters and other symbols over the course of a few weeks. I used KbdEdit Premium to make this layout and used the MSKLC file for EurKEY 1.3 beta available on the EurKEY Keyboard Layouts - Clone Project on GitHub as a base. EurKEY Ultra was made for fun as an experiment.

Note: I don't publish a separate version every time I make a small change. For some of the bigger changes I made, I released them as separate "old" versions. These old versions are included for archival and for curiosity. If you want to make sure you have the latest version, check the date of the release.

# Layout Enhancements and Changes

EurKEY Ultra adds many characters that are missing in EurKEY. Some of these include:

* Full Greek keyboard, with tonos, dialytika, and combined accents
* Hungarian double acute letters ő and ű
* Breve accent, such as ă and ŭ
* Romanian comma-below support for ț and ș
* Turkish dotless ı and capital dotted İ
* Easier access to letters with ogonek, like ą and ę, for Polish and Lithuanian
* Letters like ř and š for Czech and Slovak can be typed using fewer keystrokes than EurKEY
* Support for minority languages like Sámi, Welsh, Romani, Sorbian, Resian, Livonian, and many others
* Esperanto is also fully supported
* Type over 300 symbols, including over 150 math symbols like ∃ ℤ ∇ ∀, over 60 arrows like ⇗ ⟼ ⇚ ↫, and over 150 other symbols like ¤ ₿ † ‡ and ⛈ ⛔ ❄ ☯ ⚡ (some of these might render as emojis, depending on the font/app)

I tested this keyboard layout with typing tests on several websites, like monkeytype.com, keyhero.com, 10fastfingers.com, free-online-writing.com, and quicktypingtest.com. I tried typing words and passages in Spanish, French, German, Norwegian, Icelandic, Hungarian, Polish, Slovak, Czech, Latvian, Lithuanian, Romanian, Turkish, Greek, and many others. For basically all the Latin-based European languages available on those typing test sites, I tested them several times each. I was able to get about 30–40 WPM for pretty much every language I tested (except Greek, where I can only get about 25 WPM because I'm not as familiar with that layout). You could probably do it much faster with practice. The layout also supports many math symbols that are in LaTeX and Amssymb.

Some things are the same as on EurKEY, but there are many differences. I didn't keep track of every change I made, but here are some of them:

* More dead keys, different dead key positions
* Restored the functionality of ð (eth) to `AltGr` + `D` for Icelandic support. The letter đ can still be typed using the macron dead key
* Moved æ back to `AltGr` + `Z` to match the US international keyboard layout
* Made `AltGr` + `Shift` + `E` the Euro sign, and `AltGr` + `Shift` + `C` the cent sign
* The º and ª for Spanish ordinals are typed using `AltGr` + `Shift` + `2` and `AltGr` + `Shift` + `3`, instead of `AltGr` + `2` and `AltGr` + `3`
* Moved the German lower-99 quotation mark „ symbol to `AltGr` + `0` instead of `AltGr` + `8` because of the new dead key on `AltGr` + `8`. The left and right double-quote keys are also in different positions
* Rearranged a few Greek symbols and added final sigma ς to follow the standard Greek layout
* Rearranged some of the math symbols that were already in EurKEY. The math layer is also now on `AltGr` + `M` instead of `AltGr` + `Shift` + `M` (one key less)
* Subscript and superscript numbers were moved to the misc. symbols layer
* Fractions are typed by holding down `AltGr` in the misc. symbols layer. For example, `AltGr` + `\` + `2` → ½ (or `AltGr` + `\`, `AltGr` + `2`)

# Installation

On Windows, a standalone installation exe is included if you just want to install and use the layout. A .kbe file is included that you can use to import the layout into KbdEdit if you want to make your own customizations. On Mac, follow the "Installing exported layouts on a Mac" directions on http://www.kbdedit.com/manual/file_export_mac_keylayout_file.html See the disclaimer below about Mac support though.

# Layout

## Language Characters

### `AltGr` Layer

<img src="screenshots/layout/altgr.png" width="800">

### `AltGr` + `Shift` Layer

<img src="screenshots/layout/altgr-shift.png" width="800">

## Greek Keyboard—`Caps Lock`

<img src="screenshots/layout/greek.png" width="800">

## Math Symbols—`AltGr` + `M`

### No Modifier

<img src="screenshots/layout/math.png" width="800">

### With `Shift` Key

<img src="screenshots/layout/math-shift.png" width="800">

### With `AltGr` Key

<img src="screenshots/layout/math-altgr.png" width="800">

### With `AltGr` + `Shift` Keys

<img src="screenshots/layout/math-altgr-shift.png" width="800">

## Misc. Symbols—`AltGr` + `\`

### No Modifier

<img src="screenshots/layout/misc-symbols.png" width="800">

### With `Shift` Key

<img src="screenshots/layout/misc-symbols-shift.png" width="800">

### With `AltGr` Key

<img src="screenshots/layout/misc-symbols-altgr.png" width="800">

### With `AltGr` + `Shift` Keys

<img src="screenshots/layout/misc-symbols-altgr-shift.png" width="800">

# How to Use This Keyboard Layout

This keyboard layout uses **dead keys** to type symbols and accented letters. The layout is divided into layers and sublayers. If you aren't trying to type special characters, the keyboard will just work like a regular US QWERTY keyboard, except for the `Caps Lock` key, which switches to Greek letters. The other layers are accessed with the `AltGr` (right `Alt`) key. The dead keys are highlighted in blue in the screenshots.

Typing symbols involves two steps. First, press `AltGr` + another key to enter one of the main layers (or `AltGr` + `Shift` + a number for a few accents). After that, press a combination of one, two, or three keys to type the symbol you want. To type an accented letter, just press the letter that takes the accent after the dead key sequence. Accented letters are typed with `AltGr` + number keys, the math layer is on `AltGr` + `M`, and the miscellaneous symbols layer is on `AltGr` + `\`. In these instructions, a **+** (plus sign) means you press two keys at the same time, and a **,** (comma) means let go of all the keys. For example, a key sequence like `AltGr` + `2`, `Shift` + `O` → Õ should be interpreted as "press `AltGr` and `2` together, let go of both keys, and then press `Shift` and `O` together." The capital version of any letter can be made by adding `Shift` before the last key, such as `AltGr` + `Shift` + `5`, `Shift` + `A` → Ă

The math and misc. symbols layers each have four sublayers: the base layer (no modifier), `Shift`, `AltGr`, and `Shift` + `AltGr`. To see which symbols you can type, and how to type them, follow the screenshots. For example, to type the ∈ symbol on the math layer, press `AltGr` + `M` together. Then let go of both keys, and press `K`. To type ⋈, you would press `AltGr` + `M`, then `AltGr` + `W`. To type ⌘ on the misc. symbols layer, press `AltGr` + `\`, and then `AltGr` + `Shift` + `X`. If a key combination has `AltGr` twice in it, you could keep holding `AltGr`. In that case, for ⋈ you could press `AltGr` + `M`, then let go of `M` but keep holding `AltGr`, then press `W`, and for ⌘ you could press `AltGr` + `\`, then let go of only `\` and press `Shift` + `X`. 

For math and miscellaneous symbols, most of the symbols either resemble the shape of the letter used to type them, or the symbol's name starts with the last letter used to type it. For example, `AltGr` + `M`, `Shift` + `S` → ∫ (integral sign, shaped like an S), or `AltGr` + `M`, `P` → ∂ (partial derivative symbol, name starts with a P). Understanding the symbol placement is like understanding the dynamics of high school culture. In high school, everyone belongs to a sort of "niche." There are jocks, nerds, goths, cheerleaders, and so on. In this keyboard layout, similar symbols go together too, either by being next to each other, being on the same sublayer, or being on the same key. For example, the set-relation symbols are on `G`, `H`, and `B`, and the weather symbols are mostly capital letters that represent the start of the name, like `Shift` + `S` for ☀ and `Shift` + `C` for ☁. For math symbols, the most common ones are usually typed without `Shift` or `AltGr` after the dead key, like ∃ ∞ ∧ ∘ ∅ ∛. These are the popular symbols that everyone is asking out to the big dance ☺. `Shift` is also used to type some common symbols, like ∀ ℤ ∫ ⊕ and some rarer symbols like ∮ ℘ ⊻ ∬. Most of the rarest symbols are on the `AltGr` and `AltGr` + `Shift` sublayers, like ⊞ ⋓ ⨖.

## Visual Mnemonic for Accents

<img src="screenshots/layout/mnemonic.png" width="500">

Many letters used in western European languages can be typed without using any dead keys, except for circumflex letters like ê â ô for French and tilde letters ã õ for Portuguese. You can just use `AltGr` + QWERTY letters to type characters that are commonly used in many languages, such as `AltGr` + `A` → ä, `AltGr` + `G` → é. For other languages, this keyboard layout uses a system of ten keys to type accented characters. The number keys are used becase they are in the same place on most keyboard layouts. The key to the left of `1` is also used, which is sometimes a `0`, but usually something else, depending on the region. In order to understand which accents correspond to which number, you have to look at the shape of that number. Here's how to visualize the dead-key system:

* `AltGr` + [key left of 1] → Grave. No visual mnemonic. Just remember it's next to the `1` key, which is used for acute. Example letters: è, ì, à
* `AltGr` + `1` → Acute. The top of the number 1 looks like an acute accent. Example letters: ó, í, ú, also έ, ά, ώ (Greek tonos)
* `AltGr` + `2` → Tilde. The number 2, rotated sideways, looks like a tilde symbol. Example letters: ã, õ, also ΰ, ΐ (Greek combined diacritics)
* `AltGr` + `3` → Double acute. The numeral 3 has two "hooks" that look like a double acute when the number is turned sideways. Example letters: ő, ű
* `AltGr` + `4` → Circumflex. The top of the number 4 looks like a circumflex. Example letters: ô, â, î
* `AltGr` + `5` → Caron. The bottom curve of the number 5 represents a caron. Example letters: š, ž, ř
* `AltGr` + `6` → Ogonek. The number 6 looks like an ogonek. Example letters: ę, ą, ų
* `AltGr` + `7` → Macron. The line on the top of the 7 represents a macron. Example letters: ō, ī, ā, also ł, đ, ħ, ŧ, ǥ
* `AltGr` + `8` → Dot and ring above. The top loop of the 8 represents a dot or ring (both are combined into the same key). Example letters: ż, ė, ů
* `AltGr` + `9` → Comma below. The number 9 looks like a comma. Example letters: ș, ț, ķ*
* `AltGr` + `Shift` + `1` → Diaeresis (umlaut). Follows the same convention as the US international layout by being paired with the acute key. Example letters: ä, ü, ë, also ϋ, ϊ (Greek dialytica)
* `AltGr` + `Shift` + `5` → Breve. The bottom curve of the number 5 also looks like a breve. Example letters: ă, ŭ, ğ
* `AltGr` + `Shift` + `9` → Cedilla. The number 9 also looks like a cedilla. Example letters: ş, ç, also ʒ, ŋ

Note:

*Some letters, like ķ, should be rendered with a comma below, but Unicode labels them as having cedillas. Despite Unicode's incorrect labeling, these letters are included in the dead key for comma below to match their actual function.

A few letters used in Livonian have two accent marks. All of them have a macron on top. To type them, first use the dead key for the bottom accent, then use `AltGr` + the base letter to add the macron on top. These are the key sequences:

* `AltGr` + `Shift` + `1`, `AltGr` + `A` → ǟ
* `AltGr` + `2`, `AltGr` + `O` → ȭ
* `AltGr` + `8`, `AltGr` + `O` → ȱ

There are also several dashes and spaces included as part of the macron dead key:

* `AltGr` + `7`, `1` → ‐ (hyphen)
* `AltGr` + `7`, `2` → – (en dash)
* `AltGr` + `7`, `3` → — (em dash)
* `AltGr` + `7`, `9` → no-break space
* `AltGr` + `7`, `0` → narrow no-break space
* `AltGr` + `7`, `Shift` + `9` → thin space
* `AltGr` + `7`, `Shift` + `0` → zero-width space
* `AltGr` + `7`, `AltGr` + `9` → hair space
* `AltGr` + `7`, `AltGr` + `0` → word joiner
* `AltGr` + `7`, `-` → ‑ (non-breaking hyphen)
* `AltGr` + `7`, `Shift` + `-` → soft hyphen
* `AltGr` + `7`, `=` → ‒ (figure dash)
* `AltGr` + `7`, `Shift` + `=` → figure space

The ring/dot above dead key also has a few modifier letters:

* `AltGr` + `8`, `'` → ʼ modifier letter apostrophe (Võro)
* `AltGr` + `8`, `Shift` + `'` → ʹ modifier letter prime (soft sign in ISO 9 Cyrillic transliteration, Skolt Sámi)
* `AltGr` + `8`, `AltGr` + `'` → ʺ modifier letter double prime (hard sign in ISO 9 Cyrillic transliteration)
* `AltGr` + `8`, `Shift` + `;` → ꞉ modifier letter colon (files names)
* `AltGr` + `8`, `/` → ⧸ big solidus (file names, song titles)

# The Location of the Misc. Symbols Key

Due to differences between ISO and ANSI layouts, the location of the misc. symbols dead key will be different on different keyboards. Press `AltGr` together with the highlighted key to get to these symbols. Here's a visual representation of where the key is on different boards:

## ANSI
<img src="screenshots/layout/misc-key-ansi.png" width="500">

## ISO
<img src="screenshots/layout/misc-key-iso.png" width="500">

## ISO Variant
<img src="screenshots/layout/misc-key-iso-variant.png" width="500">

# Limitations of EurKEY Ultra

* An `AltGr` (right `Alt`) key is required to use the layout, which some keyboards may not have. If your keyboard doesn't have one, you can use KeyTweak or similar to re-assign another key that you don't use for anything to be `AltGr`
* The macOS version of EurKEY Ultra is untested. There's a .keylayout file for Mac, but I can't guarantee it works because I don't have a Mac to test anything. If the .keylayout file generated by KbdEdit doesn't work, then a version will probably have to be remade with a tool like Ukelele
* This keyboard layout won't fit everyone's preferences. Some people won't like the placement of the keys, or some people won't like using dead keys to type accents, for example. A keyboard is a tool, so you should use whatever system works best for you
* The keyboard layout is designed with US QWERTY layout in mind. If you're not using a US QWERTY keyboard, this layout will still work, but note that some letters and symbols won't visually make sense to what's printed on your keycaps. All of the accents are typed using the number keys, at least, which are the same on most keyboards
* Although I tried to include and test every European language I could find that uses a Latin script, I probably missed some characters somewhere. I can't guarantee support for every minority language, but most European languages should be covered, as well as all official EU languages except Bulgarian. Languages that use Cyrillic characters won't work in general on this layout. If I missed another letter, let me know, and I'll add it if I can
* The Caps Lock key is repurposed to type Greek. You can still type in all caps using the Shift key, but if you prefer using Caps Lock, then you probably won't like this layout

# Alternatives to EurKEY Ultra

If you decide EurKEY Ultra isn't for you, here are some other alternatives worth looking at. These support multilingual European typing, math symbols, or both:

## US English keyboard with all Latin accents using chained dead keys

For Windows. An example layout from KbdEdit's website. Has 26 accents and supports stacking diacritics.

https://www.kbdedit.com/manual/ex18_latin_all_accents_chained_dead.html

## US International Scientific Keyboard Layout

For Windows. Includes many commonly used diacritics and tons of math symbols.

https://github.com/BelugaHaechi/US-International-Scientific-Keyboard

## kbdLayout-Mac

macOS only, but has 26 accents, with the ability to stack diacritics, and tons of math symbols. Has both Russian and English versions.

https://github.com/eugenesvk/kbdLayout-Mac

## Math Keyboard layout for QWERTY keyboards on Windows

For Windows. Can type many common math symbols.

https://www.jkorpela.fi/math/kbd.html

## Neo

For Windows, Mac, and Linux. Optimized for German, but supports many languages and math symbols.

https://neo-layout.org/

## BÉPO

For Windows, Mac, and Linux. Optimized for French, but supports all Latin-based EU languages, Greek, and Esperanto.

https://bepo.fr/wiki/Accueil

## Eumak

Linux only, but has broad support for many European languages.

https://eumak.org/

## SmartLayer

Linux only, but has many common accented letters and math symbols.

https://github.com/SmartLayer/SmartLayer?tab=readme-ov-file

## XKB Math-Layout

Linux only. Based on German QWERTZ layout. Supports some common math symbols and Greek letters.

https://github.com/SV-97/Math-Layout
