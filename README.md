# Dark Souls 3 Patcher

Improves Dark Souls 3 experience. Temporarily patches the game executable. Don't use online to avoid bans.

## Compatibility

- Dark Souls 3 1.15
- Python 3.8 or newer

## Usage

1. Copy `ds3_patcher` and `ds3_patcher.yaml` to the game directory
2. If you're on Linux, `chmod u+x ds3_patcher`
3. In Steam, set the game launch options to `python ds3_patcher <arguments> -- %command%`

### Examples

In Linux, there are multiple ways to launch `ds3_patcher` and setup other tools

```zsh
python ds3_patcher -is -- env MANGOHUD=1 %command%
./ds3_patcher --skip-intro --sync-save -- mangohud gamemoderun %command%
```

In Windows, use `pythonw` to prevent showing a terminal window

```zsh
pythonw ds3_patcher -is -- %command%
```

## Features

- `-i` or `--skip-intro` - skip publisher and developer logos
- `-s` or `--sync-save` - sync save via remote git repository

## Credits

- [er-patcher](https://github.com/gurrgur/er-patcher/)
- [DarkSouls3RemoveIntroScreens](https://github.com/bladecoding/DarkSouls3RemoveIntroScreens)
