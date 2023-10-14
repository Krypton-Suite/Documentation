# PaletteOffice2007BlackDarkModeBase Class


Provides a professional appearance using colors/fonts generated from system settings.



## Definition
**Namespace:** <a href="79d2eac2-21f4-54ff-7552-b20c33c30600.md">Krypton.Toolkit</a>  
**Assembly:** Krypton.Toolkit (in Krypton.Toolkit.dll) Version: 80.23.10.287+8d7660f9dc5efd033fabe008ebfb904beab6d444

**C#**
``` C#
public abstract class PaletteOffice2007BlackDarkModeBase : PaletteBase
```
**VB**
``` VB
Public MustInherit Class PaletteOffice2007BlackDarkModeBase
	Inherits PaletteBase
```

<table><tr><td><strong>Inheritance</strong></td><td>Object  →  MarshalByRefObject  →  Component  →  <a href="6da77fa5-1590-4646-f2ea-70002c922aee.md">PaletteBase</a>  →  PaletteOffice2007BlackDarkModeBase</td></tr>
<tr><td><strong>Derived</strong></td><td><a href="87fd35ed-b408-77a4-5240-9704668c4aa8.md">Krypton.Toolkit.PaletteOffice2007BlackDarkMode</a></td></tr>
</table>



## Constructors
<table>
<tr>
<td><a href="e877220d-d386-f7c8-d5ee-feb0cd84b9e3.md">PaletteOffice2007BlackDarkModeBase</a></td>
<td>Initialize a new instance of the PaletteOffice2007BlackDarkModeBase class.</td></tr>
</table>

## Properties
<table>
<tr>
<td><a href="2afc54ed-d7c2-9ff9-688b-6fd710bfbcda.md">BaseFont</a></td>
<td>Gets or sets the base palette font.<br />(Inherited from <a href="6da77fa5-1590-4646-f2ea-70002c922aee.md">PaletteBase</a>)</td></tr>
<tr>
<td><a href="ddb01e0d-c43f-a74e-b99b-65a345dcd90e.md">BaseFontSize</a></td>
<td>Gets and sets the base font size used when defining fonts.<br />(Inherited from <a href="6da77fa5-1590-4646-f2ea-70002c922aee.md">PaletteBase</a>)</td></tr>
<tr>
<td><a href="6e12dccc-b966-e968-34ba-eaa73b826af3.md">BasePaletteType</a></td>
<td>Gets or sets the type of the base palette.<br />(Inherited from <a href="6da77fa5-1590-4646-f2ea-70002c922aee.md">PaletteBase</a>)</td></tr>
<tr>
<td>CanRaiseEvents</td>
<td>Gets a value indicating whether the component can raise an event.<br />(Inherited from Component)</td></tr>
<tr>
<td><a href="276360a0-1422-19e6-cedd-ea82718f52ee.md">ColorTable</a></td>
<td>Gets access to the color table instance.<br />(Overrides <a href="6ffafb6c-ce51-edca-fb8c-8a64e15168ea.md">PaletteBase.ColorTable</a>)</td></tr>
<tr>
<td>Container</td>
<td>Gets the IContainer that contains the Component.<br />(Inherited from Component)</td></tr>
<tr>
<td>DesignMode</td>
<td>Gets a value that indicates whether the Component is currently in design mode.<br />(Inherited from Component)</td></tr>
<tr>
<td>Events</td>
<td>Gets the list of event handlers that are attached to this Component.<br />(Inherited from Component)</td></tr>
<tr>
<td><a href="41cec556-5107-1590-b409-6dd5a68b3544.md">InputControlPadding</a></td>
<td>Gets the input control padding needed to add a border to a borderless input control.<br />(Inherited from <a href="6da77fa5-1590-4646-f2ea-70002c922aee.md">PaletteBase</a>)</td></tr>
<tr>
<td>Site</td>
<td>Gets or sets the ISite of the Component.<br />(Inherited from Component)</td></tr>
<tr>
<td><a href="4729a43c-4f36-ffe2-e030-bd55b0232c3e.md">ThemeName</a></td>
<td>Gets or sets the name of the theme.<br />(Inherited from <a href="6da77fa5-1590-4646-f2ea-70002c922aee.md">PaletteBase</a>)</td></tr>
<tr>
<td><a href="0130f0f5-9443-3ec2-74bc-1af037e26783.md">UseKryptonFileDialogs</a></td>
<td>Gets or sets a value indicating whether [use krypton file dialogs].<br />(Inherited from <a href="6da77fa5-1590-4646-f2ea-70002c922aee.md">PaletteBase</a>)</td></tr>
</table>

