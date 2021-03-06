**This is an archived resource.** The repo will remain available but the resource will no longer be maintained or updated. Some or all parts of the resource may no longer work. To see our latest resources, please visit [raspberrypi.org](http://www.raspberrypi.org).

# Babbage Lights & Sounds

A re-imagining of the classic Simon game, challenging you to remember and repeat the pattern of lights and sounds!

## Requirements

You'll need `pd` installed, that's what we use to create lovely tones to accompany your lights. You should also plug in a pair of headphones or speakers.

```bash
sudo apt-get install pd
```

To download the Python files, run the following commands:

```bash
wget http://goo.gl/4Bf0MJ -O babbage.zip
unzip babbage.zip
```

## Giving it a go!

The lights and sounds game will play a variety of tunes, and challenge you to repeat them by pressing the buttons next to the corresponding lights.

Get it wrong and you lose a life, get it right and you progress to the next tune!

Are you a musical ninja, or a tone-deaf sea-dog, give it a try and find out!

```bash
cd babbage-lights-n-sounds-master
sudo python blas.py
```

## Making it your own

We've tried to comment everything so you can make changes. You'll probably want to start with changing the list of tunes.

A tune is a list of tuples containing the musical note (from the notes list) and the duration (in seconds). Here's an example:

```python
[('a',0.5),('a',0.5),('b',0.5),('c',0.5)]
```

## Licence

Unless otherwise specified, everything in this repository is covered by the following licence:

[![Creative Commons License](http://i.creativecommons.org/l/by-sa/4.0/88x31.png)](http://creativecommons.org/licenses/by-sa/4.0/)

***Babbage Lights & Sounds*** by [Pimoroni](http://pimoroni.com) and the [Raspberry Pi Foundation](http://www.raspberrypi.org) is licenced under a [Creative Commons Attribution 4.0 International License](http://creativecommons.org/licenses/by-sa/4.0/).

Based on a work at https://github.com/raspberrypilearning/babbage-lights-n-sounds
