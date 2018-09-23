# Karabiner Elements Config

## Introduction
Not long ago, I purchased my first 60% keyboard. In addition to the charming aesthetic it brought my desk, I also found the tactility of the board to be far superior when compared to the rubber dome keys I'd grown used to as a mac user. As someone who presses thousands of keys a day, I can't recommend a mechanical keyboard highly enough.

One of the trade-offs with this new board was a loss of functionality — like the lack of dedicated arrow keys. But, with necessity being the mother of invention, I've leveraged [Karabiner Elements](https://pqrs.org/osx/karabiner/) to help bring some of this functionality back, while also adding new functionality to my mac keyboard.

One of the perks of using KE instead of saving my keyboard profile in my keyboard's memory is that I don't have to retrain my fingers when I leave my board at home — now my keybindings are consistent between my macbook pro and my mechanical board.

This repo contains my personal KE profile. Feel free to use, abuse, comment, and improve.

_**Note: This file is read from top to bottom and the order of rules is very important.**_

## Rules


### Caps Lock > Delete/FN
Caps lock is used for a few things. When pressed alone, it becomes the `delete_or_backspace` key. When held down, it becomes the `fn` key. This is helpful for using `awed` and `jikl` keys as arrows.

### Right Shift > Caps Lock (When Held)
Every now and again, I need to enable caps lock — usually for  formatting text when `text-transform: uppercase` is not an option. To address this, I've mapped the `right_shift` key, when held for 1.5 seconds, to `caps_lock`. I've chosen the right over left because I often press and hold the left key to modify the arrow keys.


### FN > WASD & IJKL Arrows
One of the main reasons `caps_lock` has been remapped to `fn` is so my fingers don't have to leave home row in order to use the arrow keys. By holding `caps`, which has now been remapped to `fn`, I can use the `wasd` and `ijkl` keys as arrows.

### FN + Spacebar > FN + Shift
I often use shift as a modifier for arrow keys, mostly for quickly moving elements in design programs. To address this need, press and hold `fn` (caps_lock) and press `spacebar`. This is remapped to `left_shift`. 

### Tilde > Escape
IMO, one of the more annoying parts of working on a 60% keyboard as a developer is the loss of the tilde/grave accent keys. In JS, the tilde is an operator and the grave accent is used for template strings — I use them a lot. I also quite like the escape key at the top left of the board, so I wrote a script that gives me the best of both worlds. The `grave_accent_and_tilde` key has been mapped to `escape` by default and when held down (for > .1s) it is mapped back to the `grave_accent_and_tilde` key.  