## Methods
<table>
<tr>
<td><a href="94178b03-e4ed-8fe5-b955-999aefd200e2.md">DefineFonts</a></td>
<td>Update the fonts to reflect system or user defined changes.<br />(Inherited from <a href="6da77fa5-1590-4646-f2ea-70002c922aee.md">PaletteBase</a>)</td></tr>
<tr>
<td>Dispose()</td>
<td>Releases all resources used by the Component.<br />(Inherited from Component)</td></tr>
<tr>
<td>Dispose(Boolean)</td>
<td>Releases the unmanaged resources used by the Component and optionally releases the managed resources.<br />(Inherited from Component)</td></tr>
<tr>
<td><a href="ddaddf87-e1e8-59d8-3a48-e10d185ff698.md">DisposeFonts</a></td>
<td><br />(Inherited from <a href="6da77fa5-1590-4646-f2ea-70002c922aee.md">PaletteBase</a>)</td></tr>
<tr>
<td>Equals</td>
<td>Determines whether the specified object is equal to the current object.<br />(Inherited from Object)</td></tr>
<tr>
<td>Finalize</td>
<td>Releases unmanaged resources and performs other cleanup operations before the Component is reclaimed by garbage collection.<br />(Inherited from Component)</td></tr>
<tr>
<td><a href="1890d172-6bc6-faf1-9863-e6f262195176.md">GetAllowFormChrome</a></td>
<td>Gets a value indicating if KryptonForm instances should show custom chrome.<br />(Overrides <a href="f0826508-a608-dc87-2442-8debe708a2f3.md">PaletteBase.GetAllowFormChrome()</a>)</td></tr>
<tr>
<td><a href="2c3cc32f-1b01-1147-438e-432d6a98ebb7.md">GetBackColor1</a></td>
<td>Gets the first background color.<br />(Overrides <a href="cd675ae2-916a-4ea2-4045-0c75ef377a8d.md">PaletteBase.GetBackColor1(PaletteBackStyle, PaletteState)</a>)</td></tr>
<tr>
<td><a href="9ec7b700-c224-9ccf-730f-7289afee5497.md">GetBackColor2</a></td>
<td>Gets the second back color.<br />(Overrides <a href="3bfeea86-bc3b-38bf-1b32-d6cd8a658f86.md">PaletteBase.GetBackColor2(PaletteBackStyle, PaletteState)</a>)</td></tr>
<tr>
<td><a href="439cbca1-4c34-0be4-00bb-fe14c063015f.md">GetBackColorAlign</a></td>
<td>Gets the color alignment.<br />(Overrides <a href="35f0e232-c999-c9d2-41b2-4048e552319b.md">PaletteBase.GetBackColorAlign(PaletteBackStyle, PaletteState)</a>)</td></tr>
<tr>
<td><a href="387f3275-b8b8-11f5-a93c-2708e433f9e0.md">GetBackColorAngle</a></td>
<td>Gets the color background angle.<br />(Overrides <a href="67a98f57-0202-47d0-a751-11a70f70e2a2.md">PaletteBase.GetBackColorAngle(PaletteBackStyle, PaletteState)</a>)</td></tr>
<tr>
<td><a href="1095aedc-5f42-16f9-2b77-27bf4c4b6886.md">GetBackColorStyle</a></td>
<td>Gets the color background drawing style.<br />(Overrides <a href="97a51241-2681-131f-0420-e3f32b5ee94e.md">PaletteBase.GetBackColorStyle(PaletteBackStyle, PaletteState)</a>)</td></tr>
<tr>
<td><a href="00de2f93-6d8b-144f-cb5e-7c2f4e02cad9.md">GetBackDraw</a></td>
<td>Gets a value indicating if background should be drawn.<br />(Overrides <a href="2df43229-6399-1ec1-018a-6529b9301748.md">PaletteBase.GetBackDraw(PaletteBackStyle, PaletteState)</a>)</td></tr>
<tr>
<td><a href="7d51ec99-76f3-74be-eebc-3d4da4564bf6.md">GetBackGraphicsHint</a></td>
<td>Gets the graphics drawing hint for the background.<br />(Overrides <a href="c69f880d-d7e9-6ef9-797b-0bfb23886e4f.md">PaletteBase.GetBackGraphicsHint(PaletteBackStyle, PaletteState)</a>)</td></tr>
<tr>
<td><a href="1bc3af2b-f84b-e1bd-2a3d-e81a44b537a9.md">GetBackImage</a></td>
<td>Gets a background image.<br />(Overrides <a href="c28931d8-8575-448d-6255-ab8ac41a65e7.md">PaletteBase.GetBackImage(PaletteBackStyle, PaletteState)</a>)</td></tr>
<tr>
<td><a href="2ea8a656-2fb8-1d0c-76ce-6103ea0fc592.md">GetBackImageAlign</a></td>
<td>Gets the image alignment.<br />(Overrides <a href="7a131b0d-59a8-9d0d-30d2-83dfe6aefead.md">PaletteBase.GetBackImageAlign(PaletteBackStyle, PaletteState)</a>)</td></tr>
<tr>
<td><a href="ae2f138b-57c4-c594-5be8-39a087a290a3.md">GetBackImageStyle</a></td>
<td>Gets the background image style.<br />(Overrides <a href="25fba1c9-dc1d-3596-a41c-8e9bae9318f9.md">PaletteBase.GetBackImageStyle(PaletteBackStyle, PaletteState)</a>)</td></tr>
<tr>
<td><a href="de95d2a2-c5a1-678a-5740-894645b93f32.md">GetBorderColor1</a></td>
<td>Gets the first border color.<br />(Overrides <a href="3dafc59e-4d96-4976-c94d-6693bf460ef3.md">PaletteBase.GetBorderColor1(PaletteBorderStyle, PaletteState)</a>)</td></tr>
<tr>
<td><a href="8a36b7c0-2b0a-6019-93c6-bd196c5a674d.md">GetBorderColor2</a></td>
<td>Gets the second border color.<br />(Overrides <a href="98a68d43-8c1c-a40f-52ec-962268cfc648.md">PaletteBase.GetBorderColor2(PaletteBorderStyle, PaletteState)</a>)</td></tr>
<tr>
<td><a href="a0966682-8cf6-1264-0d53-52858acb8807.md">GetBorderColorAlign</a></td>
<td>Gets the color border alignment.<br />(Overrides <a href="3de63a53-cbc3-8395-1fc7-7a7891b7a62f.md">PaletteBase.GetBorderColorAlign(PaletteBorderStyle, PaletteState)</a>)</td></tr>
<tr>
<td><a href="380d0d7b-5cee-99c6-b7df-915b4cd00695.md">GetBorderColorAngle</a></td>
<td>Gets the color border angle.<br />(Overrides <a href="9041f671-3193-77f8-ca00-6a589435e904.md">PaletteBase.GetBorderColorAngle(PaletteBorderStyle, PaletteState)</a>)</td></tr>
<tr>
<td><a href="857c7744-f29a-f267-5bbe-4ade4136dfeb.md">GetBorderColorStyle</a></td>
<td>Gets the color border drawing style.<br />(Overrides <a href="799332fb-3119-a3f2-1998-355ac4b32d10.md">PaletteBase.GetBorderColorStyle(PaletteBorderStyle, PaletteState)</a>)</td></tr>
<tr>
<td><a href="6c20273b-ac7a-834c-24bd-b770d72ade20.md">GetBorderDraw</a></td>
<td>Gets a value indicating if border should be drawn.<br />(Overrides <a href="c7fe0c30-3948-4180-3922-b05fafadd37e.md">PaletteBase.GetBorderDraw(PaletteBorderStyle, PaletteState)</a>)</td></tr>
<tr>
<td><a href="cb8af8b4-f290-63b3-ac83-57eeb7514f41.md">GetBorderDrawBorders</a></td>
<td>Gets a value indicating which borders to draw.<br />(Overrides <a href="6e1c96e0-a241-949e-3bf0-836ea4baa76d.md">PaletteBase.GetBorderDrawBorders(PaletteBorderStyle, PaletteState)</a>)</td></tr>
<tr>
<td><a href="4295649d-9eec-a174-ee3f-1d5e9c88e179.md">GetBorderGraphicsHint</a></td>
<td>Gets the graphics drawing hint for the border.<br />(Overrides <a href="01f1b5d6-c360-3f05-7638-7ca70de08a58.md">PaletteBase.GetBorderGraphicsHint(PaletteBorderStyle, PaletteState)</a>)</td></tr>
<tr>
<td><a href="7e6d3c97-d421-5acc-9bbc-71029b8460fc.md">GetBorderImage</a></td>
<td>Gets a border image.<br />(Overrides <a href="e96e171d-0c37-0554-2000-3afc5b79e13d.md">PaletteBase.GetBorderImage(PaletteBorderStyle, PaletteState)</a>)</td></tr>
<tr>
<td><a href="23874734-3dca-68f5-e4f7-63c4c906b2bd.md">GetBorderImageAlign</a></td>
<td>Gets the image border alignment.<br />(Overrides <a href="1be81893-1f64-be1f-97a0-bab8d210a9b7.md">PaletteBase.GetBorderImageAlign(PaletteBorderStyle, PaletteState)</a>)</td></tr>
<tr>
<td><a href="a03d5b9b-4274-6606-6e3b-561f084c69d9.md">GetBorderImageStyle</a></td>
<td>Gets the border image style.<br />(Overrides <a href="3818a9b7-db38-a801-4b6e-948e1ca4066e.md">PaletteBase.GetBorderImageStyle(PaletteBorderStyle, PaletteState)</a>)</td></tr>
<tr>
<td><a href="83b768b1-448b-f9a0-52e6-8b2d5dfacf46.md">GetBorderRounding</a></td>
<td>Gets the border corner rounding.<br />(Overrides <a href="b7bf7664-d7bd-6723-72fc-eed140e6821e.md">PaletteBase.GetBorderRounding(PaletteBorderStyle, PaletteState)</a>)</td></tr>
<tr>
<td><a href="20669dab-4103-f757-017f-071feee17661.md">GetBorderWidth</a></td>
<td>Gets the border width.<br />(Overrides <a href="cec63de5-363e-1a98-b618-30f6d11a787b.md">PaletteBase.GetBorderWidth(PaletteBorderStyle, PaletteState)</a>)</td></tr>
<tr>
<td><a href="ef948861-bb30-be9d-099a-b3d25f7a846c.md">GetButtonSpecColorMap</a></td>
<td>Gets the color to remap from the image to the container foreground.<br />(Inherited from <a href="6da77fa5-1590-4646-f2ea-70002c922aee.md">PaletteBase</a>)</td></tr>
<tr>
<td><a href="ec3f2b82-8d55-6051-be77-fbff3b5722a4.md">GetButtonSpecColorTransparent</a></td>
<td>Gets the color to remap to transparent.<br />(Inherited from <a href="6da77fa5-1590-4646-f2ea-70002c922aee.md">PaletteBase</a>)</td></tr>
<tr>
<td><a href="d39e7a68-b554-de93-8449-7a395b0208a0.md">GetButtonSpecEdge</a></td>
<td>Gets the edge to position the button against.<br />(Inherited from <a href="6da77fa5-1590-4646-f2ea-70002c922aee.md">PaletteBase</a>)</td></tr>
<tr>
<td><a href="8e306522-e99e-2c59-fc78-c861e173551d.md">GetButtonSpecIcon</a></td>
<td>Gets the icon to display for the button.<br />(Inherited from <a href="6da77fa5-1590-4646-f2ea-70002c922aee.md">PaletteBase</a>)</td></tr>
<tr>
<td><a href="dfc94ff7-94a6-7bfd-9ca0-7a6f5b2581cf.md">GetButtonSpecImage</a></td>
<td>Gets the image to display for the button.<br />(Overrides <a href="d33fc993-0ad7-5b8e-4102-4183e92cd39d.md">PaletteBase.GetButtonSpecImage(PaletteButtonSpecStyle, PaletteState)</a>)</td></tr>
<tr>
<td><a href="c0a98302-ad36-12e7-e98c-14af03cd8029.md">GetButtonSpecImageTransparentColor</a></td>
<td>Gets the image transparent color.<br />(Inherited from <a href="6da77fa5-1590-4646-f2ea-70002c922aee.md">PaletteBase</a>)</td></tr>
<tr>
<td><a href="f5c285a3-49a2-dc1c-b4fc-9ea8d93ebdfe.md">GetButtonSpecLocation</a></td>
<td>Get the location for the button.<br />(Inherited from <a href="6da77fa5-1590-4646-f2ea-70002c922aee.md">PaletteBase</a>)</td></tr>
<tr>
<td><a href="fc25eae4-edec-3c21-dd64-8b26bb7701eb.md">GetButtonSpecLongText</a></td>
<td>Gets the long text to display for the button.<br />(Inherited from <a href="6da77fa5-1590-4646-f2ea-70002c922aee.md">PaletteBase</a>)</td></tr>
<tr>
<td><a href="dd05f779-4ca5-2151-e1f9-6c1908f12c95.md">GetButtonSpecOrientation</a></td>
<td>Gets the button orientation.<br />(Inherited from <a href="6da77fa5-1590-4646-f2ea-70002c922aee.md">PaletteBase</a>)</td></tr>
<tr>
<td><a href="b50fc667-8472-0a55-86af-58e426f55bdb.md">GetButtonSpecShortText</a></td>
<td>Gets the short text to display for the button.<br />(Inherited from <a href="6da77fa5-1590-4646-f2ea-70002c922aee.md">PaletteBase</a>)</td></tr>
<tr>
<td><a href="26412491-19fd-936e-6d0b-9f7a58df7161.md">GetButtonSpecStyle</a></td>
<td>Gets the button style used for drawing the button.<br />(Inherited from <a href="6da77fa5-1590-4646-f2ea-70002c922aee.md">PaletteBase</a>)</td></tr>
<tr>
<td><a href="dd864aac-a078-9f40-d05f-0232a568baba.md">GetButtonSpecToolTipTitle</a></td>
<td>Gets the tooltip title text to display for the button.<br />(Inherited from <a href="6da77fa5-1590-4646-f2ea-70002c922aee.md">PaletteBase</a>)</td></tr>
<tr>
<td><a href="21c7d1ff-04c0-5db7-630a-a6c76512d287.md">GetCheckBoxImage</a></td>
<td>Gets a check box image appropriate for the provided state.<br />(Overrides <a href="3d2ffbfb-fe3d-c91c-2ad2-5cf64576c2d7.md">PaletteBase.GetCheckBoxImage(Boolean, CheckState, Boolean, Boolean)</a>)</td></tr>
<tr>
<td><a href="fb14f33a-2e75-ce02-1c7e-a74aeead2cd8.md">GetContentAdjacentGap</a></td>
<td>Gets the padding between adjacent content items.<br />(Overrides <a href="51d4df74-8e98-8c74-00af-a0326997faf9.md">PaletteBase.GetContentAdjacentGap(PaletteContentStyle, PaletteState)</a>)</td></tr>
<tr>
<td><a href="39c148cc-270f-b466-6bd2-bfed1a8ea250.md">GetContentDraw</a></td>
<td>Gets a value indicating if content should be drawn.<br />(Overrides <a href="172382fc-3b12-1b0f-75e7-24a033bc7f9d.md">PaletteBase.GetContentDraw(PaletteContentStyle, PaletteState)</a>)</td></tr>
<tr>
<td><a href="01f27467-7999-fc96-8b82-d4666351e789.md">GetContentDrawFocus</a></td>
<td>Gets a value indicating if content should be drawn with focus indication.<br />(Overrides <a href="b7b32a72-da65-c802-9326-48212b3fa5dd.md">PaletteBase.GetContentDrawFocus(PaletteContentStyle, PaletteState)</a>)</td></tr>
<tr>
<td><a href="d32f2f5f-ecb7-35bd-3bab-f659a2afff4f.md">GetContentImageColorMap</a></td>
<td>Gets the image color to remap into another color.<br />(Overrides <a href="9b12866a-b465-1d52-4e94-23e4c033dc32.md">PaletteBase.GetContentImageColorMap(PaletteContentStyle, PaletteState)</a>)</td></tr>
<tr>
<td><a href="6c4905a6-98a7-b6de-543a-2a3cd484bf34.md">GetContentImageColorTo</a></td>
<td>Gets the color to use in place of the image map color.<br />(Overrides <a href="655e18c5-c002-d454-f528-8fb454194453.md">PaletteBase.GetContentImageColorTo(PaletteContentStyle, PaletteState)</a>)</td></tr>
<tr>
<td><a href="051c2f91-a1b0-30e0-7e82-4397745d3641.md">GetContentImageColorTransparent</a></td>
<td>Gets the image color that should be transparent.<br />(Overrides <a href="13460295-8685-bf4b-5968-c9412ffed5a5.md">PaletteBase.GetContentImageColorTransparent(PaletteContentStyle, PaletteState)</a>)</td></tr>
<tr>
<td><a href="04e1b040-b052-7a33-5cd4-34c813c390f4.md">GetContentImageEffect</a></td>
<td>Gets the effect applied to drawing of the image.<br />(Overrides <a href="dc7897e1-6324-d0e3-71c2-a6883cf65a11.md">PaletteBase.GetContentImageEffect(PaletteContentStyle, PaletteState)</a>)</td></tr>
<tr>
<td><a href="ed3436bc-13a4-d7cf-78ea-54375256fb89.md">GetContentImageH</a></td>
<td>Gets the horizontal relative alignment of the image.<br />(Overrides <a href="fb4ca3cf-7b37-bfc8-f601-90e41da5cd7e.md">PaletteBase.GetContentImageH(PaletteContentStyle, PaletteState)</a>)</td></tr>
<tr>
<td><a href="c5850fad-b5a5-7e71-3c4b-78abeac57fdb.md">GetContentImageV</a></td>
<td>Gets the vertical relative alignment of the image.<br />(Overrides <a href="31ad85a7-5b86-f773-7fa9-bc7ce2583e1b.md">PaletteBase.GetContentImageV(PaletteContentStyle, PaletteState)</a>)</td></tr>
<tr>
<td><a href="c51abee8-504b-015f-ae55-f80367e0c77a.md">GetContentLongTextColor1</a></td>
<td>Gets the first back color for the long text.<br />(Overrides <a href="d2c2a972-da08-716d-8cd1-98e44e7e3e33.md">PaletteBase.GetContentLongTextColor1(PaletteContentStyle, PaletteState)</a>)</td></tr>
<tr>
<td><a href="5d7dcb25-c30e-544f-c64e-900d8b9f7f38.md">GetContentLongTextColor2</a></td>
<td>Gets the second back color for the long text.<br />(Overrides <a href="cfeff8fc-6b67-2809-c2d4-fa2d8a421236.md">PaletteBase.GetContentLongTextColor2(PaletteContentStyle, PaletteState)</a>)</td></tr>
<tr>
<td><a href="c1192b34-72d2-e8b2-47a7-5a163aa0ae26.md">GetContentLongTextColorAlign</a></td>
<td>Gets the color alignment for the long text.<br />(Overrides <a href="a6d25592-c944-25bf-3294-29a0a154b9ab.md">PaletteBase.GetContentLongTextColorAlign(PaletteContentStyle, PaletteState)</a>)</td></tr>
<tr>
<td><a href="27c3b5f7-ad54-6e51-f793-316aeacb57d8.md">GetContentLongTextColorAngle</a></td>
<td>Gets the color background angle for the long text.<br />(Overrides <a href="d206727c-a058-5d20-5314-afc1196ee241.md">PaletteBase.GetContentLongTextColorAngle(PaletteContentStyle, PaletteState)</a>)</td></tr>
<tr>
<td><a href="1bded921-ef68-c7f0-55d8-01cfe60bcb6e.md">GetContentLongTextColorStyle</a></td>
<td>Gets the color drawing style for the long text.<br />(Overrides <a href="03de228d-3aec-8daa-17b7-268164489692.md">PaletteBase.GetContentLongTextColorStyle(PaletteContentStyle, PaletteState)</a>)</td></tr>
<tr>
<td><a href="4011ca5e-943e-0480-7607-6aa8f4456a22.md">GetContentLongTextFont</a></td>
<td>Gets the font for the long text.<br />(Overrides <a href="e5e00bb2-5737-294f-f741-55c391e3abcf.md">PaletteBase.GetContentLongTextFont(PaletteContentStyle, PaletteState)</a>)</td></tr>
<tr>
<td><a href="75c625ed-e3f6-4e3b-6369-75f43dcfc906.md">GetContentLongTextH</a></td>
<td>Gets the horizontal relative alignment of the long text.<br />(Overrides <a href="dec88b79-ee05-16b0-27a1-3aa8ae63a683.md">PaletteBase.GetContentLongTextH(PaletteContentStyle, PaletteState)</a>)</td></tr>
<tr>
<td><a href="8eedf1ab-30c0-fedb-6d5e-57bd68282d35.md">GetContentLongTextHint</a></td>
<td>Gets the rendering hint for the long text.<br />(Overrides <a href="95ab15ea-f22b-d1b8-e61c-f6fea4d0356e.md">PaletteBase.GetContentLongTextHint(PaletteContentStyle, PaletteState)</a>)</td></tr>
<tr>
<td><a href="acb6abd0-3f1c-b386-7525-021426a3b77e.md">GetContentLongTextImage</a></td>
<td>Gets a background image for the long text.<br />(Overrides <a href="1c90dd4f-2e77-0648-059b-5c3c8294c35d.md">PaletteBase.GetContentLongTextImage(PaletteContentStyle, PaletteState)</a>)</td></tr>
<tr>
<td><a href="6a9345c1-5022-535f-fc88-60a4519c091d.md">GetContentLongTextImageAlign</a></td>
<td>Gets the image alignment for the long text.<br />(Overrides <a href="4c3ab5f8-4b02-d815-edac-26e0348174b3.md">PaletteBase.GetContentLongTextImageAlign(PaletteContentStyle, PaletteState)</a>)</td></tr>
<tr>
<td><a href="7bf53922-93e9-fd42-9831-21d705e49ad4.md">GetContentLongTextImageStyle</a></td>
<td>Gets the background image style for the long text.<br />(Overrides <a href="9ebf895c-8518-b551-4cec-1432187d0eb5.md">PaletteBase.GetContentLongTextImageStyle(PaletteContentStyle, PaletteState)</a>)</td></tr>
<tr>
<td><a href="cc7cb610-6ee0-b70c-a89e-806ab0560bbf.md">GetContentLongTextMultiLine</a></td>
<td>Gets the flag indicating if multiline text is allowed for long text.<br />(Overrides <a href="e3434bd5-4124-f979-b805-da1f88ff94aa.md">PaletteBase.GetContentLongTextMultiLine(PaletteContentStyle, PaletteState)</a>)</td></tr>
<tr>
<td><a href="86bf9de2-73d5-d9cc-9a25-3eac2056bd43.md">GetContentLongTextMultiLineH</a></td>
<td>Gets the horizontal relative alignment of multiline long text.<br />(Overrides <a href="87772071-b167-cf88-01be-0928723a9e00.md">PaletteBase.GetContentLongTextMultiLineH(PaletteContentStyle, PaletteState)</a>)</td></tr>
<tr>
<td><a href="2dd890ee-9c00-a410-1bd0-9d654faaa2ad.md">GetContentLongTextNewFont</a></td>
<td>Gets the font for the long text by generating a new font instance.<br />(Overrides <a href="d93fb034-9bf5-e8b5-2081-80a73a612be4.md">PaletteBase.GetContentLongTextNewFont(PaletteContentStyle, PaletteState)</a>)</td></tr>
<tr>
<td><a href="5a4876c2-56ae-a5d8-21a9-f3e27c362d34.md">GetContentLongTextPrefix</a></td>
<td>Gets the prefix drawing setting for long text.<br />(Overrides <a href="b4464b21-9e5e-3f52-7daf-8c3cee9e7299.md">PaletteBase.GetContentLongTextPrefix(PaletteContentStyle, PaletteState)</a>)</td></tr>
<tr>
<td><a href="3409960b-9036-ae3d-adc2-5734be628de1.md">GetContentLongTextTrim</a></td>
<td>Gets the text trimming to use for long text.<br />(Overrides <a href="19ff4fa9-94e1-ead1-063a-d2e9d4ae406a.md">PaletteBase.GetContentLongTextTrim(PaletteContentStyle, PaletteState)</a>)</td></tr>
<tr>
<td><a href="85f480e0-2452-1bdd-7b82-f7f9526301b4.md">GetContentLongTextV</a></td>
<td>Gets the vertical relative alignment of the long text.<br />(Overrides <a href="6b4d6c07-b04e-4810-8575-a862ea5cad88.md">PaletteBase.GetContentLongTextV(PaletteContentStyle, PaletteState)</a>)</td></tr>
<tr>
<td><a href="15169d39-2cb2-769b-9005-1cccf986bc55.md">GetContentPadding</a></td>
<td>Gets the padding between the border and content drawing.<br />(Overrides <a href="433c1b92-972a-ad88-ba91-edd47bfd5849.md">PaletteBase.GetContentPadding(PaletteContentStyle, PaletteState)</a>)</td></tr>
<tr>
<td><a href="df8940b3-6158-b0ec-d478-b202721dcd99.md">GetContentShortTextColor1</a></td>
<td>Gets the first back color for the short text.<br />(Overrides <a href="36377bbc-ec7a-ebb6-584e-d4f1f9d8b3f9.md">PaletteBase.GetContentShortTextColor1(PaletteContentStyle, PaletteState)</a>)</td></tr>
<tr>
<td><a href="8e676ec5-939a-3293-60cb-81f50613f47a.md">GetContentShortTextColor2</a></td>
<td>Gets the second back color for the short text.<br />(Overrides <a href="54740aa3-7959-8d49-fdd3-d572cdba2c12.md">PaletteBase.GetContentShortTextColor2(PaletteContentStyle, PaletteState)</a>)</td></tr>
<tr>
<td><a href="8424da28-5844-88c2-58dd-32bdd66b8866.md">GetContentShortTextColorAlign</a></td>
<td>Gets the color alignment for the short text.<br />(Overrides <a href="dd4e52ff-5675-6c65-ec87-949abc3fd909.md">PaletteBase.GetContentShortTextColorAlign(PaletteContentStyle, PaletteState)</a>)</td></tr>
<tr>
<td><a href="bb9b6e14-6a35-bc03-d29c-5314fb3ab463.md">GetContentShortTextColorAngle</a></td>
<td>Gets the color background angle for the short text.<br />(Overrides <a href="e99e21fe-09b5-048e-f646-6a4a9df1b6d9.md">PaletteBase.GetContentShortTextColorAngle(PaletteContentStyle, PaletteState)</a>)</td></tr>
<tr>
<td><a href="b67a0681-1be0-3084-bc1d-58d5d2e8f46b.md">GetContentShortTextColorStyle</a></td>
<td>Gets the color drawing style for the short text.<br />(Overrides <a href="7bf6a6d7-e559-c66b-303b-7f857d34781c.md">PaletteBase.GetContentShortTextColorStyle(PaletteContentStyle, PaletteState)</a>)</td></tr>
<tr>
<td><a href="5527bba1-e4dc-1598-d7e5-b88d28b5b230.md">GetContentShortTextFont</a></td>
<td>Gets the font for the short text.<br />(Overrides <a href="a788414c-9a0c-cb5a-1356-0d90b40614d0.md">PaletteBase.GetContentShortTextFont(PaletteContentStyle, PaletteState)</a>)</td></tr>
<tr>
<td><a href="c4139400-723e-2a05-a7bf-c84efe43d9fd.md">GetContentShortTextH</a></td>
<td>Gets the horizontal relative alignment of the short text.<br />(Overrides <a href="8b04266e-e8c9-0c64-ed2d-5576332eaf84.md">PaletteBase.GetContentShortTextH(PaletteContentStyle, PaletteState)</a>)</td></tr>
<tr>
<td><a href="13aaed40-277e-4b64-02e9-fb17bf8eeecd.md">GetContentShortTextHint</a></td>
<td>Gets the rendering hint for the short text.<br />(Overrides <a href="2c4cc351-4897-d352-3b58-154562667934.md">PaletteBase.GetContentShortTextHint(PaletteContentStyle, PaletteState)</a>)</td></tr>
<tr>
<td><a href="d2409dd3-a1d5-4324-5106-8154cf0620e2.md">GetContentShortTextImage</a></td>
<td>Gets a background image for the short text.<br />(Overrides <a href="22e5536c-d880-cf85-6038-a02d71dee664.md">PaletteBase.GetContentShortTextImage(PaletteContentStyle, PaletteState)</a>)</td></tr>
<tr>
<td><a href="4b6615b4-d339-82f4-32d5-0ce3cf28257d.md">GetContentShortTextImageAlign</a></td>
<td>Gets the image alignment for the short text.<br />(Overrides <a href="3171f046-2022-a94a-d41f-2a31c1aa99fc.md">PaletteBase.GetContentShortTextImageAlign(PaletteContentStyle, PaletteState)</a>)</td></tr>
<tr>
<td><a href="b04a7d6a-e2a5-8aa9-99ad-26302438a1c5.md">GetContentShortTextImageStyle</a></td>
<td>Gets the background image style.<br />(Overrides <a href="c6cefb7b-1c0a-1fc6-6f9b-e60ab3145e9f.md">PaletteBase.GetContentShortTextImageStyle(PaletteContentStyle, PaletteState)</a>)</td></tr>
<tr>
<td><a href="00171b9a-c92f-832b-ca7d-7d79f7d15880.md">GetContentShortTextMultiLine</a></td>
<td>Gets the flag indicating if multiline text is allowed for short text.<br />(Overrides <a href="0bdb21ef-3838-c4ef-58c3-7b5addbd8b08.md">PaletteBase.GetContentShortTextMultiLine(PaletteContentStyle, PaletteState)</a>)</td></tr>
<tr>
<td><a href="d19b9d48-e0e3-4747-73ef-ca6a1c96fa49.md">GetContentShortTextMultiLineH</a></td>
<td>Gets the horizontal relative alignment of multiline short text.<br />(Overrides <a href="8b91956d-9e25-b12d-ba1e-929eeb7f44a5.md">PaletteBase.GetContentShortTextMultiLineH(PaletteContentStyle, PaletteState)</a>)</td></tr>
<tr>
<td><a href="541be95e-ce16-3f44-f4cc-8cc0274dd557.md">GetContentShortTextNewFont</a></td>
<td>Gets the font for the short text by generating a new font instance.<br />(Overrides <a href="529449d0-4320-7e36-d4a9-8b56e152d877.md">PaletteBase.GetContentShortTextNewFont(PaletteContentStyle, PaletteState)</a>)</td></tr>
<tr>
<td><a href="c5b7db20-ae96-dc5c-18bd-33d68a5dbb5d.md">GetContentShortTextPrefix</a></td>
<td>Gets the prefix drawing setting for short text.<br />(Overrides <a href="1aedb00d-5ab3-0e47-3183-97c7cbe531c7.md">PaletteBase.GetContentShortTextPrefix(PaletteContentStyle, PaletteState)</a>)</td></tr>
<tr>
<td><a href="9de3b7f3-543b-a046-62ec-da3ee7e2babc.md">GetContentShortTextTrim</a></td>
<td>Gets the text trimming to use for short text.<br />(Overrides <a href="8a11b199-6870-b468-e3b6-4de6e397cbd4.md">PaletteBase.GetContentShortTextTrim(PaletteContentStyle, PaletteState)</a>)</td></tr>
<tr>
<td><a href="783f6ced-218b-ee6b-6cd1-d77d79e8bf7e.md">GetContentShortTextV</a></td>
<td>Gets the vertical relative alignment of the short text.<br />(Overrides <a href="673572d4-c8b6-067b-d460-d460c2dd26ba.md">PaletteBase.GetContentShortTextV(PaletteContentStyle, PaletteState)</a>)</td></tr>
<tr>
<td><a href="a47359dc-8f38-83a1-5961-d2c693a5f1e0.md">GetContextMenuCheckedImage</a></td>
<td>Gets a checked image appropriate for a context menu item.<br />(Overrides <a href="77a42003-7b20-304b-f19b-45757658eb69.md">PaletteBase.GetContextMenuCheckedImage()</a>)</td></tr>
<tr>
<td><a href="312a2e1d-5d22-4675-e8ac-52b219ee1b85.md">GetContextMenuIndeterminateImage</a></td>
<td>Gets a indeterminate image appropriate for a context menu item.<br />(Overrides <a href="f5591a04-45b8-9c3d-32dc-ee89b3141c27.md">PaletteBase.GetContextMenuIndeterminateImage()</a>)</td></tr>
<tr>
<td><a href="2b77d6ee-795d-d47d-e14d-fb330d5c2c8d.md">GetContextMenuSubMenuImage</a></td>
<td>Gets an image indicating a sub-menu on a context menu item.<br />(Inherited from <a href="6da77fa5-1590-4646-f2ea-70002c922aee.md">PaletteBase</a>)</td></tr>
<tr>
<td><a href="d09f7f10-d17c-54a8-520f-5518cf940220.md">GetDragDropDockActive</a></td>
<td>Gets the active color for docking indicators.<br />(Inherited from <a href="6da77fa5-1590-4646-f2ea-70002c922aee.md">PaletteBase</a>)</td></tr>
<tr>
<td><a href="61722bb2-6a1e-540d-a999-264e95040228.md">GetDragDropDockBack</a></td>
<td>Gets the background color for the docking indicators area.<br />(Inherited from <a href="6da77fa5-1590-4646-f2ea-70002c922aee.md">PaletteBase</a>)</td></tr>
<tr>
<td><a href="01e30487-ad49-e43f-f717-8fa395e8bbb7.md">GetDragDropDockBorder</a></td>
<td>Gets the border color for the docking indicators area.<br />(Inherited from <a href="6da77fa5-1590-4646-f2ea-70002c922aee.md">PaletteBase</a>)</td></tr>
<tr>
<td><a href="2feefe8d-989c-695f-9262-15a9e26a9541.md">GetDragDropDockInactive</a></td>
<td>Gets the inactive color for docking indicators.<br />(Inherited from <a href="6da77fa5-1590-4646-f2ea-70002c922aee.md">PaletteBase</a>)</td></tr>
<tr>
<td><a href="ce9d2077-0412-81bc-0976-d64aa48158ca.md">GetDragDropFeedback</a></td>
<td>Gets the feedback drawing method used.<br />(Inherited from <a href="6da77fa5-1590-4646-f2ea-70002c922aee.md">PaletteBase</a>)</td></tr>
<tr>
<td><a href="9e963a4a-cde6-21a8-e127-2b4ba0cb017b.md">GetDragDropSolidBack</a></td>
<td>Gets the background color for a solid drag drop area.<br />(Inherited from <a href="6da77fa5-1590-4646-f2ea-70002c922aee.md">PaletteBase</a>)</td></tr>
<tr>
<td><a href="97356158-90b3-a5a2-1a57-bc668e50140c.md">GetDragDropSolidBorder</a></td>
<td>Gets the border color for a solid drag drop area.<br />(Inherited from <a href="6da77fa5-1590-4646-f2ea-70002c922aee.md">PaletteBase</a>)</td></tr>
<tr>
<td><a href="399cee9a-5080-a5ae-b4ae-39338ac50ea4.md">GetDragDropSolidOpacity</a></td>
<td>Gets the opacity of the solid area.<br />(Inherited from <a href="6da77fa5-1590-4646-f2ea-70002c922aee.md">PaletteBase</a>)</td></tr>
<tr>
<td><a href="1030065a-5045-00d5-726a-dc801f5896e9.md">GetDropDownButtonImage</a></td>
<td>Gets a drop down button image appropriate for the provided state.<br />(Overrides <a href="1f18af5b-869b-6fab-e6b4-95fedaa9e62b.md">PaletteBase.GetDropDownButtonImage(PaletteState)</a>)</td></tr>
<tr>
<td><a href="1ece4f0b-7c3e-38ca-a3ff-c612c95db29b.md">GetElementColor1</a></td>
<td>Gets the first element color.<br />(Overrides <a href="4ca7336c-78d7-0500-cf1b-41c9aeb6cc3a.md">PaletteBase.GetElementColor1(PaletteElement, PaletteState)</a>)</td></tr>
<tr>
<td><a href="d38a8c9a-98ba-5d3e-8558-7aeac876c267.md">GetElementColor2</a></td>
<td>Gets the second element color.<br />(Overrides <a href="ab6e4ac1-b341-acdc-9ff0-c1eb083061f3.md">PaletteBase.GetElementColor2(PaletteElement, PaletteState)</a>)</td></tr>
<tr>
<td><a href="77916507-a38a-9e98-1e04-3311e2a3b708.md">GetElementColor3</a></td>
<td>Gets the third element color.<br />(Overrides <a href="4429f5ea-70d5-61a0-0b65-33e9b4933823.md">PaletteBase.GetElementColor3(PaletteElement, PaletteState)</a>)</td></tr>
<tr>
<td><a href="5d42fc08-93a4-430e-ffcf-d987b333fce9.md">GetElementColor4</a></td>
<td>Gets the fourth element color.<br />(Overrides <a href="fbe433f7-f00a-be34-bcce-c175f092e83e.md">PaletteBase.GetElementColor4(PaletteElement, PaletteState)</a>)</td></tr>
<tr>
<td><a href="348ee756-eb28-8437-4428-d63b71527449.md">GetElementColor5</a></td>
<td>Gets the fifth element color.<br />(Overrides <a href="ef750d81-2486-0372-e420-cadece659ee0.md">PaletteBase.GetElementColor5(PaletteElement, PaletteState)</a>)</td></tr>
<tr>
<td><a href="77f6a818-fc96-4992-d4f9-a196012f4718.md">GetGalleryButtonImage</a></td>
<td>Gets a check box image appropriate for the provided state.<br />(Overrides <a href="aa53ce85-28b2-27cd-0cb7-853504c4cda6.md">PaletteBase.GetGalleryButtonImage(PaletteRibbonGalleryButton, PaletteState)</a>)</td></tr>
<tr>
<td>GetHashCode</td>
<td>Serves as the default hash function.<br />(Inherited from Object)</td></tr>
<tr>
<td>GetLifetimeService</td>
<td>Retrieves the current lifetime service object that controls the lifetime policy for this instance.<br />(Inherited from MarshalByRefObject)<br /><strong>Obsolete.</strong></td></tr>
<tr>
<td><a href="025cce4e-84d4-c432-2318-57838a114c27.md">GetMetricBool</a></td>
<td>Gets a boolean metric value.<br />(Overrides <a href="1002c35a-da1a-f739-23f2-42558745509d.md">PaletteBase.GetMetricBool(PaletteState, PaletteMetricBool)</a>)</td></tr>
<tr>
<td><a href="2c87c56e-f9f2-c09b-951a-ef5a7ce923d1.md">GetMetricInt</a></td>
<td>Gets an integer metric value.<br />(Overrides <a href="00d41543-cdf1-2164-f20f-604e9be58e54.md">PaletteBase.GetMetricInt(PaletteState, PaletteMetricInt)</a>)</td></tr>
<tr>
<td><a href="eaa04c4f-1aad-ae06-fa0d-46ca27569322.md">GetMetricPadding</a></td>
<td>Gets a padding metric value.<br />(Overrides <a href="f1bf12bc-129b-c8c7-81be-5940b46cd46d.md">PaletteBase.GetMetricPadding(PaletteState, PaletteMetricPadding)</a>)</td></tr>
<tr>
<td><a href="3784ac85-28a8-9f87-f0c4-f91d44277469.md">GetRadioButtonImage</a></td>
<td>Gets a check box image appropriate for the provided state.<br />(Overrides <a href="936bd2d3-7269-e6cb-dc5b-79c39a80cc3b.md">PaletteBase.GetRadioButtonImage(Boolean, Boolean, Boolean, Boolean)</a>)</td></tr>
<tr>
<td><a href="24ac2e32-708f-22e5-f607-77d7fc24ca35.md">GetRenderer</a></td>
<td>Gets the renderer to use for this palette.<br />(Overrides <a href="08e680cb-366c-4029-7be4-4ed5024659fa.md">PaletteBase.GetRenderer()</a>)</td></tr>
<tr>
<td><a href="36d08cea-7350-a5af-8541-2ff63699a1c1.md">GetRibbonBackColor1</a></td>
<td>Gets the first background color for the ribbon item.<br />(Overrides <a href="4dc81f67-981e-2630-0507-07f6979117e5.md">PaletteBase.GetRibbonBackColor1(PaletteRibbonBackStyle, PaletteState)</a>)</td></tr>
<tr>
<td><a href="4a84c84a-d335-66d6-4bbd-f70c82b3f685.md">GetRibbonBackColor2</a></td>
<td>Gets the second background color for the ribbon item.<br />(Overrides <a href="f8677d2a-c69c-0ed9-8701-d550b8c9d39a.md">PaletteBase.GetRibbonBackColor2(PaletteRibbonBackStyle, PaletteState)</a>)</td></tr>
<tr>
<td><a href="340ea143-516a-116e-096a-2df9b703bf10.md">GetRibbonBackColor3</a></td>
<td>Gets the third background color for the ribbon item.<br />(Overrides <a href="58805344-6a2c-d388-0f24-ccf18f57027e.md">PaletteBase.GetRibbonBackColor3(PaletteRibbonBackStyle, PaletteState)</a>)</td></tr>
<tr>
<td><a href="fa406a8c-27a2-6a66-cf9c-11f489e1d0d4.md">GetRibbonBackColor4</a></td>
<td>Gets the fourth background color for the ribbon item.<br />(Overrides <a href="04a8146f-7b23-63ed-7df3-6ef0e692008d.md">PaletteBase.GetRibbonBackColor4(PaletteRibbonBackStyle, PaletteState)</a>)</td></tr>
<tr>
<td><a href="7be0cae5-ed84-4b62-6ce1-e6b7bc25d97b.md">GetRibbonBackColor5</a></td>
<td>Gets the fifth background color for the ribbon item.<br />(Overrides <a href="bf928261-f6f9-918e-eeed-16024f4a8006.md">PaletteBase.GetRibbonBackColor5(PaletteRibbonBackStyle, PaletteState)</a>)</td></tr>
<tr>
<td><a href="aa319b13-aee4-117c-012d-4c502e714c66.md">GetRibbonBackColorStyle</a></td>
<td>Gets the method used to draw the background of a ribbon item.<br />(Overrides <a href="e1cd9587-d1d2-b057-0916-8530be27d4fc.md">PaletteBase.GetRibbonBackColorStyle(PaletteRibbonBackStyle, PaletteState)</a>)</td></tr>
<tr>
<td><a href="8605fcc1-1967-810c-db19-0f8d7b792906.md">GetRibbonContextTextAlign</a></td>
<td>Gets the text alignment for the ribbon context text.<br />(Overrides <a href="27ac4c79-8e4e-8e75-6506-01faa84eef13.md">PaletteBase.GetRibbonContextTextAlign(PaletteState)</a>)</td></tr>
<tr>
<td><a href="350c1c94-ce82-2580-6c00-cec333c25cf0.md">GetRibbonContextTextColor</a></td>
<td>Gets the color for the ribbon context text.<br />(Overrides <a href="303696ef-5f38-f900-2790-7f6792a8ec92.md">PaletteBase.GetRibbonContextTextColor(PaletteState)</a>)</td></tr>
<tr>
<td><a href="b276ee65-00d2-9620-2b2f-761a5a622bff.md">GetRibbonContextTextFont</a></td>
<td>Gets the font for the ribbon context text.<br />(Overrides <a href="e18088f7-65d6-9543-6bf3-74e7c1d46247.md">PaletteBase.GetRibbonContextTextFont(PaletteState)</a>)</td></tr>
<tr>
<td><a href="40740f52-8b4f-1f35-c5ba-7f9d5cd41ec8.md">GetRibbonDisabledDark</a></td>
<td>Gets the dark disabled color used for ribbon glyphs.<br />(Overrides <a href="7deef2a0-a126-37da-b7ba-d24bc5374e92.md">PaletteBase.GetRibbonDisabledDark(PaletteState)</a>)</td></tr>
<tr>
<td><a href="ef507810-bc2b-1322-8a9a-c2656757d734.md">GetRibbonDisabledLight</a></td>
<td>Gets the light disabled color used for ribbon glyphs.<br />(Overrides <a href="43a28d16-9481-30ab-60e8-ed0be282b3c7.md">PaletteBase.GetRibbonDisabledLight(PaletteState)</a>)</td></tr>
<tr>
<td><a href="5716c351-26cc-85a1-7886-43d37a680793.md">GetRibbonDropArrowDark</a></td>
<td>Gets the color for the drop arrow dark.<br />(Overrides <a href="0db7ee0e-1da9-2c83-9aca-00f9d7ff13b4.md">PaletteBase.GetRibbonDropArrowDark(PaletteState)</a>)</td></tr>
<tr>
<td><a href="efca09e1-a2c4-de85-04c4-bcad319411a7.md">GetRibbonDropArrowLight</a></td>
<td>Gets the color for the drop arrow light.<br />(Overrides <a href="4950dee8-18da-fcd1-0ee5-6300b7e5d369.md">PaletteBase.GetRibbonDropArrowLight(PaletteState)</a>)</td></tr>
<tr>
<td><a href="51567874-f954-2d40-f6b0-c4cb75003e53.md">GetRibbonGroupDialogDark</a></td>
<td>Gets the color for the dialog launcher dark.<br />(Overrides <a href="58999f28-3724-ede8-f807-920bde54e88e.md">PaletteBase.GetRibbonGroupDialogDark(PaletteState)</a>)</td></tr>
<tr>
<td><a href="30022fa8-ee0a-e67b-ba3a-337a80fc6b36.md">GetRibbonGroupDialogLight</a></td>
<td>Gets the color for the dialog launcher light.<br />(Overrides <a href="98c4fc1d-3a79-1626-66b5-790968b55a39.md">PaletteBase.GetRibbonGroupDialogLight(PaletteState)</a>)</td></tr>
<tr>
<td><a href="60d29790-253a-6f69-9b79-d74d15b7c0fc.md">GetRibbonGroupSeparatorDark</a></td>
<td>Gets the color for the group separator dark.<br />(Overrides <a href="5871693c-7aef-7cd7-fb07-3b207da0b487.md">PaletteBase.GetRibbonGroupSeparatorDark(PaletteState)</a>)</td></tr>
<tr>
<td><a href="c62255de-3643-8ca6-d71a-d05d5a01f4bd.md">GetRibbonGroupSeparatorLight</a></td>
<td>Gets the color for the group separator light.<br />(Overrides <a href="12023439-3efe-a48c-0c1e-1d3945dc9e7a.md">PaletteBase.GetRibbonGroupSeparatorLight(PaletteState)</a>)</td></tr>
<tr>
<td><a href="295cad9d-e6f8-0d9c-5850-0b57ab5a34ee.md">GetRibbonMinimizeBarDark</a></td>
<td>Gets the color for the minimize bar dark.<br />(Overrides <a href="81d37bc1-034e-b9b5-c8d8-f81e3a77e454.md">PaletteBase.GetRibbonMinimizeBarDark(PaletteState)</a>)</td></tr>
<tr>
<td><a href="dbb4a530-74d2-3732-17cd-657a197f25b1.md">GetRibbonMinimizeBarLight</a></td>
<td>Gets the color for the minimize bar light.<br />(Overrides <a href="6604501a-f469-9521-048b-e2a4569d0b1c.md">PaletteBase.GetRibbonMinimizeBarLight(PaletteState)</a>)</td></tr>
<tr>
<td><a href="7cedf622-1532-b768-f4e3-bba3b06633f7.md">GetRibbonQATButtonDark</a></td>
<td>Gets the color for the extra QAT button dark content color.<br />(Overrides <a href="2866b2df-c79c-f93d-0b4b-abac0ca6a106.md">PaletteBase.GetRibbonQATButtonDark(PaletteState)</a>)</td></tr>
<tr>
<td><a href="1e838c49-5e16-7397-7d6b-bf657f7e1a69.md">GetRibbonQATButtonLight</a></td>
<td>Gets the color for the extra QAT button light content color.<br />(Overrides <a href="c5d4ea60-cff4-7ce3-1889-5443d74117e7.md">PaletteBase.GetRibbonQATButtonLight(PaletteState)</a>)</td></tr>
<tr>
<td><a href="c8424731-4cd4-1b2a-7afc-f343c55e33eb.md">GetRibbonShape</a></td>
<td>Gets the ribbon shape that should be used.<br />(Overrides <a href="99c5bb3e-21ea-904c-b21e-f82c997cfed9.md">PaletteBase.GetRibbonShape()</a>)</td></tr>
<tr>
<td><a href="c659919c-b195-3119-44a0-0ca920289d32.md">GetRibbonTabSeparatorColor</a></td>
<td>Gets the color for the tab separator.<br />(Overrides <a href="a1cdc46d-2281-b98a-361c-518a19b2d893.md">PaletteBase.GetRibbonTabSeparatorColor(PaletteState)</a>)</td></tr>
<tr>
<td><a href="f04ce910-b557-ea30-a5b3-f2ac14cb8179.md">GetRibbonTabSeparatorContextColor</a></td>
<td>Gets the color for the tab context separators.<br />(Overrides <a href="5ffb4aba-e2aa-9763-c39f-01a7da490410.md">PaletteBase.GetRibbonTabSeparatorContextColor(PaletteState)</a>)</td></tr>
<tr>
<td><a href="ca1da77e-4395-1690-d9c7-fbdaefa31e28.md">GetRibbonTextColor</a></td>
<td>Gets the =color for the item text.<br />(Overrides <a href="90b34fe5-5027-4d63-d258-473007fa289e.md">PaletteBase.GetRibbonTextColor(PaletteRibbonTextStyle, PaletteState)</a>)</td></tr>
<tr>
<td><a href="cbffeb36-085a-8ab2-fa17-7ba8b4a1b0c1.md">GetRibbonTextFont</a></td>
<td>Gets the font for the ribbon text.<br />(Overrides <a href="b686f934-0810-1dc9-91c2-b74c644f1f20.md">PaletteBase.GetRibbonTextFont(PaletteState)</a>)</td></tr>
<tr>
<td><a href="f57561a9-cb22-886e-fc4f-d070a892bab8.md">GetRibbonTextHint</a></td>
<td>Gets the rendering hint for the ribbon font.<br />(Overrides <a href="030741c0-972b-40f8-9dd5-51a0ad06cfa1.md">PaletteBase.GetRibbonTextHint(PaletteState)</a>)</td></tr>
<tr>
<td>GetService</td>
<td>Returns an object that represents a service provided by the Component or by its Container.<br />(Inherited from Component)</td></tr>
<tr>
<td><a href="d48531e6-e299-1ba7-ec17-e1b3ede7acd2.md">GetTreeViewImage</a></td>
<td>Gets a tree view image appropriate for the provided state.<br />(Overrides <a href="945ef50d-0293-a198-f5af-b7b5a348f45a.md">PaletteBase.GetTreeViewImage(Boolean)</a>)</td></tr>
<tr>
<td>GetType</td>
<td>Gets the Type of the current instance.<br />(Inherited from Object)</td></tr>
<tr>
<td>InitializeLifetimeService</td>
<td>Obtains a lifetime service object to control the lifetime policy for this instance.<br />(Inherited from MarshalByRefObject)<br /><strong>Obsolete.</strong></td></tr>
<tr>
<td>MemberwiseClone()</td>
<td>Creates a shallow copy of the current Object.<br />(Inherited from Object)</td></tr>
<tr>
<td>MemberwiseClone(Boolean)</td>
<td>Creates a shallow copy of the current MarshalByRefObject object.<br />(Inherited from MarshalByRefObject)</td></tr>
<tr>
<td><a href="fc1dda96-32ee-fd9e-347f-614e5a355826.md">OnAllowFormChromeChanged</a></td>
<td>Raises the AllowFormChromeChanged event.<br />(Inherited from <a href="6da77fa5-1590-4646-f2ea-70002c922aee.md">PaletteBase</a>)</td></tr>
<tr>
<td><a href="edac6247-2caf-0f34-291f-905a750e9cf9.md">OnBasePaletteChanged</a></td>
<td>Raises the BasePaletteChanged event.<br />(Inherited from <a href="6da77fa5-1590-4646-f2ea-70002c922aee.md">PaletteBase</a>)</td></tr>
<tr>
<td><a href="3e430758-0f07-b362-dc14-ddf812f4ba99.md">OnBaseRendererChanged</a></td>
<td>Raises the BaseRendererChanged event.<br />(Inherited from <a href="6da77fa5-1590-4646-f2ea-70002c922aee.md">PaletteBase</a>)</td></tr>
<tr>
<td><a href="1c2e0ca2-ebff-eb9b-426f-152e3d9c3b1e.md">OnButtonSpecChanged</a></td>
<td>Raises the ButtonSpecChanged event.<br />(Inherited from <a href="6da77fa5-1590-4646-f2ea-70002c922aee.md">PaletteBase</a>)</td></tr>
<tr>
<td><a href="064ecef4-b34e-931e-d159-a7e583a64d17.md">OnPalettePaint</a></td>
<td>Raises the PalettePaint event.<br />(Inherited from <a href="6da77fa5-1590-4646-f2ea-70002c922aee.md">PaletteBase</a>)</td></tr>
<tr>
<td><a href="b705b1e4-f111-1b13-2131-e2dd398591f1.md">OnUserPreferenceChanged</a></td>
<td>Handle a change in the user preferences.<br />(Overrides <a href="c2be628c-21ef-9b21-c557-a77cf7921882.md">PaletteBase.OnUserPreferenceChanged(Object, UserPreferenceChangedEventArgs)</a>)</td></tr>
<tr>
<td>ToString</td>
<td>Returns a String containing the name of the Component, if any. This method should not be overridden.<br />(Inherited from Component)</td></tr>
<tr>
<td><a href="fba2d295-02d5-067a-362a-1228c9d2838a.md">UserPreferenceChanged</a></td>
<td><br />(Inherited from <a href="6da77fa5-1590-4646-f2ea-70002c922aee.md">PaletteBase</a>)</td></tr>
</table>

