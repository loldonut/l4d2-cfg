# Left 4 Dead 2 config files

My Left 4 Dead 2 config files

## Install Script (Linux Only)

**Note: This symlinks to `$HOME/.local/share/Steam/steamapps/common/Left 4 Dead 2/left4dead2/cfg`, so Steam installed through flatpak won't work.**

```sh
./install
```

## Format `autoexec.cfg`

To make the tab width consistent you can use the CLI tool provided in this repo:

```sh
python3 fmt_cfg.py autoexec.cfg
```

### usage

```
usage: fmt_cfg.py [-h] [-t TAB_WIDTH] file

Align CFG variables into clean columns.

positional arguments:
  file                  Path to the .cfg file

options:
  -h, --help            show this help message and exit
  -t, --tab-width TAB_WIDTH
                        Spaces after the longest variable (default: 5)
```
