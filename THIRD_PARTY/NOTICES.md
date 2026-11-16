# Third-party runtime notices

Keep this THIRD_PARTY folder with Tidycade when copying the download.
The notices below apply to bundled runtime components, not a new licence for
Tidycade's own code. These third-party notices do not grant a new licence to Tidycade's own code. Games downloaded separately retain their own licences.

## Ubuntu runtime

Python 3.10.12 (PSF and bundled component notices), OpenSSL 3.0.2 (Apache 2.0),
zlib 1.2.11, bzip2 1.0.8, Expat 2.4.7, XZ/liblzma 5.2.5, libmpdec 2.5.1,
and python-zstandard 0.25.0 with bundled Zstandard are included. The exact
Ubuntu package copyright files in this folder retain the applicable notices
and licence texts. Apache-2.0.txt supplies the complete Apache licence.
The XZ package copyright also covers build tools that are not bundled here;
liblzma's own code is public domain under the upstream declaration.

## Windows runtime

Python 3.12.8 and OpenSSL 3.0.15, plus Microsoft Visual C++ runtime
VCRUNTIME140.dll and VCRUNTIME140_1.dll version 14.42.34226.3, are included.
Windows-Python-3.12.8-LICENSE.txt contains the distribution's full Python,
third-party and Microsoft Distributable Code notices and conditions.
Apache-2.0.txt supplies the complete OpenSSL licence.

The Microsoft Distributable Code is supplied subject to the additional
conditions in Windows-Python-3.12.8-LICENSE.txt. Anyone redistributing or using
that code must comply with those conditions: preserve its notices, do not
imply Microsoft endorsement, do not distribute it for platforms other than
Microsoft operating systems/runtime technologies/application platforms, and
do not include it in malicious, deceptive or unlawful programs. These limits
apply to that Microsoft code, not to Python itself or Tidycade's own code.

## Packaging and game images

PyInstaller 6.22.3's bootloader exception permits distributing this combined
executable without imposing its GPL on Tidycade. Full terms are included.
Game image credits and notices are available through each card's Credits and
are bundled in the executable. Downloaded game-list additions retain notices
under home/catalogue-v3/<pack-hash>/attribution/. Older v2 cached notices remain under home/catalogue-v2/. Game programs are not bundled
in this client download; they install separately when chosen.

No bundled runtime component was modified for this packaging pass.

## Native controller menu additions in 0.12.0

See native-panel/RUNTIME-EXTRA-NOTICES.md and its exact platform-package notices for Tcl/Tk, BLT, X11 and font-library dependencies. This software is based in part on the work of the FreeType Team; the FTL license is selected. See SDL2-PROVENANCE.json, SDL2-2.28.4-LICENSE.txt, SDL2-HIDAPI-BSD.txt and SDL2-yuv2rgb-BSD.txt for the exact native input runtime and notices. The original unmodified SDL source archive and recorded configure flags are supplied with the matching application source. No pygame or media-codec stack is part of this release.
