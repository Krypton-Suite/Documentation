# RenderVisualStudio2010With2007 Class


Extends the professional renderer to provide Visual Studio 2010 with Office 2007 style additions.



## Definition
**Namespace:** <a href="79d2eac2-21f4-54ff-7552-b20c33c30600.md">Krypton.Toolkit</a>  
**Assembly:** Krypton.Toolkit (in Krypton.Toolkit.dll) Version: 80.23.10.287+8d7660f9dc5efd033fabe008ebfb904beab6d444

**C#**
``` C#
public class RenderVisualStudio2010With2007 : RenderProfessional
```
**VB**
``` VB
Public Class RenderVisualStudio2010With2007
	Inherits RenderProfessional
```

<table><tr><td><strong>Inheritance</strong></td><td>Object  →  MarshalByRefObject  →  Component  →  <a href="6cc5032c-8089-e880-78ad-3a805f7bd344.md">RenderBase</a>  →  <a href="8a8b9945-a6ad-21c4-5182-014e3b962e19.md">RenderStandard</a>  →  <a href="2216dac9-5539-d45a-e25b-97bad326d559.md">RenderProfessional</a>  →  RenderVisualStudio2010With2007</td></tr>
</table>



## Constructors
<table>
<tr>
<td><a href="6d033f46-7573-3e78-9115-9388295d817b.md">RenderVisualStudio2010With2007</a></td>
<td>Initializes a new instance of the RenderVisualStudio2010With2007 class</td></tr>
</table>

## Properties
<table>
<tr>
<td>CanRaiseEvents</td>
<td>Gets a value indicating whether the component can raise an event.<br />(Inherited from Component)</td></tr>
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
<td><a href="49103901-7488-3c93-de85-8e71196c2c01.md">RenderGlyph</a></td>
<td>Gets the glyph renderer.<br />(Inherited from <a href="6cc5032c-8089-e880-78ad-3a805f7bd344.md">RenderBase</a>)</td></tr>
<tr>
<td><a href="0a712e52-0145-65ba-066b-aaac28f129f0.md">RenderRibbon</a></td>
<td>Gets the ribbon renderer.<br />(Inherited from <a href="6cc5032c-8089-e880-78ad-3a805f7bd344.md">RenderBase</a>)</td></tr>
<tr>
<td><a href="eebf4cb5-6263-46ee-3e1e-e49379246d90.md">RenderStandardBack</a></td>
<td>Gets the standard background renderer.<br />(Inherited from <a href="6cc5032c-8089-e880-78ad-3a805f7bd344.md">RenderBase</a>)</td></tr>
<tr>
<td><a href="26e6ac21-23cb-18aa-659a-477c982951bc.md">RenderStandardBorder</a></td>
<td>Gets the standard border renderer.<br />(Inherited from <a href="6cc5032c-8089-e880-78ad-3a805f7bd344.md">RenderBase</a>)</td></tr>
<tr>
<td><a href="2929f2b7-c927-38f6-cdb5-5ff08ba338b6.md">RenderStandardContent</a></td>
<td>Gets the standard content renderer.<br />(Inherited from <a href="6cc5032c-8089-e880-78ad-3a805f7bd344.md">RenderBase</a>)</td></tr>
<tr>
<td><a href="20645369-c416-c079-e71e-6e6a5e02cd11.md">RenderTabBorder</a></td>
<td>Gets the tab border renderer.<br />(Inherited from <a href="6cc5032c-8089-e880-78ad-3a805f7bd344.md">RenderBase</a>)</td></tr>
<tr>
<td>Site</td>
<td>Gets or sets the ISite of the Component.<br />(Inherited from Component)</td></tr>
</table>

