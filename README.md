# leonardo-flasher

A zero-install web page that flashes a compiled Arduino sketch (`.hex`) onto
ATmega32U4 boards — Leonardo, Micro, Pro Micro, and other Caterina-bootloader
(AVR109) boards — straight from the browser over WebSerial. No software to
install; Chrome or Edge on desktop.

Open the page, pick a `.hex`, reset the board into its bootloader, flash.

If a `firmware.hex` sits next to `index.html` it is offered as the default —
useful when the site doubles as a distribution point for a specific sketch.
