# EurKEY Ultra—Multilingual European and Symbolic Keyboard Layout

EurKEY Ultra is a keyboard layout based off of EurKEY 1.3 beta by Steffen Brüntjen. At first, I was just looking for a keyboard to type German characters ä, ü, ö, and ß without having to use the Windows emoji picker menu. I tried the US international keyboard layout built into Windows and hated it because of the way it handles the quote and grave keys. Then I found EurKEY, which is a lot better because it doesn't get in your way and also has access to more symbols than the standard US international keyboard. EurKEY is a great layout, but I felt like there were some mistakes and missed opportunities in it. This got me interested in the idea of multilingual typing and led me to a quest to find the ultimate European keyboard. There's also Eumak, but that's only available for Linux. I saw there wasn't another keyboard out there that could type most European languages that use Latin-based characters, so I decided to try making one, which took a few days. I kept adding more math symbols and miscellaneous symbols over the course of a few weeks. Keep in mind that I don't publish a separate version every time I make a small change. For some of the bigger changes I made, I released them as separate "old" versions. If you want to make sure you have the latest version, check the date of the release. I used KbdEdit Premium to make this layout and used the MSKLC file for EurKEY 1.3 beta available on the EurKEY Keyboard Layouts - Clone Project on GitHub as a base. EurKEY Ultra was made for fun as an experiment.

# Layout Enhancements and Changes

EurKEY Ultra adds many characters that are missing in EurKEY. Some of these include:

* Full Greek keyboard, with tonos, dialytika, and combined accents
* Hungarian double acute letters ő and ű
* Breve accent, such as ă and ŭ
* Romanian comma-below support for ț and ș
* Turkish dotless ı and capital dotted İ
* Easier access to letters with ogonek, like ą and ę, for Polish and Lithuanian
* Letters like ř and š for Czech and Slovak can be typed using fewer keystrokes than EurKEY
* Type over 300 symbols, including over 150 math symbols like ∃ ℤ ∇ ∀, over 60 arrows like ⇗ ⟼ ⇚ ↫, and over 150 other symbols like ¤ ₿ † ‡ and ⛈ ⛔ ❄ ☯ ⚡ (some of these might render as emojis, depending on the font/app)

