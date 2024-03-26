# Dvorak AltGr International Extended
![layout diagram](image.png)

This is a Windows port of the Linux/Unix implementation of Dvorak International, with dead keys moved to the AltGr and AltGr+Shift modifier states.<br>

Liberties taken:<br>
  * Changes from core layout:
    - Superscript 1 (`¹`) has swapped positions with inverted exclamation mark (`¡`).
    - Dead hook has swapped positions with inverted question mark (`¿`).
    - Dead cedilla and dead caron have been moved to <kbd>AltGr</kbd> + <kbd>,<</kbd>, replacing `Ç`/`ç`.
      - <kbd>AltGr</kbd> + <kbd>Shift</kbd> + <kbd>5%</kbd> produces Permille sign (`‰`).
      - <kbd>AltGr</kbd> + <kbd>Shift</kbd> + <kbd>.<</kbd> produces a duplicate dead circumflex.
    - The generic currency symbol (`¤`) has swapped positions with the Pound Sterling sign (`£`).
    - <kbd>AltGr</kbd> + <kbd>Shift</kbd> + <kbd>S</kbd> produces Capital Sharp S (`ẞ`).
      - Section Sign (`§`) has been moved to <kbd>AltGr</kbd> + <kbd>Shift</kbd> + <kbd>;:</kbd>.
    - `“`Double curly quotaton marks`”` have been replaced with `‹`single angle quotation marks`›`.
      - Curly quotes remain accessible via dead acute/diaeresis + `<`/`>`.
  * Various dead key QOL optimizations:
    - Additional diacritics available from existing dead keys:
      - Dead macron also functions as dead belowmacron.
      - Dead ogonek also functions as dead belowcomma.
      - Many mathematical symbols are able to be produced via dead key sequences.
    - Changes to output from XOrg:
      - Dead acute + `Ó`/`ó`/`Ú`/`ú` produces `Ő`/`ő`/`Ű`/`ű`.
      - Dead abovedot + `U`/`u` produces `Ů`/`ů`.
      - Dead hook + `N`/`n` produces Eng (`Ŋ`/`ŋ`).
      - Dead hook + <kbd>AltGr</kbd> + `Y`/`y` produces `Ƴ`/`ƴ`.
      - Dead tilde + `=` produces `≅`.
      - Dead stroke + `U`/`u` produces `Ꞹ`/`ꞹ`.

## Building
Compilation requires KbdEdit which can be obtained [here](http://www.kbdedit.com/).
