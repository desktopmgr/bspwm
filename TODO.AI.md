# TODO

## etc/bspwm-sxhkdrc pre-existing binding conflict (found incidentally, out of scope for keybinding standardization)

- [ ] `super + o` is bound twice: line 140 (`bspc node -g sticky={on,off}`)
      and line 143-144 (`super + {i,o}` -> `bspc node -f {prev,next}.local`).
      Only one can actually fire; decide which binding is intended and
      remove/remap the other.
