# [1.0.4] - 2026-10-07

## Fixed

- Command works again on Sublime Text’s default Python 3.3 plugin host: marker dates use `datetime.now().date()` instead of `astimezone()` on a naive datetime ([#1](https://github.com/dennykorsukewitz/Sublime-QuoteWithMarker/issues/1)).
