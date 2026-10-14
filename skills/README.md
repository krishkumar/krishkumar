# Xcode Agent Skills

This directory contains the 10 agent skills exported from the active Xcode toolchain with `xcrun agent skills export` on October 14, 2026.

## Skills

- `adopt-c-bounds-safety` — adopt C bounds safety in C and Objective-C code
- `app-intents-specialist` — build and debug App Intents integrations
- `app-intents-whats-new-27` — apply App Intents updates introduced in Xcode 27
- `app-resizability` — make Apple platform apps adapt to different window sizes
- `audit-xcode-security-settings` — audit Xcode project security settings
- `building-document-based-swiftui-applications` — build document based SwiftUI apps
- `device-interaction` — interact with Apple devices during development
- `modernize-tests` — modernize Apple platform tests
- `swiftui-specialist` — design and implement SwiftUI interfaces
- `swiftui-whats-new-27` — apply SwiftUI updates introduced in Xcode 27

Each skill folder contains its `SKILL.md` and any supporting references or scripts included by the exporter.

## Export again

To refresh these files from the currently selected Xcode toolchain:

```sh
xcrun agent skills export --output-dir ./skills --replace-existing
```

The exported skill content is authored and distributed by Apple through Xcode. This repository is a personal export; consult Apple's terms for use and redistribution.
