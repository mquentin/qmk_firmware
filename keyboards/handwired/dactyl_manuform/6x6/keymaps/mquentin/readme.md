## To compile

`qmk compile -kb handwired/dactyl_manuform/6x6 -km mquentin``

## To flash

### Manually 

- `qmk flash -kb handwired/dactyl_manuform/6x6 -km mquentin`
- reset (cf. later section)

### QMK-toolbox

#### If not installed

- `brew install qmk-toolbox` 
- enable in macOS security
- run it


#### If installed

- run it
- load the compiled hex file
- pick atmega32u4 processor cf. keyboards/handwired/dactyl_manuform/6x6/promicro/keyboard.json
- reset
- click flash


### To Reset

with current layout to reset: press and hold ESC_RSTA then KC_ENTER THEN KC_LGUI

