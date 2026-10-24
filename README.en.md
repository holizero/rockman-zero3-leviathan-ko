# Rockman Zero 3 · Leviathan Korean Mod

[한국어](./README.md) | **English**

A fan mod that replaces Zero with playable Leviathan in Rockman Zero 3. It includes spear and ice attacks, dedicated swimming, a custom title screen and portrait, and Korean menus. The patch applies the Korean translation and mod together to the supported Japanese original. This is a Korean-language mod; this English README is an installation guide.

![Leviathan Korean title screen](./title.png)

## Download

**[Download v1.0.1 patch package](https://github.com/holizero/rockman-zero3-leviathan-ko/releases/download/v1.0.1/leviathan-ko-v1.0.1.zip)** · [Release notes](https://github.com/holizero/rockman-zero3-leviathan-ko/releases/tag/v1.0.1) · [ZIP checksum](https://github.com/holizero/rockman-zero3-leviathan-ko/releases/download/v1.0.1/leviathan-ko-v1.0.1.zip.sha256)

Choose **`leviathan-ko-v1.0.1.zip`**, rather than GitHub's automatically generated `Source code (zip)`.

## Version history

- **v1.0.1 · 2026-10-25:** Fixed repeated hitstop that caused slowdown when spear attacks hit guarding enemies.
- **v1.0.0 · 2026-10-25:** Initial stable release.

Patch the supported Japanese original with the v1.0.1 package. Back up your in-game save and restart the new ROM; do not load an older save state.

## Installation and restoration

1. Extract the complete release ZIP.
2. Open `레비아탄_패치도구.html` in a browser.
3. Select the supported Japanese original `.gba`, choose `패치 적용` (Apply patch), and save the result as a new file.
4. Open the patched ROM in an emulator and start a new game.

The patcher works offline in the browser. No separate Korean patch or server is required. It does not overwrite the input ROM or save file.

To restore the Japanese original, choose `일본판 원본 복원`, select this release's patched ROM, then choose `원본 복원`.

## Supported original

| Item | Required value |
| --- | --- |
| Game | Rockman Zero 3 (Japan) |
| Game code | BZ3J |
| Size | 8,388,608 bytes |
| SHA-1 | `ff7a801776dc76e6d8c7ef73a6660ae732934a3f` |

Korean, North American, development, and already modified ROMs are unsupported. Back up ROMs and saves before installation. Restart the patched ROM and use in-game saves instead of older save states. Detailed controls, save guidance, and verification scope are included in the release ZIP.

## Blog guide

[한국어 가이드](https://mntkim.com/rockman-zero-3-leviathan-korean-mod-v1-0-0/) · [English guide](https://mntkim.com/en/rockman-zero-3-leviathan-korean-mod-v1-0-0/)

## Notes

- No original or patched game ROMs, saves, or emulator binaries are distributed.
- Additional equipment, skills, and items are earned through normal progression, rather than granted at the start of a new game.
- Hidden features become available after collecting in-game elements.
- Existing mGBA verification covers 16 scenarios and 48,030 frames, including test-specific state setup. It does not establish full-campaign, real-hardware, or all-save compatibility.
- Original game: CAPCOM / INTI CREATES. This fan mod uses existing Korean translation data and Leviathan material from Zero 1, 2, and 3.

## Other Rockman Zero 3 mods

[Harpuia Korean Mod](https://github.com/holizero/rockman-zero3-harpuia-ko) · [Omega Zero Korean Mod](https://github.com/holizero/rockman-zero3-omega-ko). Apply each mod separately to the supported Japanese original; do not stack them.
