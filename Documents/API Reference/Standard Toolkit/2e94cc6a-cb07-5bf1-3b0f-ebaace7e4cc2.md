# DrawImageHelper Method


Helper routine to draw an image taking into account various properties.



## Definition
**Namespace:** <a href="79d2eac2-21f4-54ff-7552-b20c33c30600.md">Krypton.Toolkit</a>  
**Assembly:** Krypton.Toolkit (in Krypton.Toolkit.dll) Version: 80.23.10.287+8d7660f9dc5efd033fabe008ebfb904beab6d444

**C#**
``` C#
protected static void DrawImageHelper(
	ViewContext context,
	Image image,
	Color remapTransparent,
	Rectangle imageRect,
	VisualOrientation orientation,
	PaletteImageEffect effect,
	Color remapColor,
	Color remapNew
)
```
**VB**
``` VB
Protected Shared Sub DrawImageHelper ( 
	context As ViewContext,
	image As Image,
	remapTransparent As Color,
	imageRect As Rectangle,
	orientation As VisualOrientation,
	effect As PaletteImageEffect,
	remapColor As Color,
	remapNew As Color
)
```



#### Parameters
<dl><dt>  <a href="ed48663c-5842-51d4-9c11-490570023d3d.md">ViewContext</a></dt><dd>Rendering context.</dd><dt>  Image</dt><dd>Image to be drawn.</dd><dt>  Color</dt><dd>Color that should become transparent.</dd><dt>  Rectangle</dt><dd>Destination rectangle.</dd><dt>  <a href="d38051f8-c2cc-e81c-0029-02f7ad46f2fa.md">VisualOrientation</a></dt><dd>Visual orientation.</dd><dt>  <a href="32bb7d2d-d70a-08af-0e9a-60c232f62d5a.md">PaletteImageEffect</a></dt><dd>Drawing effect.</dd><dt>  Color</dt><dd>Image color to remap.</dd><dt>  Color</dt><dd>New color for remap.</dd></dl>

## Exceptions
<table>
<tr>
<td>ArgumentNullException</td>
<td /></tr>
</table>

## See Also


#### Reference
<a href="6cc5032c-8089-e880-78ad-3a805f7bd344.md">RenderBase Class</a>  
<a href="79d2eac2-21f4-54ff-7552-b20c33c30600.md">Krypton.Toolkit Namespace</a>  