I tested this keyboard layout with typing tests on several websites, like keyhero.com, 10fastfingers.com, free-online-writing.com, and quicktypingtest.com. I tried typing words and passages in Spanish, French, German, Norwegian, Icelandic, Hungarian, Polish, Slovak, Czech, Latvian, Lithuanian, Romanian, Turkish, Greek, and many others. Esperanto is also fully supported. For basically all the Latin-based scripts available on those typing test sites, I tested them several times each. I was able to get about 30–40 WPM for pretty much every language I tested (except Greek, because I'm not as familiar with the layout). You could probably do it much faster with practice. The layout also supports many math symbols that are in LaTeX and Amssymb.

Some things are the same as on EurKEY, but there are many differences. I didn't keep track of every change I made, but here are some of them:

* More dead keys, different dead key positions
* Restored the functionality of ð (eth) to `AltGr` + `D` for Icelandic support. The letter đ can still be typed using the macron dead key
* Moved æ back to `AltGr` + `Z` to match the US international keyboard layout
* Made `AltGr` + `Shift` + `E` the Euro sign, and `AltGr` + `Shift` + `Y` the Yen sign
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

### Without `Shift` Key

<img src="screenshots/layout/math.png" width="800">

### With `Shift` Key

<img src="screenshots/layout/math-shift.png" width="800">

### With `AltGr` Key

<img src="screenshots/layout/math-altgr.png" width="800">

### With `AltGr` + `Shift` Keys

<img src="screenshots/layout/math-altgr-shift.png" width="800">

## Misc. Symbols—`AltGr` + `\`

### Without `Shift` Key

<img src="screenshots/layout/misc-symbols.png" width="800">

### With `Shift` Key

<img src="screenshots/layout/misc-symbols-shift.png" width="800">

### With `AltGr` Key

<img src="screenshots/layout/misc-symbols-altgr.png" width="800">

### With `AltGr` + `Shift` Keys

<img src="screenshots/layout/misc-symbols-altgr-shift.png" width="800">

# How to Use This Keyboard Layout

This keyboard layout uses **dead keys** to type symbols and accented letters. The layout is divided into different layers. If you aren't trying to type special characters, the keyboard will just work like a regular US QWERTY keyboard, except for the `Caps Lock` key, which switches to Greek letters. The other layers are accessed with the `AltGr` key. Accented letters are typed with `AltGr` + number keys, the math layer is on `AltGr` + `M`, and the miscellaneous symbols layer is on `AltGr` + `\`. To see which symbols you can type, and how to type them, look at the screenshots. For example, to type the ∈ symbol on the math layer, press `AltGr` + `M` together. Then let go of both keys, and press `K`. To type ⋈, you would press `AltGr` + `M`, then `AltGr` + `W`. If a key combination has `AltGr` twice in it, you could keep holding `AltGr`. In that case, you would press `AltGr` + `M`, then let go of `M` but keep holding `AltGr`, then press `W`. The math and miscellaneous symbols are laid out so that the most common symbols are usually typed with or without `Shift`, and rarer symbols are on the `AltGr` and `AltGr` + `Shift` sublayers. Most of the symbols either resemble the shape of the letter used to type them, or the symbol's name starts with the letter. For example, `AltGr` + `M`, `Shift` + `S` → ∫ (integral sign, shaped like an S), or `AltGr` + `M`, `P` → ∂ (partial derivative symbol, name starts with a P).

## Visual Mnemonic for Accents

<img src="screenshots/layout/mnemonic.png" width="500">

Many western European languages can be typed without using any dead keys, except for circumflex letters like â ô for French. You can just use `AltGr` + QWERTY letters to type letters that are commonly used in many languages, such as `AltGr` + `A` → ä, `AltGr` + `G` → é. For other languages, this keyboard layout uses a system of ten keys to type accented characters. The number keys are used becase they are in the same place on most keyboard layouts. The key to the left of `1` is also used, which is sometimes a `0`, but usually something else, depending on the region. In order to understand which accents correspond to which number, you have to look at the shape of that number. Here's how to visualize the dead-key system:

* `AltGr` + [key left of 1] → Grave¹. No visual mnemonic. Just remember it's next to the `1` key, which is used for acute. Examples: è, ì, à
* `AltGr` + `1` → Acute¹. The top of the number 1 looks like an acute accent. Examples: ó, í, ú, also ł, also έ, ά, ώ (Greek tonos)
* `AltGr` + `2` → Tilde. The number 2, rotated sideways, looks like a tilde symbol. Examples: ã, õ, also ΰ, ΐ (Greek combined diacritics)
* `AltGr` + `3` → Double acute accent for Hungarian. The numeral 3 has two "hooks" that look like a double acute when the number is turned sideways. Examples: ő, ű
* `AltGr` + `4` → Circumflex. The top of the number 4 looks like a circumflex. Examples: ô, â, î
* `AltGr` + `5` → Caron and breve. The bottom curve of the number 5 looks like a caron or breve (both are combined into the same key). Examples: š, ž, ř (caron) and ă, ŭ, ğ (breve)
* `AltGr` + `6` → Ogonek. The number 6 looks like an ogonek. Examples: ę, ą, ų
* `AltGr` + `7` → Macron. The line on the top of the 7 represents a macron. Examples: ō, ī, ā, also ħ, ŧ, also ‐, –, — (hyphen, en dash, em dash)
* `AltGr` + `8` → Dot and ring above. The top loop of the 8 represents a dot or ring (both are combined into the same key). Examples: ż, ė, ů
* `AltGr` + `9` → Cedilla. The number 9 looks like a cedilla. Examples: ş, ç, ķ, ņ², also ʒ
* `AltGr` + `Shift` + `1` → Diaeresis (umlaut)¹. Follows the same convention as the US international layout by being paired with the acute key. Examples: ä, ü, ë, also ϋ, ϊ (Greek dialytica)
* `AltGr` + `Shift` + `9` → Comma below for Romanian. The number 9 also visually looks like a comma. Examples: ș, ț, also ŋ

Notes:

¹There are quicker shortcut keys to access common acute, grave, and double-dot letters, such as `AltGr` + `A` for ä or `AltGr` + `G` for é (on a QWERTY layout).

²Some letters, like ķ and ņ, actually have commas below, but Unicode mislabels them as having cedillas. They are still included in the cedilla category to follow this naming convention.

# The Location of the Misc. Symbols Key

Due to differences between ISO and ANSI layouts, the location of the misc. symbols dead key will be different on different keyboards. Press `AltGr` together with the highlighted key to get to these symbols. Here's a visual representation of where the key is on different boards:

## ANSI
<img src="screenshots/layout/misc-key-ansi.png" width="500">

## ISO
<img src="screenshots/layout/misc-key-iso.png" width="500">

## ISO Variant
<img src="screenshots/layout/misc-key-iso-variant.png" width="500">

# Limitations of EurKEY Ultra

* The macOS version of EurKEY Ultra is untested. There's a .keylayout file for Mac, but I can't guarantee it works because I don't have a Mac to test anything. If the .keylayout file generated by KbdEdit doesn't work, then a version will probably have to be remade with a tool like Ukelele
* This keyboard layout won't fit everyone's preferences. Some people won't like the placement of the keys, or some people won't like using dead keys to type accents, for example. A keyboard is a tool, so you should use whatever system works best for you
* The keyboard layout is designed with US QWERTY layout in mind. If you're not using a US QWERTY keyboard, this layout will still work, but note that some letters and symbols won't visually make sense to what's printed on your keycaps. All of the accents are typed using the number keys, at least, which are the same on most keyboards
* Although I tried to include and test every European language I could find that uses a Latin script, I probably missed some characters somewhere. I can't guarantee support for every minority language, but most European languages should be covered, as well as all official EU languages except Bulgarian. Languages that use cyrillic characters won't work in general on this layout
* The Caps Lock key is repurposed to type Greek. You can still type in all caps using the Shift key, but if you prefer using Caps Lock, then you probably won't like this layout
