---
description: Some less useful launch options, just documented here because why not?
...

# Silly Launch Options

These are launch options that take performance or making the game look bad too far, 
or they're generally not useful for any reasonable user, and are not included in the config.

* **-nops2b** : uses pixel shaders 2.0 instead of 2.0b, makes fog thicker, more frames on really old/bad GPUs, will decrease FPS on others. It also causes some visual artifacts when using transparent viewmodels, like blurry scope and killcam ghosting
* **-nosrgb** : disables sRGB (limits variety of colors), very bright lighting, flatter colors, buggy invisible character and stretched out models, random lines on screen
* **-mat_softwaretl** : forces software vertex processing, might be good for very bad GPUs at very low display resolutions, will greatly decrease FPS otherwise
* **-insert_search_path** : essentially add new custom folders (MOD+GAME search paths) in a comma separated list. Example: `"C:\tf2_custom,C:\my_stuff.vpk"`.
* **-gamestatslogging -gamestatsloggingtofile** : saves game stats which are sent to Steam as a local `tf_gamestats.dat` file.
