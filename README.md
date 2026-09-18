# Fradev OS 1.0 Stable

**Un sistema para crear sin límites.**

Fradev OS is a developer-focused GNU/Linux workstation that unifies development, productivity, Windows compatibility, Android integration, gaming, virtualization and hardware tooling in one coherent desktop.

The public product name is **Fradev OS** and its visual layer is **fraGlass**. Version **1.0 Stable** is the canonical release baseline.

## Main components

- **Fradev OS Control Center** — system health, development profiles, services, tools and system management.
- **fraGlass** — visual presets, opacity, blur and session persistence.
- **Fradev OS Puente** — Wine plus Proton/UMU best-effort paths for Windows applications.
- **Android / Waydroid** — APK integration, shortcuts and post-reboot persistence.
- **Steam + Game Lab** — normal Steam workflow plus user-supplied legal game builds/ROMs.
- **Fradev Devices + Hardware Vault** — printing, scanning, Bluetooth, phones, storage, firmware, GPU/display diagnostics and redistributable support tooling.
- **Compatibility Center** — clear status for native, Windows, Android, gaming, devices, virtualization and network dependencies.

## Compatibility policy

Fradev OS does not claim universal cross-platform compatibility. Proprietary runtimes, DRM, anti-cheat, architecture-specific applications and vendor-only drivers can require Internet, licensed guest images or extra configuration. These limitations are shown rather than hidden.

## Stable source/build policy

The Clean-Room Builder contains the exact Fradev OS 1.0 source archive and verifies its SHA-256 before building. A newly generated ISO should complete the Live → offline install → reboot → online regression cycle before that specific ISO is marked hardware-validated.

## Canonical project endpoints after repository rename

- Site: `https://yottomtnz.github.io/fradevosupdate/`
- Repository: `https://github.com/YottoMtnz/fradevosupdate`
- Update feed: `https://raw.githubusercontent.com/YottoMtnz/fradevosupdate/main/update`
