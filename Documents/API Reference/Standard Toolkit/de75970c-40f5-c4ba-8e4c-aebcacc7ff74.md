# DrawBackGlassTrackingStump Method


Draw a background in tracking stumpy glass effect.



## Definition
**Namespace:** <a href="79d2eac2-21f4-54ff-7552-b20c33c30600.md">Krypton.Toolkit</a>  
**Assembly:** Krypton.Toolkit (in Krypton.Toolkit.dll) Version: 80.23.10.287+8d7660f9dc5efd033fabe008ebfb904beab6d444

**C#**
``` C#
public static IDisposable? DrawBackGlassTrackingStump(
	RenderContext context,
	Rectangle rect,
	Color backColor1,
	Color backColor2,
	VisualOrientation orientation,
	GraphicsPath path,
	IDisposable? memento
)
```
**VB**
``` VB
Public Shared Function DrawBackGlassTrackingStump ( 
	context As RenderContext,
	rect As Rectangle,
	backColor1 As Color,
	backColor2 As Color,
	orientation As VisualOrientation,
	path As GraphicsPath,
	memento As IDisposable
) As IDisposable
```



#### Parameters
<dl><dt>  <a href="ef60a5af-08ff-7a94-87f5-362a7e392cd4.md">RenderContext</a></dt><dd>Rendering context.</dd><dt>  Rectangle</dt><dd>Rectangle to draw.</dd><dt>  Color</dt><dd>First color.</dd><dt>  Color</dt><dd>Second color.</dd><dt>  <a href="d38051f8-c2cc-e81c-0029-02f7ad46f2fa.md">VisualOrientation</a></dt><dd>Drawing orientation.</dd><dt>  GraphicsPath</dt><dd>Clipping path.</dd><dt>  IDisposable</dt><dd>Cache used for drawing.</dd></dl>

#### Return Value
IDisposable  
\[Missing &lt;returns&gt; documentation for "M:Krypton.Toolkit.RenderGlassHelpers.DrawBackGlassTrackingStump(Krypton.Toolkit.RenderContext,System.Drawing.Rectangle,System.Drawing.Color,System.Drawing.Color,Krypton.Toolkit.VisualOrientation,System.Drawing.Drawing2D.GraphicsPath,System.IDisposable)"\]

## See Also


#### Reference
<a href="5dd36462-c8ca-e41d-4392-c6e4e5729519.md">RenderGlassHelpers Class</a>  
<a href="79d2eac2-21f4-54ff-7552-b20c33c30600.md">Krypton.Toolkit Namespace</a>  
