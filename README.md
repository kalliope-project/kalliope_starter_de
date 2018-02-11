# kalliope starter config de
[![Gitter](https://badges.gitter.im/gitterHQ/gitter.svg)](https://gitter.im/kalliope-project/Lobby)

This is an out of the box working configuration for german kalliope user


# requirements
/!\ You need to have the [Kalliope Core](https://github.com/kalliope-project/kalliope) installed before cloning this starter kit.

This starter kit has been tested with Kalliope v0.5.0

# How to use

Use:
 ```bash
git clone https://github.com/kalliope-project/kalliope_starter_de.git
cd kalliope_starter_de
kalliope start
```

You can change the trigger word from "Kalliope" to "Computer" by
going to 'settings.yml' and changing the following lines:
'''
triggers:
  - snowboy:
      pmdl_file: "trigger/Computer.pmdl"
'''
If you have problems with Kalliope recognizing your keyword, try to change it to "Computer" or create
your own model and help to improve [kalliope-DE](https://snowboy.kitt.ai/hotword/4324).
