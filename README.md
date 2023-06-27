# MouthSounds
Python tool for analysing sound files and identifying clicks in speech to allow remediation.

Requirements:
 - Python 3.x
 - Jupyter
 - numpy
 - librosa
 - pandas

Currently this is only set up to use as a Jupyter notebook. It would be failrly straightforward to convert to a .py file. Has only been tested for use with WAV fiels, but I suspect it should also work on any librosa supported filetypes. My only concern is that when tested on a 22050Hz sample rate (rather than Audacity's native 44100Hz) it tended to pick up more false positives.
