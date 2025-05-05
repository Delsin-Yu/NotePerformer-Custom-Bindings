# Custom Bindings for Note Performer Playback Engine 5

This repo contains a set of custom bindings created for the [NPPE 5](https://www.noteperformer.com/?page=playback_engines_overview&anchor=playback_engines).

While these bindings are released with an MIT license, you must obtain a valid copy of the appropriate dependency sound libraries and their corresponding sound host.

## Table of Contents

|        Sound Library        |Binding Version|Mapped Instrument(s)|Dependencies|Download Link|Known Issue(s)|
|-|:-:|:-:|:-:|:-:|:-|
|![avatar](./Bindings/Studio%20Drummer/poster_studio_drummer.png)|`0.1 (in development)`|`Garage Kit`<br/>`Session Kit`<br/>`Stadium Kit`|`Kontakt 7 or 8`<br/>`Studio Drummer 1.4.1`|[Studio Drummer 0.1.zip](./Bindings/Studio%20Drummer/Studio%20Drummer%200.1.zip)|1. You need to load `Cine Series / Drum Kit` first and switch to `Studio Drumer / *` for Noteperformer to register the instrument correctly.<br/>2. All notes have auto-mute, which means a 16th-note-long Crash Cymbal will sound exactly 16th-note-long.|
