<p align="center">
  <img src="https://raw.githubusercontent.com/remarkablegames/renpy-solitaire/master/game/images/card/53.png" alt="Renpy Solitaire">
</p>

# Ren'Py Solitaire

[![build](https://github.com/remarkablegames/renpy-solitaire/actions/workflows/build.yml/badge.svg)](https://github.com/remarkablegames/renpy-solitaire/actions/workflows/build.yml)
[![lint](https://github.com/remarkablegames/renpy-solitaire/actions/workflows/lint.yml/badge.svg)](https://github.com/remarkablegames/renpy-solitaire/actions/workflows/lint.yml)

🃏 Ren'Py [Solitaire](<https://wikipedia.org/wiki/Klondike_(solitaire)>) card game. See [Cardgame](https://www.renpy.org/wiki/renpy/Cardgame) or [Ren'Py Cardgame Engine](https://github.com/renpy/cardgame).

Play the game on:

- [remarkablegames](https://remarkablegames.org/renpy-solitaire)

## Prerequisites

Download [Ren'Py SDK](https://www.renpy.org/latest.html):

```sh
git clone https://github.com/remarkablegames/renpy-sdk.git
```

Symlink `renpy`:

```sh
sudo ln -sf "$(realpath renpy-sdk/renpy.sh)" /usr/local/bin/renpy
```

Check the version:

```sh
renpy --version
```

## Install

Clone the repository to the `Projects Directory`:

```sh
git clone https://github.com/remarkablegames/renpy-solitaire.git
cd renpy-solitaire
```

## Run

Launch the project:

```sh
renpy .
```

Or open the `Ren'Py Launcher`:

```sh
renpy
```

Press `Shift`+`R` to reload the game.

Press `Shift`+`D` to open the developer menu.

## Cache

Clear the cache:

```sh
find game -name "*.rpyc" -delete
```

Or open `Ren'Py Launcher` > `Force Recompile`:

```sh
renpy
```

## Lint

Lint the game:

```sh
renpy game lint
```

## License

[MIT](LICENSE)
