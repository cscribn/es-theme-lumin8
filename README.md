# Lumin8 Theme for EmulationStation

Lumin8 is an EmulationStation version 4 compatible theme, making it ideal for any system, even low-powered ones using RetroPie or ArkOS, as well as the PlayStation Classic. It displays the system's fullname from your `es_settings.cfg`. It displays mini-consoles. Only "Released", "Developer", and "Publisher" meta data is utilized.

![System Select](art/README/System%20Select.png) ![Detailed Game List](art/README/Detailed%20Game%20List.png)

Based on ['luminous' - 11-03-2016 by Rookervik](https://github.com/ehettervik/es-theme-luminous).

## Why "8"?

Eight is the number of bits in a character. For systems, Lumin8 uses characters for the system's fullname.

## Configuration

### Change Font

Copy your font to /etc/emulationstation/themes/carbon8/art folder. For the gamelist text, rename the original font "Cabin-Bold.ttf" to "Cabin-Bold.ttf.bak" and then rename your font to "Cabin-Bold.ttf". For the system text, rename the original font "Akrobat-Bold.otf" to "Akrobat-Bold.otf.bak" and then rename your font to "Akrobat-Bold.otf".

### Change Color

To change the colors open colors.xml with a text editor. Find all occurances of "04e9f7" and replace them with your chosen color.

### Change Sound

To change the sound effect, replace /art/scroll.wav with what ever WAV file you would like.
