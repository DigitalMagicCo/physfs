
PhysicsFS; a portable, flexible file i/o abstraction.

  https://icculus.org/physfs/

Please see the docs directory for documentation.

Please see LICENSE.txt for licensing information.

DigitalMagic modifications:
 * Added Visual Studio project and solution
 * Redefined PHYSFS_DECL for _MSC_VER so no symbols would be exported for static linking.
 * Tweaked SDL include so it'll use vcpkg's SDL2 in extras/physfsrwops.h
 * Tweaked physfs.h include in extras/physfsrwops.h so it'll be relative.
 * Fixed bug in PHYSFS_init on Windows where initialization would fail without details.
   * Bug fix found here: http://icculus.org/pipermail/physfs/2018-October/001272.html

