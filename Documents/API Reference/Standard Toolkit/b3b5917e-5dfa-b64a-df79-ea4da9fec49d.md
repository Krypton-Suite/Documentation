# MouseDown Method


Mouse button has been pressed in the view.



## Definition
**Namespace:** <a href="a21ac074-d119-3dc6-bd1c-d3a12c0128bc.md">Krypton.Navigator</a>  
**Assembly:** Krypton.Navigator (in Krypton.Navigator.dll) Version: 80.23.10.287+8d7660f9dc5efd033fabe008ebfb904beab6d444

**C#**
``` C#
public virtual bool MouseDown(
	Control c,
	Point pt,
	MouseButtons button
)
```
**VB**
``` VB
Public Overridable Function MouseDown ( 
	c As Control,
	pt As Point,
	button As MouseButtons
) As Boolean
```



#### Parameters
<dl><dt>  Control</dt><dd>Reference to the source control instance.</dd><dt>  Point</dt><dd>Mouse position relative to control.</dd><dt>  MouseButtons</dt><dd>Mouse button pressed down.</dd></dl>

#### Return Value
Boolean  
True if capturing input; otherwise false.

#### Implements
<a href="2dc37542-2808-cca9-9b5c-bf9002c30471.md">IMouseController.MouseDown(Control, Point, MouseButtons)</a>  


## See Also


#### Reference
<a href="4c79fefd-c14e-b4de-83fa-875e4578a143.md">DragViewController Class</a>  
<a href="a21ac074-d119-3dc6-bd1c-d3a12c0128bc.md">Krypton.Navigator Namespace</a>  
