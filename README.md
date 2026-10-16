# OK Mixer

Per-application audio control for GNOME Shell, for GNOME 50+.

OK Mixer is a clean rewrite of the now-archived GNOME Application Volume Mixer extension, focused on compatibility, simplicity, and native GNOME integration.

## Why “OK”?

Because it is meant to be... OK.

OK Mixer aims to be a simple, reliable, application volume mixer for daily use.
No giant feature set, no configurations, just quick per-application volume control that works well and stays out of the way.

The name is also short for _Oklahoma Mixer_ (オクラホマミキサー), the Japanese name for the “Turkey in the Straw” folk dance.

## Usage

Open quick settings and use the Mixer toggle to adjust per-app volumes.

## Development

- Entry point: `extension.js`
- Modules: `src/appVolumeSlider.js`, `src/mixerToggle.js`, `src/mixerIndicator.js`

## Packaging

When publishing, create the extension package using:

```bash
gnome-extensions pack . --extra-source src/ --out-dir dist/
```

## Credits

Inspired by Gnome Application Volume Mixer extension (archived): <https://github.com/mymindstorm/gnome-volume-mixer>.
It targets older GNOME Shell versions and does not work on GNOME 50.