## Events
<table>
<tr>
<td><a href="9776065a-5cf2-33aa-ac96-1702838579a2.md">AllowFormChromeChanged</a></td>
<td>Occurs when the AllowFormChrome setting changes.<br />(Inherited from <a href="6da77fa5-1590-4646-f2ea-70002c922aee.md">PaletteBase</a>)</td></tr>
<tr>
<td><a href="1687f6f6-f329-81eb-e83d-e628f6529d21.md">BasePaletteChanged</a></td>
<td>Occurs when the BasePalette/BasePaletteMode setting changes.<br />(Inherited from <a href="6da77fa5-1590-4646-f2ea-70002c922aee.md">PaletteBase</a>)</td></tr>
<tr>
<td><a href="98cbbdd9-745f-ad62-17da-e5bb36fd09b6.md">BaseRendererChanged</a></td>
<td>Occurs when the BaseRenderer/BaseRendererMode setting changes.<br />(Inherited from <a href="6da77fa5-1590-4646-f2ea-70002c922aee.md">PaletteBase</a>)</td></tr>
<tr>
<td><a href="2ec8f354-a431-e1bd-7737-63221e7a9f60.md">ButtonSpecChanged</a></td>
<td>Occurs when a button spec change occurs.<br />(Inherited from <a href="6da77fa5-1590-4646-f2ea-70002c922aee.md">PaletteBase</a>)</td></tr>
<tr>
<td>Disposed</td>
<td>Occurs when the component is disposed by a call to the Dispose() method.<br />(Inherited from Component)</td></tr>
<tr>
<td><a href="d3ef0e9c-0866-cbdc-8d1d-5c0bd87cf2e7.md">PalettePaint</a></td>
<td>Occurs when a palette change requires a repaint.<br />(Inherited from <a href="6da77fa5-1590-4646-f2ea-70002c922aee.md">PaletteBase</a>)</td></tr>
</table>

