# MultiFontText


## Example:
```lua
hook.Add("HUDPaint", "HUDPaint_MultiFontText_Example", function()
  draw.MultiFontText(Color(255, 255, 255), ScrW()/2, ScrH()/2, TEXT_ALIGN_CENTER, TEXT_ALIGN_CENTER, "Roboto-Regular", "This text ", "Roboto-Black", "has multiple ", "Roboto-Italic", "different fonts")
end)
```



## API Context:
**Color**: A color created with [Color](https://wiki.facepunch.com/gmod/Global.Color).

**x**: The X coordinate on the screen.

**y**: The Y coordinate on the screen.

**xAlign**: The alignment of the X coordinate using [Enums/TEXT_ALIGN](https://wiki.facepunch.com/gmod/Enums/TEXT_ALIGN).

**yAlign**: The alignment of the Y coordinate using [Enums/TEXT_ALIGN](https://wiki.facepunch.com/gmod/Enums/TEXT_ALIGN).

**vararg**: A [vararg](https://wiki.facepunch.com/gmod/vararg) of fonts and strings. Any non string value will be converted to a string with [tostring()](https://wiki.facepunch.com/gmod/Global.tostring).

```
draw.MultiFontText(Font, x, y, xAlign, yAlign, vararg)
```
