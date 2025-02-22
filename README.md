Flatpak manifest for SimpleDiary
================================

### Updating gtkmdeditor

1. Download gtkmdeditor source
2. Download flatpak-cargo-generator.py from [flatpak-builder-tools](https://github.com/flatpak/flatpak-builder-tools/blob/master/cargo/flatpak-cargo-generator.py)
3. Run "./flatpak-cargo-generator.py -o gtkmdeditor-cargo-deps.json Cargo.lock"
4. Copy gtkmdeditor-cargo-deps.json into this repository

To veryfy that it will also work in the flathub builder, use the script "build" in this repo which forces local builds.
