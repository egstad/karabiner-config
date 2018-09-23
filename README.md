# Karabiner Elements Config

## Note
This file is read from top to bottom and the order of rules is very important. 

## Rules


### Caps Lock > Delete/FN
Caps lock is used for a few things. When pressed alone, it becomes the `delete_or_backspace` key. When held down, it becomes the `fn` key. This is helpful for using `awsd` and `jikl` keys as arrows.

### Right Shift > Caps Lock (When Held)
Every now and again, I need to enable caps lock — usually for  formatting text when `text-transform: uppercase` is not an option. To address this, I've mapped the `right_shift` key, when held for 1.5 seconds, to `caps_lock`. I've chosen the right over left because I often press and hold the left key to modify the arrow keys.


### FN > WASD & IJKL Arrows
One of the main reasons `caps_lock` has been remapped to `fn` is so my fingers don't have to leave home row in order to use the arrow keys. By holding `caps`, which has now been remapped to `fn`, I can use the `wasd` and `ijkl` keys as arrows.

### FN + Spacebar > FN + Shift
I often use shift as a modifier for arrow keys, mostly for quickly moving elements in design programs. To address this need, press and hold `fn` (caps_lock) and press `spacebar`. This is remapped to `left_shift`. 

### Tilde > Escape
IMO, one of the more annoying parts of working on a 60% keyboard as a developer is the loss of the tilde/grave accent keys. In JS, the tilde is an operator and the grave accent is used for template strings — I use them a lot. I also quite like the escape key at the top left of the board, so I wrote a script that gives me the best of both worlds. The `grave_accent_and_tilde` key has been mapped to `escape` by default and when held down (for > .1s) it is mapped back to the `grave_accent_and_tilde` key.  