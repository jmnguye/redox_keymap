# The default keymap for Redox

I activated tap dance : https://github.com/samhocevar-forks/qmk-firmware/blob/master/docs/feature_tap_dance.md 

Update `rules.mk` with `TAP_DANCE_ENABLE = yes`

copy all file in directory :
`~/qmk_firmware/keyboards/redox/keymaps/KEYMAPNAME`

compile the firmware first
`qmk compile`
then flash
`qmk flash`
