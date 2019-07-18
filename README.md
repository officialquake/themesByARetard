# themesByARetard

Howdy Partner
Discord: onion#9529

Usage: 
1. Drag the .cs file into your project.
2. Start the build so the control pops up.
3. Drag the control on, and dock it on full if it's a form control.
4. For the form right click and send it to the back, also set the resizable mode to none.
5. (Optional) add this to your form's loading function to speed up drawing.
```c#
SetStyle(
ControlStyles.OptimizedDoubleBuffer 
| ControlStyles.AllPaintingInWmPaint 
| ControlStyles.DoubleBuffer 
| ControlStyles.UserPaint 
| ControlStyles.ResizeRedraw 
| ControlStyles.SupportsTransparentBackColor, true
);
```
