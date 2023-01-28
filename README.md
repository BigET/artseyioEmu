# artseyioEmu
A software emulation of the artseyio keyboard.

Sometimes you want ot try a interesting keyboard, but you do not have the hardware.

For the ARTSEYIO you can take a normal keyboard/keypad and put this emulation layer.

Now you have a way to try it.

# Building

Just run make. You should have the linux haders installed.

# Running

aetseyioEmu {-A keycode} {-R keycode} {-T keycode} {-S keycode} {-E keycode} {-Y keycode} {-I keycode} {-O keycode} {-n keyboad_name} -d device_to_grab

This will grab the provided device and then will create another uinput device to emulate the keyboard.
