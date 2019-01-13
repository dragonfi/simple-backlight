# simple-backlight
A simple script to set the backlight.

## i3 setup

1. Add this script to your pathl
2. Add the following to your .config/i3/config:

  set $brightness_step 100
  bindsym XF86MonBrightnessUp exec brightness -inc $brightness_step
  bindsym XF86MonBrightnessDown exec brightness -dec $brightness_step

