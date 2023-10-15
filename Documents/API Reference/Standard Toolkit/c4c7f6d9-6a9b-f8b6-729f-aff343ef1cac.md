# DragManager Class


Manage a dragging operation.



## Definition
**Namespace:** <a href="a21ac074-d119-3dc6-bd1c-d3a12c0128bc.md">Krypton.Navigator</a>  
**Assembly:** Krypton.Navigator (in Krypton.Navigator.dll) Version: 80.23.10.287+8d7660f9dc5efd033fabe008ebfb904beab6d444

**C#**
``` C#
public class DragManager : IDragPageNotify, 
	IDisposable
```
**VB**
``` VB
Public Class DragManager
	Implements IDragPageNotify, IDisposable
```

<table><tr><td><strong>Inheritance</strong></td><td>Object  →  DragManager</td></tr>
<tr><td><strong>Derived</strong></td><td><a href="19778691-abac-8e23-120e-b1812d34bcd8.md">Krypton.Docking.DockingDragManager</a></td></tr>
<tr><td><strong>Implements</strong></td><td><a href="0bde36e7-848f-5e69-cde6-d41167367de8.md">IDragPageNotify</a>, IDisposable</td></tr>
</table>



## Constructors
<table>
<tr>
<td><a href="71ee4088-ce39-f612-3c2f-feed1825ff8e.md">DragManager</a></td>
<td>Initialize a new instance of the DragManager class.</td></tr>
</table>

## Properties
<table>
<tr>
<td><a href="b2c9402f-3a53-7523-223f-f52ad70385b5.md">DocumentCursor</a></td>
<td>Gets and sets a value indicating if document cursors should be used during dragging.</td></tr>
<tr>
<td><a href="7cae82cd-3f99-d533-bb60-a9069e1c990d.md">DragTargetProviders</a></td>
<td>Gets access to the collection of target providers.</td></tr>
<tr>
<td><a href="8e0a77b1-47a7-d7b1-cff5-0d467fd4a82c.md">IsDisposed</a></td>
<td>Gets a value indicating if the view has been disposed.</td></tr>
<tr>
<td><a href="28d5dea6-a95b-d714-2514-fab6d3f74465.md">IsDragging</a></td>
<td>Gets a value indicating if dragging is currently occurring.</td></tr>
<tr>
<td><a href="7c6e25b3-db07-f68a-3690-54a5bc9bd776.md">Palette</a></td>
<td>Gets and sets the custom palette implementation.</td></tr>
<tr>
<td><a href="df9db979-1b9e-0e8b-8dff-8f97f698dc3a.md">PaletteMode</a></td>
<td>Gets or sets the palette to be applied.</td></tr>
<tr>
<td><a href="1c70437f-8671-5542-553a-98bf4c279c4a.md">StateCommon</a></td>
<td>Gets access to the common navigator appearance entries.</td></tr>
</table>

## Methods
<table>
<tr>
<td><a href="5e02e911-cbd2-3d36-efd8-3a877b37ad60.md">CreateDropData</a></td>
<td>Create the actual drop data based on the proposed data provided.</td></tr>
<tr>
<td><a href="fd1816be-979e-39ce-f213-8bd4705cc927.md">Dispose()</a></td>
<td>Release managed and unmanaged resources.</td></tr>
<tr>
<td><a href="4606b176-8c21-d0e5-3a15-c55b932c43ce.md">Dispose(Boolean)</a></td>
<td>Release unmanaged and optionally managed resources.</td></tr>
<tr>
<td><a href="8f1ffd3d-af29-dc87-facd-aff6447a7313.md">DragEnd</a></td>
<td>Occurs when dragging ends because of dropping.</td></tr>
<tr>
<td><a href="c8f93e97-d5ac-68ab-9ebb-5a0e6f582d64.md">DragMove</a></td>
<td>Occurs on dragging movement.</td></tr>
<tr>
<td><a href="da62e0ee-a05c-fa4d-ba88-762c24bd5243.md">DragQuit</a></td>
<td>Occurs when dragging quits.</td></tr>
<tr>
<td><a href="3f10798a-2de6-664c-aedb-8b7c097a9cd0.md">DragStart</a></td>
<td>Occurs when dragging starts.</td></tr>
<tr>
<td>Equals</td>
<td>Determines whether the specified object is equal to the current object.<br />(Inherited from Object)</td></tr>
<tr>
<td><a href="e3cb40d7-3921-d16f-2676-41592bc6ec78.md">Finalize</a></td>
<td>Release resources.<br />(Overrides Object.Finalize())</td></tr>
<tr>
<td>GetHashCode</td>
<td>Serves as the default hash function.<br />(Inherited from Object)</td></tr>
<tr>
<td>GetType</td>
<td>Gets the Type of the current instance.<br />(Inherited from Object)</td></tr>
<tr>
<td>MemberwiseClone</td>
<td>Creates a shallow copy of the current Object.<br />(Inherited from Object)</td></tr>
<tr>
<td><a href="d4dbf0df-16b8-df03-9825-b41be99f9155.md">PageDragEnd</a></td>
<td>Occurs when drag operation completes with pages being dropped.</td></tr>
<tr>
<td><a href="f3d48bce-73f1-e1f8-31c1-9689b69cea5c.md">PageDragMove</a></td>
<td>Occurs when the mouse moves during the drag operation.</td></tr>
<tr>
<td><a href="6988cee0-da95-6cb8-f749-74b40471a628.md">PageDragQuit</a></td>
<td>Occurs when dragging pages has been cancelled.</td></tr>
<tr>
<td><a href="10842e7b-0ddf-0dbc-9a83-4e1357fdc326.md">PageDragStart</a></td>
<td>Occurs when a page drag is about to begin and allows it to be cancelled.</td></tr>
<tr>
<td><a href="26a99c19-9f2e-3c01-20f5-07dfbd48121a.md">RestoreCursor</a></td>
<td>Restore the Displayed cursor back to null.</td></tr>
<tr>
<td>ToString</td>
<td>Returns a string that represents the current object.<br />(Inherited from Object)</td></tr>
<tr>
<td><a href="18174880-aa15-9ca7-c419-fcf8249760bd.md">UpdateCursor</a></td>
<td>Update the Displayed cursor to reflect the current dragging state.</td></tr>
</table>

## See Also


#### Reference
<a href="a21ac074-d119-3dc6-bd1c-d3a12c0128bc.md">Krypton.Navigator Namespace</a>  
