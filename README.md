# Dark Souls 3 Patcher

Improves Dark Souls 3 experience. Temporarily patches the game executable. Don't use online to avoid bans.

## Dependencies

- Python 3.8 or newer

## Usage

1. Copy `ds3-patcher` to the game directory
2. In Steam, set the game launch options to `python ds3-patcher <arguments> -- %command%`

### Examples

In Linux, other tools can be enabled and configured in different ways

```zsh
python ds3-patcher --s -- env MANGOHUD=1 %command%
python ds3-patcher --skip-intro -- mangohud gamemoderun %command%
```

In Windows, use `pythonw` to prevent showing a terminal window

```zsh
pythonw ds3-patcher --all -- %command%
```

## Features

- `-s` or `--skip-intro` - skip intro logos
- `--all` - enable all options

## Credits

- [er-patcher](https://github.com/gurrgur/er-patcher/)
- [DarkSouls3RemoveIntroScreens](https://github.com/bladecoding/DarkSouls3RemoveIntroScreens)