## Fields
<table>
<tr>
<td><a href="51ea23b5-fe38-1125-a9b5-ec55847ed4fe.md">BoldFont</a></td>
<td><br />(Inherited from <a href="6da77fa5-1590-4646-f2ea-70002c922aee.md">PaletteBase</a>)</td></tr>
<tr>
<td><a href="ca2a5472-bd5a-0895-8187-ec08694fb667.md">ButtonFont</a></td>
<td><br />(Inherited from <a href="6da77fa5-1590-4646-f2ea-70002c922aee.md">PaletteBase</a>)</td></tr>
<tr>
<td><a href="49a31c60-ed8d-e29b-f419-0d3198ea1d3a.md">ButtonFontNavigatorMini</a></td>
<td><br />(Inherited from <a href="6da77fa5-1590-4646-f2ea-70002c922aee.md">PaletteBase</a>)</td></tr>
<tr>
<td><a href="259455dd-1b72-9d04-6af8-97815fcb23d2.md">ButtonFontNavigatorStack</a></td>
<td><br />(Inherited from <a href="6da77fa5-1590-4646-f2ea-70002c922aee.md">PaletteBase</a>)</td></tr>
<tr>
<td><a href="6bb0a3c0-35ae-1025-7397-916ec7c465b5.md">CalendarBoldFont</a></td>
<td><br />(Inherited from <a href="6da77fa5-1590-4646-f2ea-70002c922aee.md">PaletteBase</a>)</td></tr>
<tr>
<td><a href="c7077bf2-cbb8-f173-5d9f-60e6ca722416.md">CalendarFont</a></td>
<td><br />(Inherited from <a href="6da77fa5-1590-4646-f2ea-70002c922aee.md">PaletteBase</a>)</td></tr>
<tr>
<td><a href="2eb50573-c487-9254-c7f9-36d5475d450b.md">GridFont</a></td>
<td><br />(Inherited from <a href="6da77fa5-1590-4646-f2ea-70002c922aee.md">PaletteBase</a>)</td></tr>
<tr>
<td><a href="eb82c5c6-e316-d3d4-e86f-8317dc68058d.md">Header1LongFont</a></td>
<td><br />(Inherited from <a href="6da77fa5-1590-4646-f2ea-70002c922aee.md">PaletteBase</a>)</td></tr>
<tr>
<td><a href="df4b1ab4-5230-41ef-df2c-686dc7dec34f.md">Header1ShortFont</a></td>
<td><br />(Inherited from <a href="6da77fa5-1590-4646-f2ea-70002c922aee.md">PaletteBase</a>)</td></tr>
<tr>
<td><a href="d0fe9194-2cfe-2c59-8dfe-91f500461f0f.md">Header2LongFont</a></td>
<td><br />(Inherited from <a href="6da77fa5-1590-4646-f2ea-70002c922aee.md">PaletteBase</a>)</td></tr>
<tr>
<td><a href="645b68de-726b-a1f9-8d6b-c8c965f3f7fb.md">Header2ShortFont</a></td>
<td><br />(Inherited from <a href="6da77fa5-1590-4646-f2ea-70002c922aee.md">PaletteBase</a>)</td></tr>
<tr>
<td><a href="a37a1413-fdaa-6257-faa4-8b9f6fd5649b.md">HeaderFormFont</a></td>
<td><br />(Inherited from <a href="6da77fa5-1590-4646-f2ea-70002c922aee.md">PaletteBase</a>)</td></tr>
<tr>
<td><a href="f44eaf74-1316-6482-f157-8b700a170519.md">ItalicFont</a></td>
<td><br />(Inherited from <a href="6da77fa5-1590-4646-f2ea-70002c922aee.md">PaletteBase</a>)</td></tr>
<tr>
<td><a href="76df6c3b-341f-fc4b-0ae4-8ce17b2303af.md">RibbonTabContextFont</a></td>
<td><br />(Inherited from <a href="6da77fa5-1590-4646-f2ea-70002c922aee.md">PaletteBase</a>)</td></tr>
<tr>
<td><a href="7ec94592-8a0b-0aa7-c071-928a2e5c32a2.md">RibbonTabFont</a></td>
<td><br />(Inherited from <a href="6da77fa5-1590-4646-f2ea-70002c922aee.md">PaletteBase</a>)</td></tr>
<tr>
<td><a href="7945b645-fcb1-de0c-d2d9-c19bb061ac53.md">SuperToolFont</a></td>
<td><br />(Inherited from <a href="6da77fa5-1590-4646-f2ea-70002c922aee.md">PaletteBase</a>)</td></tr>
<tr>
<td><a href="528ff070-8c57-c372-743b-fe742124b5e2.md">TabFontNormal</a></td>
<td><br />(Inherited from <a href="6da77fa5-1590-4646-f2ea-70002c922aee.md">PaletteBase</a>)</td></tr>
<tr>
<td><a href="1789d7f1-3bb6-9cae-58c1-5ddce9d1cff6.md">TabFontSelected</a></td>
<td><br />(Inherited from <a href="6da77fa5-1590-4646-f2ea-70002c922aee.md">PaletteBase</a>)</td></tr>
</table>

## See Also


#### Reference
<a href="79d2eac2-21f4-54ff-7552-b20c33c30600.md">Krypton.Toolkit Namespace</a>  
