# Lumin8 Theme for EmulationStation

Lumin8 is an EmulationStation version 4 compatible theme, making it ideal for low-powered systems using RetroPie or ArkOS, as well as the PlayStation Classic.

Do you love the luminous theme, but have trouble discerning a system based on its logo or controller? Have you wondered whether `Game Gear` should be sorted with the `Gs`, for `Game`, or the `Ss`, for `Sega`? This theme was designed to address those issues. Instead of displaying the system's controller, it instead displays the system's fullname from your `es_settings.cfg`. Only "Released", "Developer", and "Publisher" meta data is utilized.

![System Select](art/README/System%20Select.png) ![Detailed Game List](art/README/Detailed%20Game%20List.png)

Based on ['luminous' - 11-03-2016 by Rookervik](https://github.com/ehettervik/es-theme-luminous).

## Why "8"?

Eight is the number of bits in a character. For systems, Lumin8 uses characters above the system logos.

## Configuration

### Change Font

Copy your font to /etc/emulationstation/themes/carbon8/art folder. For the gamelist text, rename the original font "Cabin-Bold.ttf" to "Cabin-Bold.ttf.bak" and then rename your font to "Cabin-Bold.ttf". For the system text, rename the original font "SNES.ttf" to "SNES.ttf.bak" and then rename your font to "SNES.ttf".

### Change Color

To change the colors open colors.xml with a text editor. Find all occurances of "04e9f7" and replace them with your chosen color.

### Change Sound

To change the sound effect, replace /art/scroll.wav with what ever WAV file you would like.
