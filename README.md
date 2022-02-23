All slavic XKB layouts.

## Installation
   
Change folder to ```$HOME/.config/xkb```, with creation if no, and chechout the repo into it.

```sh
cd ~/.config
git clone git@github.com:znamenica/slavicxkb.git xkb
```

## Usage

Apply the configuration to the currently used keyboards.

```sh
xkbcomp -I${HOME}/.config/xkb -R${HOME}/.config/xkb keymap/usual ${DISPLAY}
```

If you want to use more useful but unhabitual layout, which widely use the pinky finger, just use:

```sh
xkbcomp -I${HOME}/.config/xkb -R${HOME}/.config/xkb keymap/useful ${DISPLAY}
```
