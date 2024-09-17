# To compile

`qmk compile -kb handwired/dactyl_manuform/6x6 -km mquentin``

# To flash

## Manually 

- `qmk flash -kb handwired/dactyl_manuform/6x6 -km mquentin`
- reset (cf. later section)

## QMK-toolbox

### If not installed

- `brew install qmk-toolbox` 
- enable in macOS security
- run it


### If installed

- run it
- load the compiled hex file `/Users/.../qmk_mquentin/qmk_firmware/handwired_dactyl_manuform_6x6_promicro_mquentin.hex`
- pick atmega32u4 processor cf. keyboards/handwired/dactyl_manuform/6x6/promicro/keyboard.json
- reset
- click flash

![Screenshot 2024-09-17 at 13 02 43](https://github.com/user-attachments/assets/04d2a01a-2a45-474e-b7f4-aad5498d784f)


# To Reset

with current layout to reset: press and hold ESC_RSTA then KC_ENTER THEN KC_LGUI

![PXL_20240917_105940414~2](https://github.com/user-attachments/assets/96e63271-b1fd-4585-aab9-2037f34e923a)