## Methods
<table>
<tr>
<td>Dispose()</td>
<td>Releases all resources used by the Component.<br />(Inherited from Component)</td></tr>
<tr>
<td>Dispose(Boolean)</td>
<td>Releases the unmanaged resources used by the Component and optionally releases the managed resources.<br />(Inherited from Component)</td></tr>
<tr>
<td><a href="0db8dbe5-8da7-9097-389f-eb2dee5e8255.md">DrawBack</a></td>
<td>Draw background to fill the specified path.<br />(Inherited from <a href="8a8b9945-a6ad-21c4-5182-014e3b962e19.md">RenderStandard</a>)</td></tr>
<tr>
<td><a href="d65f2574-fad5-8867-46f9-6432a9e9398c.md">DrawBorder</a></td>
<td>Draw border on the inside edge of the specified rectangle.<br />(Inherited from <a href="8a8b9945-a6ad-21c4-5182-014e3b962e19.md">RenderStandard</a>)</td></tr>
<tr>
<td><a href="7c3e60bc-df3e-82db-b6b4-28809842a6f0.md">DrawCheckBox</a></td>
<td>Perform drawing of a check box.<br />(Inherited from <a href="8a8b9945-a6ad-21c4-5182-014e3b962e19.md">RenderStandard</a>)</td></tr>
<tr>
<td><a href="deea458c-665a-b656-d4f8-23f1604235c5.md">DrawContent</a></td>
<td>Perform draw of content using provided memento.<br />(Inherited from <a href="8a8b9945-a6ad-21c4-5182-014e3b962e19.md">RenderStandard</a>)</td></tr>
<tr>
<td><a href="6c2e7326-a12a-9ea8-7fd8-1f23c306ffb0.md">DrawDragDropDockingGlyph</a></td>
<td>Draw a solid area glyph suitable for a drag drop area.<br />(Inherited from <a href="8a8b9945-a6ad-21c4-5182-014e3b962e19.md">RenderStandard</a>)</td></tr>
<tr>
<td><a href="b0b3eaea-ae0a-62dc-b416-71e96c577dca.md">DrawDragDropSolidGlyph</a></td>
<td>Draw a solid area glyph suitable for a drag drop area.<br />(Inherited from <a href="8a8b9945-a6ad-21c4-5182-014e3b962e19.md">RenderStandard</a>)</td></tr>
<tr>
<td><a href="b45efd95-2536-ab9b-9174-4bc60b6f6cfe.md">DrawDropDownButton</a></td>
<td>Perform drawing of a drop down button.<br />(Inherited from <a href="8a8b9945-a6ad-21c4-5182-014e3b962e19.md">RenderStandard</a>)</td></tr>
<tr>
<td><a href="0329baf6-4572-8c8b-ac4e-b3ba1c5f739d.md">DrawGrabHandleGlyph</a></td>
<td>Internal rendering method.<br />(Inherited from <a href="2216dac9-5539-d45a-e25b-97bad326d559.md">RenderProfessional</a>)</td></tr>
<tr>
<td><a href="ac077688-f7ea-2b5f-be88-e14618ac7f98.md">DrawGridErrorGlyph</a></td>
<td>Draw a grid error glyph.<br />(Inherited from <a href="8a8b9945-a6ad-21c4-5182-014e3b962e19.md">RenderStandard</a>)</td></tr>
<tr>
<td><a href="3602688e-7fc2-02d2-f2c3-c129fa9abf9c.md">DrawGridRowGlyph</a></td>
<td>Draw a grid row glyph.<br />(Inherited from <a href="8a8b9945-a6ad-21c4-5182-014e3b962e19.md">RenderStandard</a>)</td></tr>
<tr>
<td><a href="207fb04b-8a2b-a15a-88b4-9de539525403.md">DrawGridSortGlyph</a></td>
<td>Draw a grid sorting direction glyph.<br />(Inherited from <a href="8a8b9945-a6ad-21c4-5182-014e3b962e19.md">RenderStandard</a>)</td></tr>
<tr>
<td><a href="6cc53a51-4523-f682-b7b9-97d95b3bd6d5.md">DrawInputControlDropDownGlyph</a></td>
<td>Draw a drop down grid appropriate for a input control.<br />(Inherited from <a href="8a8b9945-a6ad-21c4-5182-014e3b962e19.md">RenderStandard</a>)</td></tr>
<tr>
<td><a href="c0fd125d-409c-f742-75a2-055f4dd741dc.md">DrawInputControlNumericDownGlyph</a></td>
<td>Draw a numeric down button image appropriate for a input control.<br />(Inherited from <a href="8a8b9945-a6ad-21c4-5182-014e3b962e19.md">RenderStandard</a>)</td></tr>
<tr>
<td><a href="93836f9e-bcbe-b053-1200-ae338a3321f0.md">DrawInputControlNumericUpGlyph</a></td>
<td>Draw a numeric up button image appropriate for a input control.<br />(Inherited from <a href="8a8b9945-a6ad-21c4-5182-014e3b962e19.md">RenderStandard</a>)</td></tr>
<tr>
<td><a href="c456cf73-0ef9-2e61-e1ed-97057884b0cc.md">DrawRadioButton</a></td>
<td>Perform drawing of a radio button.<br />(Inherited from <a href="8a8b9945-a6ad-21c4-5182-014e3b962e19.md">RenderStandard</a>)</td></tr>
<tr>
<td><a href="e2b36005-577c-29e4-4dfd-cc935d16fa78.md">DrawRibbonAppButton</a></td>
<td>Internal rendering method.<br />(Inherited from <a href="8a8b9945-a6ad-21c4-5182-014e3b962e19.md">RenderStandard</a>)</td></tr>
<tr>
<td><a href="5e5b4369-82e8-9f16-4ad4-d157184bc36e.md">DrawRibbonAppButtonBorder1</a></td>
<td>Internal rendering method.<br />(Inherited from <a href="8a8b9945-a6ad-21c4-5182-014e3b962e19.md">RenderStandard</a>)</td></tr>
<tr>
<td><a href="61cad78e-4990-b26c-5807-6f3db6432de7.md">DrawRibbonAppButtonBorder2</a></td>
<td>Internal rendering method.<br />(Inherited from <a href="8a8b9945-a6ad-21c4-5182-014e3b962e19.md">RenderStandard</a>)</td></tr>
<tr>
<td><a href="41c0c055-9972-87c6-9236-51ca7bef77e5.md">DrawRibbonAppButtonGlowCenter</a></td>
<td>Internal rendering method.<br />(Inherited from <a href="8a8b9945-a6ad-21c4-5182-014e3b962e19.md">RenderStandard</a>)</td></tr>
<tr>
<td><a href="bda7af36-d78a-bbc3-94f1-f83cbfb2416c.md">DrawRibbonAppButtonGlowUpperBottom</a></td>
<td>Internal rendering method.<br />(Inherited from <a href="8a8b9945-a6ad-21c4-5182-014e3b962e19.md">RenderStandard</a>)</td></tr>
<tr>
<td><a href="87f9b77f-20f8-597e-eec8-909e02c69f52.md">DrawRibbonAppButtonLowerHalf</a></td>
<td>Internal rendering method.<br />(Inherited from <a href="8a8b9945-a6ad-21c4-5182-014e3b962e19.md">RenderStandard</a>)</td></tr>
<tr>
<td><a href="f3e6a759-b9f8-0d9f-73b0-2ecd5bd7c966.md">DrawRibbonAppButtonUpperHalf</a></td>
<td>Internal rendering method.<br />(Inherited from <a href="8a8b9945-a6ad-21c4-5182-014e3b962e19.md">RenderStandard</a>)</td></tr>
<tr>
<td><a href="fb551060-4530-6d30-ca35-4f7bc0c4f519.md">DrawRibbonApplicationButton</a></td>
<td>Draw the application button.<br />(Inherited from <a href="8a8b9945-a6ad-21c4-5182-014e3b962e19.md">RenderStandard</a>)</td></tr>
<tr>
<td><a href="5540ac69-eb3c-9726-4bce-3ba5eac49395.md">DrawRibbonApplicationTab</a></td>
<td>Draw the application tab.<br />(Inherited from <a href="8a8b9945-a6ad-21c4-5182-014e3b962e19.md">RenderStandard</a>)</td></tr>
<tr>
<td><a href="be73247f-66b1-afce-00d8-84c185be4b99.md">DrawRibbonAppMenuInner</a></td>
<td>Internal rendering method.<br />(Inherited from <a href="8a8b9945-a6ad-21c4-5182-014e3b962e19.md">RenderStandard</a>)</td></tr>
<tr>
<td><a href="567c0800-54d6-cefc-266e-1dc28a13e366.md">DrawRibbonAppMenuOuter</a></td>
<td>Internal rendering method.<br />(Inherited from <a href="8a8b9945-a6ad-21c4-5182-014e3b962e19.md">RenderStandard</a>)</td></tr>
<tr>
<td><a href="fac99ec1-bf42-000b-16cc-5e3f5ed98506.md">DrawRibbonAppTab</a></td>
<td>Internal rendering method.<br />(Inherited from <a href="8a8b9945-a6ad-21c4-5182-014e3b962e19.md">RenderStandard</a>)</td></tr>
<tr>
<td><a href="05e121d7-2922-f30b-e41c-f16f5dd44c5c.md">DrawRibbonBack</a></td>
<td>Draw the background of a ribbon element.<br />(Inherited from <a href="8a8b9945-a6ad-21c4-5182-014e3b962e19.md">RenderStandard</a>)</td></tr>
<tr>
<td><a href="ffe080bd-05db-a629-f3c5-4a3917561e4b.md">DrawRibbonClusterEdge</a></td>
<td>Perform drawing of a ribbon cluster edge.<br />(Overrides <a href="3544a5f1-97be-e60e-6602-3f7ac1e57355.md">RenderStandard.DrawRibbonClusterEdge(PaletteRibbonShape, RenderContext, Rectangle, IPaletteBack, PaletteState)</a>)</td></tr>
<tr>
<td><a href="beace573-1c43-40eb-5931-395dd853452b.md">DrawRibbonContextArrow</a></td>
<td>Perform drawing of a ribbon context arrow glyph.<br />(Inherited from <a href="8a8b9945-a6ad-21c4-5182-014e3b962e19.md">RenderStandard</a>)</td></tr>
<tr>
<td><a href="9be5f2b9-40b1-9239-1733-8218a868c883.md">DrawRibbonDialogBoxLauncher</a></td>
<td>Perform drawing of a ribbon dialog box launcher glyph.<br />(Inherited from <a href="8a8b9945-a6ad-21c4-5182-014e3b962e19.md">RenderStandard</a>)</td></tr>
<tr>
<td><a href="82ecfe06-7d94-6c74-0ef8-35f10703b853.md">DrawRibbonDropArrow</a></td>
<td>Perform drawing of a ribbon drop arrow glyph.<br />(Inherited from <a href="8a8b9945-a6ad-21c4-5182-014e3b962e19.md">RenderStandard</a>)</td></tr>
<tr>
<td><a href="48e4a9db-8e9f-f1b9-14b6-6790cbf83654.md">DrawRibbonGroupAreaBorder1And2</a></td>
<td>Internal rendering method.<br />(Inherited from <a href="8a8b9945-a6ad-21c4-5182-014e3b962e19.md">RenderStandard</a>)</td></tr>
<tr>
<td><a href="74b945f8-77f6-79c2-f1ca-9ac0bd2bda81.md">DrawRibbonGroupAreaBorder3And4</a></td>
<td>Internal rendering method.<br />(Inherited from <a href="8a8b9945-a6ad-21c4-5182-014e3b962e19.md">RenderStandard</a>)</td></tr>
<tr>
<td><a href="414a743c-e460-043f-bf0d-b897dd6d842a.md">DrawRibbonGroupAreaBorderContext</a></td>
<td>Internal rendering method.<br />(Inherited from <a href="8a8b9945-a6ad-21c4-5182-014e3b962e19.md">RenderStandard</a>)</td></tr>
<tr>
<td><a href="bc43ee6e-f48a-20e8-dff8-b4d7629c90e0.md">DrawRibbonGroupCollapsedBorder</a></td>
<td>Internal rendering method.<br />(Inherited from <a href="8a8b9945-a6ad-21c4-5182-014e3b962e19.md">RenderStandard</a>)</td></tr>
<tr>
<td><a href="59f088cc-0561-b9fb-d8f9-f1635cfd4f3a.md">DrawRibbonGroupCollapsedFrameBorder</a></td>
<td>Internal rendering method.<br />(Inherited from <a href="8a8b9945-a6ad-21c4-5182-014e3b962e19.md">RenderStandard</a>)</td></tr>
<tr>
<td><a href="d4e64e17-179e-1ce5-b3e6-394386c80011.md">DrawRibbonGroupGradientOne</a></td>
<td>Internal rendering method.<br />(Inherited from <a href="8a8b9945-a6ad-21c4-5182-014e3b962e19.md">RenderStandard</a>)</td></tr>
<tr>
<td><a href="1afd38a3-04ba-7928-cac1-c78711594179.md">DrawRibbonGroupGradientTwo</a></td>
<td>Internal rendering method.<br />(Inherited from <a href="8a8b9945-a6ad-21c4-5182-014e3b962e19.md">RenderStandard</a>)</td></tr>
<tr>
<td><a href="fa6cfdbe-7bf3-e65b-5570-288dec49c96c.md">DrawRibbonGroupNormal</a></td>
<td>Internal rendering method.<br />(Inherited from <a href="8a8b9945-a6ad-21c4-5182-014e3b962e19.md">RenderStandard</a>)</td></tr>
<tr>
<td><a href="7cc074a3-6e36-7157-0232-b70c4eb93b16.md">DrawRibbonGroupNormalBorder</a></td>
<td>Internal rendering method.<br />(Inherited from <a href="8a8b9945-a6ad-21c4-5182-014e3b962e19.md">RenderStandard</a>)</td></tr>
<tr>
<td><a href="93787d86-2a70-3034-3730-169a11ea8c19.md">DrawRibbonGroupNormalBorderSep</a></td>
<td>Internal rendering method.<br />(Inherited from <a href="8a8b9945-a6ad-21c4-5182-014e3b962e19.md">RenderStandard</a>)</td></tr>
<tr>
<td><a href="87506a05-88f8-fb44-eb77-dc7fe4139e07.md">DrawRibbonGroupNormalTitle</a></td>
<td>Internal rendering method.<br />(Inherited from <a href="8a8b9945-a6ad-21c4-5182-014e3b962e19.md">RenderStandard</a>)</td></tr>
<tr>
<td><a href="bca05588-4d1a-a5b0-d627-0c42352c37c6.md">DrawRibbonGroupSeparator</a></td>
<td>Perform drawing of a ribbon group separator.<br />(Inherited from <a href="8a8b9945-a6ad-21c4-5182-014e3b962e19.md">RenderStandard</a>)</td></tr>
<tr>
<td><a href="692e1363-293f-3767-5483-45a88c819084.md">DrawRibbonLinear</a></td>
<td>Internal rendering method.<br />(Inherited from <a href="8a8b9945-a6ad-21c4-5182-014e3b962e19.md">RenderStandard</a>)</td></tr>
<tr>
<td><a href="65503e0e-d0c9-bc60-06a5-6a53b347c09b.md">DrawRibbonLinearBorder</a></td>
<td>Internal rendering method.<br />(Inherited from <a href="8a8b9945-a6ad-21c4-5182-014e3b962e19.md">RenderStandard</a>)</td></tr>
<tr>
<td><a href="28cd5658-34a3-cb01-74ba-979cd3a1e8bd.md">DrawRibbonOverflow</a></td>
<td>Perform drawing of a ribbon overflow image.<br />(Inherited from <a href="8a8b9945-a6ad-21c4-5182-014e3b962e19.md">RenderStandard</a>)</td></tr>
<tr>
<td><a href="64d91852-028b-1ac8-6f27-e514d112a988.md">DrawRibbonQATFullbarRound</a></td>
<td>Internal rendering method.<br />(Inherited from <a href="8a8b9945-a6ad-21c4-5182-014e3b962e19.md">RenderStandard</a>)</td></tr>
<tr>
<td><a href="9c479450-bc56-df07-e6f6-25b3607df04a.md">DrawRibbonQATFullbarSquare</a></td>
<td>Internal rendering method.<br />(Inherited from <a href="8a8b9945-a6ad-21c4-5182-014e3b962e19.md">RenderStandard</a>)</td></tr>
<tr>
<td><a href="a1aac58c-5465-72d3-fa28-fd62b83d83af.md">DrawRibbonQATMinibarDouble</a></td>
<td>Internal rendering method.<br />(Inherited from <a href="8a8b9945-a6ad-21c4-5182-014e3b962e19.md">RenderStandard</a>)</td></tr>
<tr>
<td><a href="4022658a-f8ae-8ee3-76a3-fd8472e887e0.md">DrawRibbonQATMinibarSingle</a></td>
<td>Internal rendering method.<br />(Inherited from <a href="8a8b9945-a6ad-21c4-5182-014e3b962e19.md">RenderStandard</a>)</td></tr>
<tr>
<td><a href="c52ebbec-98b7-1202-519e-1bff34579338.md">DrawRibbonQATOverflow</a></td>
<td>Internal rendering method.<br />(Inherited from <a href="8a8b9945-a6ad-21c4-5182-014e3b962e19.md">RenderStandard</a>)</td></tr>
<tr>
<td><a href="661dd9a1-cd5a-ab04-cf8e-b1ac76659e10.md">DrawRibbonTabContext</a></td>
<td>Internal rendering method.<br />(Overrides <a href="b00f4011-9f7b-4308-b810-1d28c66692b5.md">RenderProfessional.DrawRibbonTabContext(RenderContext, Rectangle, IPaletteRibbonGeneral, IPaletteRibbonBack, IDisposable)</a>)</td></tr>
<tr>
<td><a href="77e75d17-994d-e3ca-68c7-78886747e791.md">DrawRibbonTabContextSelected</a></td>
<td>Internal rendering method.<br />(Inherited from <a href="8a8b9945-a6ad-21c4-5182-014e3b962e19.md">RenderStandard</a>)</td></tr>
<tr>
<td><a href="527ff365-7fe3-b2fe-3b28-c2455bf0d203.md">DrawRibbonTabContextSelectedBottom</a></td>
<td>Internal rendering method.<br />(Inherited from <a href="8a8b9945-a6ad-21c4-5182-014e3b962e19.md">RenderStandard</a>)</td></tr>
<tr>
<td><a href="31f33e32-80c3-0229-70c5-3bfd8a64f5b1.md">DrawRibbonTabContextSelectedBottomDraw</a></td>
<td>Internal rendering method.<br />(Inherited from <a href="8a8b9945-a6ad-21c4-5182-014e3b962e19.md">RenderStandard</a>)</td></tr>
<tr>
<td><a href="3ff9d7ad-f381-a685-15f5-0881aad89f6c.md">DrawRibbonTabContextSelectedLeft</a></td>
<td>Internal rendering method.<br />(Inherited from <a href="8a8b9945-a6ad-21c4-5182-014e3b962e19.md">RenderStandard</a>)</td></tr>
<tr>
<td><a href="1930e08d-8c78-5e43-6ac5-bcbd9d05bdb5.md">DrawRibbonTabContextSelectedLeftDraw</a></td>
<td>Internal rendering method.<br />(Inherited from <a href="8a8b9945-a6ad-21c4-5182-014e3b962e19.md">RenderStandard</a>)</td></tr>
<tr>
<td><a href="0c140ca2-f60f-b89b-1fb7-dcf8fa2d7178.md">DrawRibbonTabContextSelectedRight</a></td>
<td>Internal rendering method.<br />(Inherited from <a href="8a8b9945-a6ad-21c4-5182-014e3b962e19.md">RenderStandard</a>)</td></tr>
<tr>
<td><a href="9aac436a-b048-c240-da18-53d6c6b46602.md">DrawRibbonTabContextSelectedRightDraw</a></td>
<td>Internal rendering method.<br />(Inherited from <a href="8a8b9945-a6ad-21c4-5182-014e3b962e19.md">RenderStandard</a>)</td></tr>
<tr>
<td><a href="5a5118d0-daea-d3e5-9bbb-8831d667753e.md">DrawRibbonTabContextSelectedTop</a></td>
<td>Internal rendering method.<br />(Inherited from <a href="8a8b9945-a6ad-21c4-5182-014e3b962e19.md">RenderStandard</a>)</td></tr>
<tr>
<td><a href="0dd1bcba-e0a6-0e75-e3bb-07e9bd24f041.md">DrawRibbonTabContextSelectedTopDraw</a></td>
<td>Internal rendering method.<br />(Inherited from <a href="8a8b9945-a6ad-21c4-5182-014e3b962e19.md">RenderStandard</a>)</td></tr>
<tr>
<td><a href="66887ba1-1974-d04b-e920-4ebf93fc2d4e.md">DrawRibbonTabContextTitle</a></td>
<td>Draw a context ribbon tab title.<br />(Inherited from <a href="8a8b9945-a6ad-21c4-5182-014e3b962e19.md">RenderStandard</a>)</td></tr>
<tr>
<td><a href="f15728f8-7c6a-7e87-1b85-6a4247bad3cf.md">DrawRibbonTabFocus2010</a></td>
<td>Internal rendering method.<br />(Inherited from <a href="8a8b9945-a6ad-21c4-5182-014e3b962e19.md">RenderStandard</a>)</td></tr>
<tr>
<td><a href="9aed009f-e7fc-e556-d3fd-350a185eb1bb.md">DrawRibbonTabFocusBottom2010</a></td>
<td>Internal rendering method.<br />(Inherited from <a href="8a8b9945-a6ad-21c4-5182-014e3b962e19.md">RenderStandard</a>)</td></tr>
<tr>
<td><a href="bbfd2abe-a92c-5ce7-acae-d1b5cddae2a7.md">DrawRibbonTabFocusLeft2010</a></td>
<td>Internal rendering method.<br />(Inherited from <a href="8a8b9945-a6ad-21c4-5182-014e3b962e19.md">RenderStandard</a>)</td></tr>
<tr>
<td><a href="adadb4f5-5f38-0db4-9133-e89535d5dd98.md">DrawRibbonTabFocusRight2010</a></td>
<td>Internal rendering method.<br />(Inherited from <a href="8a8b9945-a6ad-21c4-5182-014e3b962e19.md">RenderStandard</a>)</td></tr>
<tr>
<td><a href="43e3dda1-b8a1-5760-e5f6-1e5cf413d602.md">DrawRibbonTabFocusTop2010</a></td>
<td>Internal rendering method.<br />(Inherited from <a href="8a8b9945-a6ad-21c4-5182-014e3b962e19.md">RenderStandard</a>)</td></tr>
<tr>
<td><a href="50087076-abb7-48fb-aace-652e9e523f29.md">DrawRibbonTabGlowing</a></td>
<td>Internal rendering method.<br />(Inherited from <a href="8a8b9945-a6ad-21c4-5182-014e3b962e19.md">RenderStandard</a>)</td></tr>
<tr>
<td><a href="20a391b8-d91c-6640-7ce4-777788e528d4.md">DrawRibbonTabGlowingBottom</a></td>
<td>Internal rendering method.<br />(Inherited from <a href="8a8b9945-a6ad-21c4-5182-014e3b962e19.md">RenderStandard</a>)</td></tr>
<tr>
<td><a href="b3402fac-397f-cc6e-f046-c7848e50c15d.md">DrawRibbonTabGlowingLeft</a></td>
<td>Internal rendering method.<br />(Inherited from <a href="8a8b9945-a6ad-21c4-5182-014e3b962e19.md">RenderStandard</a>)</td></tr>
<tr>
<td><a href="4d814241-4b66-df21-7fec-110d97d935d3.md">DrawRibbonTabGlowingRight</a></td>
<td>Internal rendering method.<br />(Inherited from <a href="8a8b9945-a6ad-21c4-5182-014e3b962e19.md">RenderStandard</a>)</td></tr>
<tr>
<td><a href="59e19d36-da45-7a95-5fed-913a24e7ac90.md">DrawRibbonTabGlowingTop</a></td>
<td>Internal rendering method.<br />(Inherited from <a href="8a8b9945-a6ad-21c4-5182-014e3b962e19.md">RenderStandard</a>)</td></tr>
<tr>
<td><a href="6107889e-7365-46fa-efdf-b2cc3c3a5366.md">DrawRibbonTabHighlight</a></td>
<td>Internal rendering method.<br />(Inherited from <a href="8a8b9945-a6ad-21c4-5182-014e3b962e19.md">RenderStandard</a>)</td></tr>
<tr>
<td><a href="6a9fa2c1-3e6c-9426-b3ee-0ad1789f524e.md">DrawRibbonTabHighlightBottom</a></td>
<td>Internal rendering method.<br />(Inherited from <a href="8a8b9945-a6ad-21c4-5182-014e3b962e19.md">RenderStandard</a>)</td></tr>
<tr>
<td><a href="ab572eaa-91c3-5ff0-1547-16c63dc72b82.md">DrawRibbonTabHighlightBottomDraw</a></td>
<td>Internal rendering method.<br />(Inherited from <a href="8a8b9945-a6ad-21c4-5182-014e3b962e19.md">RenderStandard</a>)</td></tr>
<tr>
<td><a href="b5abf42a-8223-fc34-abc7-d0d4d8d24b10.md">DrawRibbonTabHighlightLeft</a></td>
<td>Internal rendering method.<br />(Inherited from <a href="8a8b9945-a6ad-21c4-5182-014e3b962e19.md">RenderStandard</a>)</td></tr>
<tr>
<td><a href="55ae19c5-5938-17c2-b4de-ef32ea7907e3.md">DrawRibbonTabHighlightLeftDraw</a></td>
<td>Internal rendering method.<br />(Inherited from <a href="8a8b9945-a6ad-21c4-5182-014e3b962e19.md">RenderStandard</a>)</td></tr>
<tr>
<td><a href="ab4329bb-7551-3acf-0adf-0af1bf71f61b.md">DrawRibbonTabHighlightRight</a></td>
<td>Internal rendering method.<br />(Inherited from <a href="8a8b9945-a6ad-21c4-5182-014e3b962e19.md">RenderStandard</a>)</td></tr>
<tr>
<td><a href="3fd71c00-ca97-5b0c-0fa9-559ec4035f5a.md">DrawRibbonTabHighlightRightDraw</a></td>
<td>Internal rendering method.<br />(Inherited from <a href="8a8b9945-a6ad-21c4-5182-014e3b962e19.md">RenderStandard</a>)</td></tr>
<tr>
<td><a href="cccd42a5-ad7e-3c93-78ea-ce4cd60fab36.md">DrawRibbonTabHighlightTop</a></td>
<td>Internal rendering method.<br />(Inherited from <a href="8a8b9945-a6ad-21c4-5182-014e3b962e19.md">RenderStandard</a>)</td></tr>
<tr>
<td><a href="7bd70be0-261d-b80a-cfc7-a5fd8afbd6d8.md">DrawRibbonTabHighlightTopDraw</a></td>
<td>Internal rendering method.<br />(Inherited from <a href="8a8b9945-a6ad-21c4-5182-014e3b962e19.md">RenderStandard</a>)</td></tr>
<tr>
<td><a href="1baedf94-1b54-78e3-b8fd-68b4fb108dc9.md">DrawRibbonTabSelected2007</a></td>
<td>Internal rendering method.<br />(Inherited from <a href="8a8b9945-a6ad-21c4-5182-014e3b962e19.md">RenderStandard</a>)</td></tr>
<tr>
<td><a href="0fd3c072-507f-4864-a123-a58ef2995e7b.md">DrawRibbonTabSelected2010</a></td>
<td>Internal rendering method.<br />(Inherited from <a href="8a8b9945-a6ad-21c4-5182-014e3b962e19.md">RenderStandard</a>)</td></tr>
<tr>
<td><a href="9c28b839-e4dd-237f-ecee-b35dd3cfb23b.md">DrawRibbonTabSelectedBottom2007</a></td>
<td>Internal rendering method.<br />(Inherited from <a href="8a8b9945-a6ad-21c4-5182-014e3b962e19.md">RenderStandard</a>)</td></tr>
<tr>
<td><a href="29ccfda2-b9fc-fef2-668d-d69c74c2e454.md">DrawRibbonTabSelectedBottom2010</a></td>
<td>Internal rendering method.<br />(Inherited from <a href="8a8b9945-a6ad-21c4-5182-014e3b962e19.md">RenderStandard</a>)</td></tr>
<tr>
<td><a href="3a287c1e-f925-5d5b-aba7-8299671f2869.md">DrawRibbonTabSelectedBottomDraw2007</a></td>
<td>Internal rendering method.<br />(Inherited from <a href="8a8b9945-a6ad-21c4-5182-014e3b962e19.md">RenderStandard</a>)</td></tr>
<tr>
<td><a href="6094c2ff-12d6-56e4-08e9-b4a8bc0e2602.md">DrawRibbonTabSelectedBottomDraw2010</a></td>
<td>Internal rendering method.<br />(Inherited from <a href="8a8b9945-a6ad-21c4-5182-014e3b962e19.md">RenderStandard</a>)</td></tr>
<tr>
<td><a href="ff576851-7ec8-e130-95ee-1e6518b9f168.md">DrawRibbonTabSelectedLeft2007</a></td>
<td>Internal rendering method.<br />(Inherited from <a href="8a8b9945-a6ad-21c4-5182-014e3b962e19.md">RenderStandard</a>)</td></tr>
<tr>
<td><a href="0c55584d-d6f3-ca89-f6a2-230b118faaff.md">DrawRibbonTabSelectedLeft2010</a></td>
<td>Internal rendering method.<br />(Inherited from <a href="8a8b9945-a6ad-21c4-5182-014e3b962e19.md">RenderStandard</a>)</td></tr>
<tr>
<td><a href="8ddffd15-6d80-bc6b-d0d0-62a7eba57490.md">DrawRibbonTabSelectedLeftDraw2007</a></td>
<td>Internal rendering method.<br />(Inherited from <a href="8a8b9945-a6ad-21c4-5182-014e3b962e19.md">RenderStandard</a>)</td></tr>
<tr>
<td><a href="70491d88-62d8-e547-cd11-1470c7d2452c.md">DrawRibbonTabSelectedLeftDraw2010</a></td>
<td>Internal rendering method.<br />(Inherited from <a href="8a8b9945-a6ad-21c4-5182-014e3b962e19.md">RenderStandard</a>)</td></tr>
<tr>
<td><a href="b6fc048c-0a42-de97-5153-8431eafbd7f5.md">DrawRibbonTabSelectedRight2007</a></td>
<td>Internal rendering method.<br />(Inherited from <a href="8a8b9945-a6ad-21c4-5182-014e3b962e19.md">RenderStandard</a>)</td></tr>
<tr>
<td><a href="ae0810d2-a367-7c08-7af2-770d13081ad0.md">DrawRibbonTabSelectedRight2010</a></td>
<td>Internal rendering method.<br />(Inherited from <a href="8a8b9945-a6ad-21c4-5182-014e3b962e19.md">RenderStandard</a>)</td></tr>
<tr>
<td><a href="f15210a2-a2ad-c84a-0ed6-c37a233bf80d.md">DrawRibbonTabSelectedRightDraw2007</a></td>
<td>Internal rendering method.<br />(Inherited from <a href="8a8b9945-a6ad-21c4-5182-014e3b962e19.md">RenderStandard</a>)</td></tr>
<tr>
<td><a href="fbe4f7c3-2a0b-8e7b-2c41-5522fe14092e.md">DrawRibbonTabSelectedRightDraw2010</a></td>
<td>Internal rendering method.<br />(Inherited from <a href="8a8b9945-a6ad-21c4-5182-014e3b962e19.md">RenderStandard</a>)</td></tr>
<tr>
<td><a href="1fa61566-9744-587d-b866-3dc59561a78d.md">DrawRibbonTabSelectedTop2007</a></td>
<td>Internal rendering method.<br />(Inherited from <a href="8a8b9945-a6ad-21c4-5182-014e3b962e19.md">RenderStandard</a>)</td></tr>
<tr>
<td><a href="29edd903-b8dd-463b-05f8-35bca52e6da8.md">DrawRibbonTabSelectedTop2010</a></td>
<td>Internal rendering method.<br />(Inherited from <a href="8a8b9945-a6ad-21c4-5182-014e3b962e19.md">RenderStandard</a>)</td></tr>
<tr>
<td><a href="b6c04fca-896b-9b18-624e-2b49b8387cae.md">DrawRibbonTabSelectedTopDraw2007</a></td>
<td>Internal rendering method.<br />(Inherited from <a href="8a8b9945-a6ad-21c4-5182-014e3b962e19.md">RenderStandard</a>)</td></tr>
<tr>
<td><a href="48437323-2e9d-e798-06a5-f448e3aa8e06.md">DrawRibbonTabSelectedTopDraw2010</a></td>
<td>Internal rendering method.<br />(Inherited from <a href="8a8b9945-a6ad-21c4-5182-014e3b962e19.md">RenderStandard</a>)</td></tr>
<tr>
<td><a href="eb51d95b-65b0-1602-1a12-4803a1697671.md">DrawRibbonTabTracking2007</a></td>
<td>Internal rendering method.<br />(Inherited from <a href="8a8b9945-a6ad-21c4-5182-014e3b962e19.md">RenderStandard</a>)</td></tr>
<tr>
<td><a href="3af143e0-8c15-36d2-68d3-979e9a8d1609.md">DrawRibbonTabTracking2010</a></td>
<td>Internal rendering method.<br />(Inherited from <a href="8a8b9945-a6ad-21c4-5182-014e3b962e19.md">RenderStandard</a>)</td></tr>
<tr>
<td><a href="0b201a0f-0b2b-d2c0-baad-2261a896e480.md">DrawRibbonTabTrackingBottom2007</a></td>
<td>Internal rendering method.<br />(Inherited from <a href="8a8b9945-a6ad-21c4-5182-014e3b962e19.md">RenderStandard</a>)</td></tr>
<tr>
<td><a href="efc550bd-26da-922e-50b2-fdb7aad72995.md">DrawRibbonTabTrackingBottom2010</a></td>
<td>Internal rendering method.<br />(Inherited from <a href="8a8b9945-a6ad-21c4-5182-014e3b962e19.md">RenderStandard</a>)</td></tr>
<tr>
<td><a href="259459d5-993f-7d6b-aac4-a7fc4e45d56f.md">DrawRibbonTabTrackingBottomDraw2007</a></td>
<td>Internal rendering method.<br />(Inherited from <a href="8a8b9945-a6ad-21c4-5182-014e3b962e19.md">RenderStandard</a>)</td></tr>
<tr>
<td><a href="ef1844d3-3f46-76e0-0efa-71e0cc60a76c.md">DrawRibbonTabTrackingLeft2007</a></td>
<td>Internal rendering method.<br />(Inherited from <a href="8a8b9945-a6ad-21c4-5182-014e3b962e19.md">RenderStandard</a>)</td></tr>
<tr>
<td><a href="80c816bc-ddcd-6a55-0024-88ec53ab8bff.md">DrawRibbonTabTrackingLeft2010</a></td>
<td>Internal rendering method.<br />(Inherited from <a href="8a8b9945-a6ad-21c4-5182-014e3b962e19.md">RenderStandard</a>)</td></tr>
<tr>
<td><a href="ae6da676-33fc-8150-52ff-4e6844f34982.md">DrawRibbonTabTrackingLeftDraw2007</a></td>
<td>Internal rendering method.<br />(Inherited from <a href="8a8b9945-a6ad-21c4-5182-014e3b962e19.md">RenderStandard</a>)</td></tr>
<tr>
<td><a href="6225f9f3-ae37-1031-2888-a146ce8cf701.md">DrawRibbonTabTrackingRight2007</a></td>
<td>Internal rendering method.<br />(Inherited from <a href="8a8b9945-a6ad-21c4-5182-014e3b962e19.md">RenderStandard</a>)</td></tr>
<tr>
<td><a href="63f4ddb9-909e-9d3e-7b97-46c74b0ed676.md">DrawRibbonTabTrackingRight2010</a></td>
<td>Internal rendering method.<br />(Inherited from <a href="8a8b9945-a6ad-21c4-5182-014e3b962e19.md">RenderStandard</a>)</td></tr>
<tr>
<td><a href="0ef64a44-894f-50a9-3644-b88ee5ca5acf.md">DrawRibbonTabTrackingRightDraw2007</a></td>
<td>Internal rendering method.<br />(Inherited from <a href="8a8b9945-a6ad-21c4-5182-014e3b962e19.md">RenderStandard</a>)</td></tr>
<tr>
<td><a href="0001dfc0-a0b0-11e6-47db-5542f0d97b9a.md">DrawRibbonTabTrackingTop2007</a></td>
<td>Internal rendering method.<br />(Inherited from <a href="8a8b9945-a6ad-21c4-5182-014e3b962e19.md">RenderStandard</a>)</td></tr>
<tr>
<td><a href="3499bc9b-035b-c510-db07-c934ba81883a.md">DrawRibbonTabTrackingTop2010</a></td>
<td>Internal rendering method.<br />(Inherited from <a href="8a8b9945-a6ad-21c4-5182-014e3b962e19.md">RenderStandard</a>)</td></tr>
<tr>
<td><a href="2f58430b-008d-a065-232f-78ab85cb0358.md">DrawRibbonTabTrackingTopDraw2007</a></td>
<td>Internal rendering method.<br />(Inherited from <a href="8a8b9945-a6ad-21c4-5182-014e3b962e19.md">RenderStandard</a>)</td></tr>
<tr>
<td><a href="856f4c08-a107-960f-b54f-8932a88c8871.md">DrawSeparator</a></td>
<td>Perform drawing of a separator glyph.<br />(Inherited from <a href="2216dac9-5539-d45a-e25b-97bad326d559.md">RenderProfessional</a>)</td></tr>
<tr>
<td><a href="97c90622-c3c3-338a-bdec-b3411c821c86.md">DrawTabBorder</a></td>
<td>Draw border on the inside edge of the specified rectangle.<br />(Inherited from <a href="8a8b9945-a6ad-21c4-5182-014e3b962e19.md">RenderStandard</a>)</td></tr>
<tr>
<td><a href="5e9aff2b-8be6-a8a8-8081-8ec924092a86.md">DrawTrackGlyph</a></td>
<td>Draw the track bar track glyph.<br />(Inherited from <a href="8a8b9945-a6ad-21c4-5182-014e3b962e19.md">RenderStandard</a>)</td></tr>
<tr>
<td><a href="6c03d597-1fac-6ee8-2efa-603ac8317706.md">DrawTrackPositionGlyph</a></td>
<td>Draw the track bar position glyph.<br />(Inherited from <a href="8a8b9945-a6ad-21c4-5182-014e3b962e19.md">RenderStandard</a>)</td></tr>
<tr>
<td><a href="d055c161-b87c-d45e-f677-491276f97f94.md">DrawTrackTicksGlyph</a></td>
<td>Draw the track bar ticks glyph.<br />(Inherited from <a href="8a8b9945-a6ad-21c4-5182-014e3b962e19.md">RenderStandard</a>)</td></tr>
<tr>
<td>Equals</td>
<td>Determines whether the specified object is equal to the current object.<br />(Inherited from Object)</td></tr>
<tr>
<td><a href="d2a4b776-2d61-c414-340c-c4bb229fa201.md">EvalTransparentPaint(IPaletteBack, PaletteState)</a></td>
<td>Evaluate if transparent painting is needed for background palette.<br />(Inherited from <a href="8a8b9945-a6ad-21c4-5182-014e3b962e19.md">RenderStandard</a>)</td></tr>
<tr>
<td><a href="a62f5640-4d38-cc80-aad2-00839ec974ca.md">EvalTransparentPaint(IPaletteBack, IPaletteBorder, PaletteState)</a></td>
<td>Evaluate if transparent painting is needed for background or border palettes.<br />(Inherited from <a href="8a8b9945-a6ad-21c4-5182-014e3b962e19.md">RenderStandard</a>)</td></tr>
<tr>
<td>Finalize</td>
<td>Releases unmanaged resources and performs other cleanup operations before the Component is reclaimed by garbage collection.<br />(Inherited from Component)</td></tr>
<tr>
<td><a href="a05e9bcc-57cb-aa89-74d9-7df8c88d9087.md">GetBackPath</a></td>
<td>Generate a graphics path that encloses the border and is used when rendering a background to ensure the background does not draw over the border area.<br />(Inherited from <a href="8a8b9945-a6ad-21c4-5182-014e3b962e19.md">RenderStandard</a>)</td></tr>
<tr>
<td><a href="a24611ba-1f2c-0d18-e7bd-938338205c4b.md">GetBorderDisplayPadding</a></td>
<td>Gets the padding used to position display elements completely inside border drawing.<br />(Inherited from <a href="8a8b9945-a6ad-21c4-5182-014e3b962e19.md">RenderStandard</a>)</td></tr>
<tr>
<td><a href="5eddd4a7-e882-b7e0-8975-f73e0866a2d0.md">GetBorderPath</a></td>
<td>Generate a graphics path that is in the middle of the border.<br />(Inherited from <a href="8a8b9945-a6ad-21c4-5182-014e3b962e19.md">RenderStandard</a>)</td></tr>
<tr>
<td><a href="ab45e458-a769-35be-d000-1a8c3325cedc.md">GetBorderRawPadding</a></td>
<td>Gets the raw padding used per edge of the border.<br />(Inherited from <a href="8a8b9945-a6ad-21c4-5182-014e3b962e19.md">RenderStandard</a>)</td></tr>
<tr>
<td><a href="03c4dd8e-d61f-8356-c321-a5cfbe0de193.md">GetCheckBoxPreferredSize</a></td>
<td>Calculate the requested display size for the check box.<br />(Inherited from <a href="8a8b9945-a6ad-21c4-5182-014e3b962e19.md">RenderStandard</a>)</td></tr>
<tr>
<td><a href="503ee80b-0b80-700b-d303-0968a4da6a6c.md">GetContentImageDisplayed</a></td>
<td>Request the calculated display of the image.<br />(Inherited from <a href="8a8b9945-a6ad-21c4-5182-014e3b962e19.md">RenderStandard</a>)</td></tr>
<tr>
<td><a href="8328f328-f83a-a05a-57d3-74d7c53c5511.md">GetContentImageRectangle</a></td>
<td>Request the calculated position of the content image.<br />(Inherited from <a href="8a8b9945-a6ad-21c4-5182-014e3b962e19.md">RenderStandard</a>)</td></tr>
<tr>
<td><a href="79c40410-ab32-57af-f268-ee074c08bbbc.md">GetContentLongTextDisplayed</a></td>
<td>Request the calculated display of the long text.<br />(Inherited from <a href="8a8b9945-a6ad-21c4-5182-014e3b962e19.md">RenderStandard</a>)</td></tr>
<tr>
<td><a href="40dc3c43-44ac-7a9b-742c-e5515dc2703c.md">GetContentLongTextRectangle</a></td>
<td>Request the calculated position of the content long text.<br />(Inherited from <a href="8a8b9945-a6ad-21c4-5182-014e3b962e19.md">RenderStandard</a>)</td></tr>
<tr>
<td><a href="c303a244-6a90-92e1-fecf-1c7b54aa9fe0.md">GetContentPreferredSize</a></td>
<td>Get the preferred size for drawing the content.<br />(Inherited from <a href="8a8b9945-a6ad-21c4-5182-014e3b962e19.md">RenderStandard</a>)</td></tr>
<tr>
<td><a href="bf407d67-b820-d17b-f18e-257ce0a8a6f7.md">GetContentShortTextDisplayed</a></td>
<td>Request the calculated display of the short text.<br />(Inherited from <a href="8a8b9945-a6ad-21c4-5182-014e3b962e19.md">RenderStandard</a>)</td></tr>
<tr>
<td><a href="6b3f21ac-b0ab-a1fb-76cc-ce59257f46db.md">GetContentShortTextRectangle</a></td>
<td>Request the calculated position of the content short text.<br />(Inherited from <a href="8a8b9945-a6ad-21c4-5182-014e3b962e19.md">RenderStandard</a>)</td></tr>
<tr>
<td><a href="346438b9-66b8-3908-a7cc-1689751f6b57.md">GetDropDownButtonPreferredSize</a></td>
<td>Calculate the requested display size for the drop down button.<br />(Inherited from <a href="8a8b9945-a6ad-21c4-5182-014e3b962e19.md">RenderStandard</a>)</td></tr>
<tr>
<td>GetHashCode</td>
<td>Serves as the default hash function.<br />(Inherited from Object)</td></tr>
<tr>
<td>GetLifetimeService</td>
<td>Retrieves the current lifetime service object that controls the lifetime policy for this instance.<br />(Inherited from MarshalByRefObject)<br /><strong>Obsolete.</strong></td></tr>
<tr>
<td><a href="3a8115b8-15cf-c7ff-fd88-25e0a3fedc64.md">GetOutsideBorderPath</a></td>
<td>Generate a graphics path that is the outside edge of the border.<br />(Inherited from <a href="8a8b9945-a6ad-21c4-5182-014e3b962e19.md">RenderStandard</a>)</td></tr>
<tr>
<td><a href="adaa27dd-eafb-4cd7-2013-f3ab67d24ea4.md">GetRadioButtonPreferredSize</a></td>
<td>Calculate the requested display size for the radio button.<br />(Inherited from <a href="8a8b9945-a6ad-21c4-5182-014e3b962e19.md">RenderStandard</a>)</td></tr>
<tr>
<td>GetService</td>
<td>Returns an object that represents a service provided by the Component or by its Container.<br />(Inherited from Component)</td></tr>
<tr>
<td><a href="e0d70b8c-a8f7-4e8d-0887-b8681424b6e1.md">GetTabBackPath</a></td>
<td>Generate a graphics path that encloses the border and is used when rendering a background to ensure the background does not draw over the border area.<br />(Inherited from <a href="8a8b9945-a6ad-21c4-5182-014e3b962e19.md">RenderStandard</a>)</td></tr>
<tr>
<td><a href="fa072874-97d1-6b52-9fc4-18238794f695.md">GetTabBorderDisplayPadding</a></td>
<td>Gets the padding used to position display elements completely inside border drawing.<br />(Inherited from <a href="8a8b9945-a6ad-21c4-5182-014e3b962e19.md">RenderStandard</a>)</td></tr>
<tr>
<td><a href="fa2009ac-c7c5-3aa9-381d-dda69062b6de.md">GetTabBorderLeftDrawing</a></td>
<td>Gets if the tabs should be drawn from left to right for z-ordering.<br />(Inherited from <a href="8a8b9945-a6ad-21c4-5182-014e3b962e19.md">RenderStandard</a>)</td></tr>
<tr>
<td><a href="d0c60f17-bd61-c927-abfa-da823c5f1b8d.md">GetTabBorderPath</a></td>
<td>Generate a graphics path that encloses the border itself.<br />(Inherited from <a href="8a8b9945-a6ad-21c4-5182-014e3b962e19.md">RenderStandard</a>)</td></tr>
<tr>
<td><a href="305bc0f1-dd7d-06af-7e29-b7d42f2a33a3.md">GetTabBorderSpacingGap</a></td>
<td>Gets the spacing used to separate each tab border instance.<br />(Inherited from <a href="8a8b9945-a6ad-21c4-5182-014e3b962e19.md">RenderStandard</a>)</td></tr>
<tr>
<td>GetType</td>
<td>Gets the Type of the current instance.<br />(Inherited from Object)</td></tr>
<tr>
<td>InitializeLifetimeService</td>
<td>Obtains a lifetime service object to control the lifetime policy for this instance.<br />(Inherited from MarshalByRefObject)<br /><strong>Obsolete.</strong></td></tr>
<tr>
<td><a href="8e892905-9567-feb4-14b4-5c9a009730ae.md">LayoutContent</a></td>
<td>Perform layout calculations on the provided content.<br />(Inherited from <a href="8a8b9945-a6ad-21c4-5182-014e3b962e19.md">RenderStandard</a>)</td></tr>
<tr>
<td><a href="62d49528-0d96-a1e8-7ec0-5c2365ec4074.md">MeasureDragDropDockingGlyph</a></td>
<td>Measure the drag and drop docking glyphs.<br />(Inherited from <a href="8a8b9945-a6ad-21c4-5182-014e3b962e19.md">RenderStandard</a>)</td></tr>
<tr>
<td>MemberwiseClone()</td>
<td>Creates a shallow copy of the current Object.<br />(Inherited from Object)</td></tr>
<tr>
<td>MemberwiseClone(Boolean)</td>
<td>Creates a shallow copy of the current MarshalByRefObject object.<br />(Inherited from MarshalByRefObject)</td></tr>
<tr>
<td><a href="bc4ccb84-cc69-7ed4-dbca-bca1d6165d0a.md">RenderToolStrip</a></td>
<td>Gets a renderer for drawing the toolstrips.<br />(Overrides <a href="6b1709ce-1367-a7a0-8283-d5e69720ee19.md">RenderStandard.RenderToolStrip(PaletteBase)</a>)</td></tr>
<tr>
<td>ToString</td>
<td>Returns a String containing the name of the Component, if any. This method should not be overridden.<br />(Inherited from Component)</td></tr>
</table>

## Events
<table>
<tr>
<td>Disposed</td>
<td>Occurs when the component is disposed by a call to the Dispose() method.<br />(Inherited from Component)</td></tr>
</table>

## See Also


#### Reference
<a href="79d2eac2-21f4-54ff-7552-b20c33c30600.md">Krypton.Toolkit Namespace</a>  
