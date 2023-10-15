# ButtonSpecManagerLayoutRibbon Constructor


Initialize a new instance of the ButtonSpecManagerLayoutRibbon class.



## Definition
**Namespace:** <a href="1e9bc734-cff9-e9b8-f013-94cdac669794.md">Krypton.Ribbon</a>  
**Assembly:** Krypton.Ribbon (in Krypton.Ribbon.dll) Version: 80.23.10.287+8d7660f9dc5efd033fabe008ebfb904beab6d444

**C#**
``` C#
public ButtonSpecManagerLayoutRibbon(
	KryptonRibbon ribbon,
	PaletteRedirect? redirector,
	ButtonSpecCollectionBase variableSpecs,
	ButtonSpecCollectionBase fixedSpecs,
	ViewLayoutDocker[] viewDockers,
	IPaletteMetric[] viewMetrics,
	PaletteMetricInt[] viewMetricInt,
	PaletteMetricPadding[] viewMetricPaddings,
	GetToolStripRenderer getRenderer,
	NeedPaintHandler needPaint
)
```
**VB**
``` VB
Public Sub New ( 
	ribbon As KryptonRibbon,
	redirector As PaletteRedirect,
	variableSpecs As ButtonSpecCollectionBase,
	fixedSpecs As ButtonSpecCollectionBase,
	viewDockers As ViewLayoutDocker(),
	viewMetrics As IPaletteMetric(),
	viewMetricInt As PaletteMetricInt(),
	viewMetricPaddings As PaletteMetricPadding(),
	getRenderer As GetToolStripRenderer,
	needPaint As NeedPaintHandler
)
```



#### Parameters
<dl><dt>  <a href="208400ac-72b3-453b-6730-d74762316d42.md">KryptonRibbon</a></dt><dd>Ribbon that owns the button manager.</dd><dt>  <a href="eb4bd14d-b283-a570-c104-b4d55603d473.md">PaletteRedirect</a></dt><dd>Palette redirector.</dd><dt>  <a href="b2d666e2-6a3d-ffbf-f115-af56bd76b9f0.md">ButtonSpecCollectionBase</a></dt><dd>Variable set of button specifications.</dd><dt>  <a href="b2d666e2-6a3d-ffbf-f115-af56bd76b9f0.md">ButtonSpecCollectionBase</a></dt><dd>Fixed set of button specifications.</dd><dt>  <a href="d692b067-ecab-d4d3-b3c3-38897bc1b2c2.md">ViewLayoutDocker</a>[]</dt><dd>Array of target view dockers.</dd><dt>  <a href="24be40a1-a3fd-2c4b-ff96-f9b04b615193.md">IPaletteMetric</a>[]</dt><dd>Array of target metric providers.</dd><dt>  <a href="add1c883-3c14-ed6e-05cf-668b87f7fd6d.md">PaletteMetricInt</a>[]</dt><dd>Array of target metrics for outside/inside spacer size.</dd><dt>  <a href="0b770d6b-dbd6-9a12-4264-29d519d2ab3c.md">PaletteMetricPadding</a>[]</dt><dd>Array of target metrics for button padding.</dd><dt>  <a href="14e4bbc4-2e91-1098-6501-6cc39d60e0db.md">GetToolStripRenderer</a></dt><dd>Delegate for returning a tool strip renderer.</dd><dt>  <a href="33f685bd-f838-7c82-3e84-2827dccd141e.md">NeedPaintHandler</a></dt><dd>Delegate for notifying paint requests.</dd></dl>

## See Also


#### Reference
<a href="ce232063-b19f-2718-4912-3f3c5631f238.md">ButtonSpecManagerLayoutRibbon Class</a>  
<a href="1e9bc734-cff9-e9b8-f013-94cdac669794.md">Krypton.Ribbon Namespace</a>  
