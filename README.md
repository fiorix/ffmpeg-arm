# ffmpeg for arm (Raspberry Pi)

This is a Dockerfile that builds an image containg [ffmpeg](https://www.ffmpeg.org)
with alsa, libaac+ and x264 for ARM processors.

It was created with instructions from https://trac.ffmpeg.org/wiki/CompilationGuide/RaspberryPi.

Binaries and libs are available under `/opt/ffmpeg` ready to be copied to
the target device.
