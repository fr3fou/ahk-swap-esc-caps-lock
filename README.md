# ahk-swap-esc-caps-lock
:arrows_counterclockwise: Simple AHK script to swap Esc with Caps-Lock (and binding caps to Scroll Lock). Used primarily by vim users.

## Better Linux alternative

```
remove Lock = Caps_Lock
keysym Escape = Caps_Lock
keysym Caps_Lock = Escape
add Lock = Caps_Lock
```

Add this to your `~/.xmodmap` file.

After that type

```sh
xmodmap ~/.xmodmap
```

or add it to your startup.
