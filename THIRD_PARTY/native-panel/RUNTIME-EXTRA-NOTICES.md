# Native controller panel runtime additions

These notices are in addition to the unchanged Tidycade 0.11.0 runtime notices. Games download separately and keep their own terms. No code in these runtime libraries was changed by Tidycade.

The native panel uses Tcl/Tk through Python's tkinter binding. Ubuntu builds use Tcl/Tk 8.6.12 and the Ubuntu Python 3.10 tkinter binding, with the BLT shared library it links against. Windows builds use Tcl/Tk 8.6.15 from the full Python 3.12.8 distribution. Their exact supplied notice texts are included. Windows libffi and zlib notices remain in the full Python distribution license.

Ubuntu native-display dependencies include X11, Xft, Xrender, Xss, Xext, Xau, Xdmcp, libbsd, libmd, fontconfig, FreeType, libpng, Brotli and libffi. The exact Ubuntu package copyright files retain the original component notices and their complete terms, including notices for source/build files that are not part of the binary libraries bundled here. The package/version manifest records where these notices came from.

This software is based in part on the work of the FreeType Team. FreeType's FTL license is selected for the bundled FreeType library, rather than its alternative GPL license. FreeType source and build-tool notices remain in the package copyright document; source-only build tools are not shipped in the runtime executable.

The controller input backend uses a small original ctypes binding and SDL 2.28.4, not pygame. No pygame, NumPy, SDL_image/mixer/ttf or their codec/font stacks are included. The separately recorded SDL provenance and full SDL/HIDAPI/yuv2rgb notice texts accompany this distribution. HIDAPI is used under its BSD-style alternative, not the alternative GPL license. The original SDL source archive retains all source notices.

Windows Tcl 8.6.15 notice provenance: tcltk/tcl official repository tag core-8-6-15, commit 1a98213e55128c8a2136379fedfaef0c8e15320b, license.terms. Windows Tk notice was copied from its actual Python runtime tcl/tk8.6/license.terms. Python scripts require exact Tcl/Tk 8.6.15, verified from init.tcl and tk.tcl.
