# macbookpro-brightness-control
Macbook Pro 11.x Screen and Keyboard brightness control for use with i3wm or any other wm.

Still very rudimentary, but works...

Start mbc as root with `mbc start` or install the `mbc.service` systemd unit...

Use `mbc -h` for options and bind your keys in your i3 config.

Keybinding example for i3wm:
```
bindsym XF86MonBrightnessDown exec mbc screen decrease
bindsym XF86MonBrightnessUp exec mbc screen increase
bindsym XF86KbdBrightnessDown exec mbc keyboard decrease
bindsym XF86KbdBrightnessUp exec mbc keyboard increase
```
