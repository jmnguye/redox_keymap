# The default keymap for Redox

ref :
https://yanfali.github.io/keycodes/

features have to be update
`~/qmk_firmware/keyboards/redox/rev1`

led count is updated with value 34 in info.json found in 
`~/qmk_firmware/keyboards/redox/rev1`

clone the repo in:
`~/qmk_firmware/keyboards/redox/keymaps/`

don't forget to set the keymaps
`qmk config user.keymap=redox_keymap` 

compile the firmware first
`qmk compile`
then flash
`qmk flash`
