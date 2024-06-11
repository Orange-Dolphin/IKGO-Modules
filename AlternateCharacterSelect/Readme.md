# Setup
Place Alternate Character Select.lua into external/mods for the lua code to initalize

# Required Paramaters
p#.fp.main.pos = x, y ;Sets where the character the player is currently hovering over should be set, all other placements are placed around this one.

# Optional Paramaters
```
p#.fp.scale = x,y;Sets how large the currently hovered character should be shown relative to regular size, defaults to 1,1
```
```
p#.fp.down = #;Sets how many characters below the main one should be shown, defaults to 0
p#.fp.up = #;Sets how many characters above the main one should be shown, defaults to 0
p#.fp.main.left = #;Sets how many characters to the left of the main one should be shown, defaults to 0
p#.fp.main.right = #;Sets how many characters to the right of the main one should be shown, defaults to 0
```
```
p#.fp.DIRECTION.spacing = x,y;Sets the space between cells in any specific direction(up, down, left, right), defaults to cell size
```

```
p#.fp.up.V.right = #;Sets how many characters to the right of the character V number of slots up from the main one should be shown, defaults to 0
p#.fp.up.V.left = #;Sets how many characters to the left of the character V number of slots up from the main one should be shown, defaults to 0
p#.fp.down.V.right = #;Sets how many characters to the right of the character V number of slots down from the main one should be shown, defaults to 0
p#.fp.down.V.left = #;Sets how many characters to the left of the character V number of slots down from the main one should be shown, defaults to 0
```
