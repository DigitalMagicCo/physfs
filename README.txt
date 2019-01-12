
PhysicsFS; a portable, flexible file i/o abstraction.

  https://icculus.org/physfs/

Please see the docs directory for documentation.

Please see LICENSE.txt for licensing information.

DigitalMagic modifications:
 * Added Visual Studio project and solution
 * Redefined PHYSFS_DECL for _MSC_VER so no symbols would be exported.
 * Tweaked SDL include so it'll use vcpkg's SDL2 in extras/physfsrwops.h
 * Tweaked physfs.h include in extras/physfsrwops.h so it'll be relative.

