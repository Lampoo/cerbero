# Description

See https://github.com/Lampoo/cerbero

# Includes serval hotfixes

* Patching Android MediaCodec in FFMpeg to fix issue seen in avcodec\_send\_packet
  that reports failure when dequeing input/output buffer, ultimately cause stall of
  video decoding

* Enables build of Android MediaCodec and NEON for ARM in FFMpeg by default
