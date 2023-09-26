# FFmpeg for Unity

日本語版は[こちら](README_JP.md)

## Overview

This assets is to execute <a href="http://ffmpeg.org/">FFmpeg</a> on editor and application.<br>
<br>
You can do below:
- Play Movies(mp4, avi, mov etc.)<br>
- Capture Game View or Camera(In Game)<br>
- Convert Video Files<br>
- Live Streaming to <a href="https://www.youtube.com/">Youtube</a>(rtmp etc.)<br>
etc.

## How to get it

[Please sponsor me](https://github.com/sponsors/NON906).

## Correspondence Environment

- Unity Editor(Windows/Mac/Linux)<br>
- Standalone(Windows/Mac/Linux)(Mono/IL2CPP)<br>
- Android(included Meta(Oculus) Quest 2)(IL2CPP)<br>
- iOS

## Document

Document is [HERE](Document_EN.md).

## Note for FFmpeg

This assets uses FFmpeg binary(Windows/Mac/Linux) or plugins(Windows/Mac/Android/iOS) built below.<br>
<br>
It using libraries is part only(please show Lisense). So, if libraries you want to use is not included, please rebuild and replace files.<br>
<br>
For Windows, Mac (Library) and Linux(Library), replace generated 1. from 2. and execute it. 
- Windows: <a href="https://github.com/NON906/ffmpeg-windows-build-helpers">1.</a> <a href="https://github.com/NON906/fftools_lib">2.</a><br>
- Mac(Library): <a href="https://github.com/NON906/ffmpeg-kit">1.</a> <a href="https://github.com/NON906/FfmpegUnityMacPlugin">2.</a><br>
- Linux(Library): <a href="https://github.com/NON906/ffmpeg-build-script">1.</a> <a href="https://github.com/NON906/fftools_lib">2.</a><br>
- <a href="https://github.com/NON906/ffmpeg-kit">Android/iOS</a><br>
- <a href="https://github.com/NON906/ffmpeg-build-script">Mac/Linux(Binary)</a>

## License

- Redistribution to anyone other than sponsors or purchasers is prohibited (except as permitted by the licenses below).

- The following components are governed by the licenses indicated below:

```
ffmpeg: LGPLv2.1
Copyright (c) 2000-2021 the FFmpeg developers

ffmpeg-kit: LGPLv3 (for Android/iOS/Mac)

SmartException: BSD 3-Clause (for Android)
Copyright (c) 2019-2020, Taner Sener

openh264: BSD 2-Clause
Copyright (c) 2013, Cisco Systems
(NOTE: Please check for Patent: http://www.openh264.org/BINARY_LICENSE.txt)

libvpx: BSD 3-Clause
Copyright (c) 2010, The WebM Project authors. All rights reserved.

aom: BSD 2-Clause
Copyright (c) 2016, Alliance for Open Media. All rights reserved.

opus: BSD 3-Clause
Copyright 2001-2011 Xiph.Org, Skype Limited, Octasic,
Jean-Marc Valin, Timothy B. Terriberry,
CSIRO, Gregory Maxwell, Mark Borgerding,
Erik de Castro Lopo

vorbis: BSD 3-Clause
Copyright (c) 2002-2020 Xiph.org Foundation

theora: BSD 3-Clause
Copyright (C) 2002-2009 Xiph.org Foundation

libwebp: BSD 3-Clause
Copyright (c) 2010, Google Inc. All rights reserved.

giflib: MIT License
The GIFLIB distribution is Copyright (c) 1997 Eric S. Raymond

libjpeg_turbo: BSD 3-Clause
Copyright (C)2009-2020 D. R. Commander. All Rights Reserved.
Copyright (C)2015 Viktor Szathmáry. All Rights Reserved.

libogg: BSD 3-Clause
Copyright (c) 2002, Xiph.org Foundation

libpng: PNG Reference Library License version 2
* Copyright (c) 1995-2019 The PNG Reference Library Authors.
* Copyright (c) 2018-2019 Cosmin Truta.
* Copyright (c) 2000-2002, 2004, 2006-2018 Glenn Randers-Pehrson.
* Copyright (c) 1996-1997 Andreas Dilger.
* Copyright (c) 1995-1996 Guy Eric Schalnat, Group 42, Inc.

libtiff: libtiff License
Copyright (c) 1988-1997 Sam Leffler
Copyright (c) 1991-1997 Silicon Graphics, Inc.

gmp: LGPLv3
Copyright 1991, 1996, 1999, 2000, 2007 Free Software Foundation, Inc.

nettle: LGPLv3
Copyright (C) 2007 Free Software Foundation, Inc. <http://fsf.org/>

gnutls: LGPLv2.1
Copyright (C) 1991, 1999 Free Software Foundation, Inc.

winpthreads: MIT License & BSD 3-Clause
Copyright (c) 2011 mingw-w64 project (MIT)
* (C) 2010 Lockless Inc.
* All rights reserved. (BSD)

lame: LGPLv2
Copyright (C) 1991 Free Software Foundation, Inc.
59 Temple Place, Suite 330,
Boston, MA 02111-1307 USA
(www.mp3dev.org)

sdl: zlib License
Copyright (C) 1997-2022 Sam Lantinga
<slouken@libsdl.org>

libxml2: MIT License
Copyright (C) 1998-2012 Daniel Veillard. All Rights Reserved.
```
