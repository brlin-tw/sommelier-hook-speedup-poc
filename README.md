# Sommelier Core Scripts' hook based initialization speed-up PoC(incomplete)

Cut down first launch time by doing the Wine initialization process
during snap install using Snapd's hook mechanism.

Refer [[Enhancement]: Support initializing Wine during snap installation
to accelerate first-time launch speed · Issue #29 ·
snapcrafters/sommelier-core](https://github.com/snapcrafters/sommelier-core/issues/29)
for more info.

## Reference

* [Snapcraft hook support - doc - snapcraft.io](https://forum.snapcraft.io/t/snapcraft-hook-support/19069)
* [Supported snap hooks - doc - snapcraft.io](https://forum.snapcraft.io/t/supported-snap-hooks/3795#heading--the-configure-hook)
* [snapcrafters/sommelier-core: Package a Windows application for Linux using a Snap with Wine.](https://github.com/snapcrafters/sommelier-core)
* [[Enhancement]: Support initializing Wine during snap installation to
  accelerate first-time launch speed · Issue #29 · snapcrafters/sommelier-core](https://github.com/snapcrafters/sommelier-core/issues/29)
* [Wineboot - WineHQ Wiki](https://wiki.winehq.org/Wineboot)
