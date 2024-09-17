# Repaired Starfield Watchy Firmware

This repository contains a repaired version of the Starfield Watchy firmware.

## For you to know
- This is **not** InkWatchy with starfield watchface, it's just the regular shitty default firmware underneath. So nothing works, the code is horrible and I will not help you further with this firmware.
- Consider using [InkWatchy](https://github.com/Szybet/InkWatchy) (or any other modern firmware) for a more "refined" experience compared to the default firmware.
- In the release tab you will find a binary you can flash yourself, just as inkwatchy demo (look up the wiki of inkwatchy for guidance)
- Only use platformio, not arduino IDE.

## Support

If you find this project useful, please consider donating to support further development for all watchy related things! More info in InkWatchy repo

# Links to check out
https://github.com/Szybet/WatchySourcingHub

* * *
* * *
* * *

The rest of this readme is from the original author
# watchy-starfield

starfield watchface for Watchy
* step count
* sunrise/sunset time
* moonphase

![picture](/assets/img.png)

# settings

* To toggle between Dark Mode/Light Mode, push back button
* To toggle between 12-hour/24-hour, push up or down button
* To calculate exact sunrise/sunset time, change `#define LOC 31.00, 121.00, 8` in `Watchy_7_SEG.cpp`, the three data represents latitude, longitude and timezone
* To set the GMT offset for network timing, change `#define GMT_OFFSET_SEC 3600 * 8` in `settings.h`

# Credits

* [moonPhase-esp32](https://github.com/CelliesProjects/moonPhase-esp32) 

  Utilized code from this repository to calculate lunar phases

* [Dusk2Dawn](https://github.com/dmkishi/Dusk2Dawn)

  Utilized code from this repository to calculate sunrise and sunset time
