# KryptonDataGridViewLinkColumn Class


Hosts a collection of KryptonDataGridViewLinkColumn cells.



## Definition
**Namespace:** <a href="79d2eac2-21f4-54ff-7552-b20c33c30600.md">Krypton.Toolkit</a>  
**Assembly:** Krypton.Toolkit (in Krypton.Toolkit.dll) Version: 80.23.10.287+8d7660f9dc5efd033fabe008ebfb904beab6d444

**C#**
``` C#
public class KryptonDataGridViewLinkColumn : KryptonDataGridViewIconColumn
```
**VB**
``` VB
Public Class KryptonDataGridViewLinkColumn
	Inherits KryptonDataGridViewIconColumn
```

<table><tr><td><strong>Inheritance</strong></td><td>Object  →  DataGridViewElement  →  DataGridViewBand  →  DataGridViewColumn  →  <a href="21f6015d-1ab5-4482-8193-6cf4882c3abf.md">KryptonDataGridViewIconColumn</a>  →  KryptonDataGridViewLinkColumn</td></tr>
</table>



## Constructors
<table>
<tr>
<td><a href="6b0eadb1-c0a7-feaf-a703-2e976eccb040.md">KryptonDataGridViewLinkColumn</a></td>
<td>Initialize a new instance of the KryptonDataGridViewLinkColumn class.</td></tr>
</table>

## Properties
<table>
<tr>
<td>AutoSizeMode</td>
<td>Gets or sets the mode by which the column automatically adjusts its width.<br />(Inherited from DataGridViewColumn)</td></tr>
<tr>
<td><a href="80eb339b-6047-516d-6aa9-e357fbfbb2c5.md">CellTemplate</a></td>
<td>Gets or sets the template used to model cell appearance.<br />(Overrides DataGridViewColumn.CellTemplate)</td></tr>
<tr>
<td>CellType</td>
<td>Gets the run-time type of the cell template.<br />(Inherited from DataGridViewColumn)</td></tr>
<tr>
<td>ContextMenuStrip</td>
<td>Gets or sets the shortcut menu for the column.<br />(Inherited from DataGridViewColumn)</td></tr>
<tr>
<td>DataGridView</td>
<td>Gets the DataGridView control associated with this element.<br />(Inherited from DataGridViewElement)</td></tr>
<tr>
<td>DataPropertyName</td>
<td>Gets or sets the name of the data source property or database column to which the DataGridViewColumn is bound.<br />(Inherited from DataGridViewColumn)</td></tr>
<tr>
<td>DefaultCellStyle</td>
<td>Gets or sets the column's default cell style.<br />(Inherited from DataGridViewColumn)</td></tr>
<tr>
<td>DefaultHeaderCellType</td>
<td>Gets or sets the run-time type of the default header cell.<br />(Inherited from DataGridViewBand)</td></tr>
<tr>
<td>Displayed</td>
<td>Gets a value indicating whether the band is currently displayed onscreen.<br />(Inherited from DataGridViewBand)</td></tr>
<tr>
<td>DisplayIndex</td>
<td>Gets or sets the display order of the column relative to the currently displayed columns.<br />(Inherited from DataGridViewColumn)</td></tr>
<tr>
<td>DividerWidth</td>
<td>Gets or sets the width, in pixels, of the column divider.<br />(Inherited from DataGridViewColumn)</td></tr>
<tr>
<td>FillWeight</td>
<td>Gets or sets a value that represents the width of the column when it is in fill mode relative to the widths of other fill-mode columns in the control.<br />(Inherited from DataGridViewColumn)</td></tr>
<tr>
<td>Frozen</td>
<td>Gets or sets a value indicating whether a column will move when a user scrolls the DataGridView control horizontally.<br />(Inherited from DataGridViewColumn)</td></tr>
<tr>
<td>HasDefaultCellStyle</td>
<td>Gets a value indicating whether the DefaultCellStyle property has been set.<br />(Inherited from DataGridViewBand)</td></tr>
<tr>
<td>HeaderCell</td>
<td>Gets or sets the DataGridViewColumnHeaderCell that represents the column header.<br />(Inherited from DataGridViewColumn)</td></tr>
<tr>
<td>HeaderCellCore</td>
<td>Gets or sets the header cell of the DataGridViewBand.<br />(Inherited from DataGridViewBand)</td></tr>
<tr>
<td>HeaderText</td>
<td>Gets or sets the caption text on the column's header cell.<br />(Inherited from DataGridViewColumn)</td></tr>
<tr>
<td><a href="040bedbd-54c5-e613-cb1e-44ed23090eb9.md">IconSpecs</a></td>
<td>Gets the collection of the icon specifications.<br />(Inherited from <a href="21f6015d-1ab5-4482-8193-6cf4882c3abf.md">KryptonDataGridViewIconColumn</a>)</td></tr>
<tr>
<td>Index</td>
<td>Gets the relative position of the band within the DataGridView control.<br />(Inherited from DataGridViewBand)</td></tr>
<tr>
<td>InheritedAutoSizeMode</td>
<td>Gets the sizing mode in effect for the column.<br />(Inherited from DataGridViewColumn)</td></tr>
<tr>
<td>InheritedStyle</td>
<td>Gets the cell style currently applied to the column.<br />(Inherited from DataGridViewColumn)</td></tr>
<tr>
<td>IsDataBound</td>
<td>Gets a value indicating whether the column is bound to a data source.<br />(Inherited from DataGridViewColumn)</td></tr>
<tr>
<td>IsRow</td>
<td>Gets a value indicating whether the band represents a row.<br />(Inherited from DataGridViewBand)</td></tr>
<tr>
<td><a href="e79cc4da-94e6-f5c5-6b2f-a4dab287a1e2.md">LabelStyle</a></td>
<td>Gets or sets the default label style of link cell.</td></tr>
<tr>
<td><a href="08674dec-b61b-ec2c-abac-085882b47a01.md">LinkBehavior</a></td>
<td>Gets or sets a value that represents the behavior of links within cells in the column.</td></tr>
<tr>
<td>MinimumWidth</td>
<td>Gets or sets the minimum width, in pixels, of the column.<br />(Inherited from DataGridViewColumn)</td></tr>
<tr>
<td>Name</td>
<td>Gets or sets the name of the column.<br />(Inherited from DataGridViewColumn)</td></tr>
<tr>
<td>ReadOnly</td>
<td>Gets or sets a value indicating whether the user can edit the column's cells.<br />(Inherited from DataGridViewColumn)</td></tr>
<tr>
<td>Resizable</td>
<td>Gets or sets a value indicating whether the column is resizable.<br />(Inherited from DataGridViewColumn)</td></tr>
<tr>
<td>Selected</td>
<td>Gets or sets a value indicating whether the band is in a selected user interface (UI) state.<br />(Inherited from DataGridViewBand)</td></tr>
<tr>
<td>Site</td>
<td>Gets or sets the site of the column.<br />(Inherited from DataGridViewColumn)</td></tr>
<tr>
<td>SortMode</td>
<td>Gets or sets the sort mode for the column.<br />(Inherited from DataGridViewColumn)</td></tr>
<tr>
<td>State</td>
<td>Gets the user interface (UI) state of the element.<br />(Inherited from DataGridViewElement)</td></tr>
<tr>
<td>Tag</td>
<td>Gets or sets the object that contains data to associate with the band.<br />(Inherited from DataGridViewBand)</td></tr>
<tr>
<td><a href="8f45cfbb-a2a5-e26c-4f6a-e842fba9778a.md">Text</a></td>
<td>Gets or sets the default text Displayed on the link cell.</td></tr>
<tr>
<td>ToolTipText</td>
<td>Gets or sets the text used for ToolTips.<br />(Inherited from DataGridViewColumn)</td></tr>
<tr>
<td><a href="0dded82a-6ab4-fd92-7205-20d518da9dbe.md">TrackVisitedState</a></td>
<td>Gets or sets a value indicating whether the link changes color when it is visited.</td></tr>
<tr>
<td><a href="d457d034-e45f-9197-5ad3-7ef53e96104b.md">UseColumnTextForLinkValue</a></td>
<td>Gets or sets a value indicating whether the Text property value is Displayed as the link text for cells in this column.</td></tr>
<tr>
<td>ValueType</td>
<td>Gets or sets the data type of the values in the column's cells.<br />(Inherited from DataGridViewColumn)</td></tr>
<tr>
<td>Visible</td>
<td>Gets or sets a value indicating whether the column is visible.<br />(Inherited from DataGridViewColumn)</td></tr>
<tr>
<td>Width</td>
<td>Gets or sets the current width of the column.<br />(Inherited from DataGridViewColumn)</td></tr>
</table>

## Methods
<table>
<tr>
<td><a href="35dd0192-c7ae-b51f-6095-a634205aca4b.md">Clone</a></td>
<td>This member overrides DataGridViewButtonColumn.Clone.<br />(Overrides <a href="2c225d0c-ac0d-d52c-a7d5-7427b6930106.md">KryptonDataGridViewIconColumn.Clone()</a>)</td></tr>
<tr>
<td>Dispose()</td>
<td>Releases all resources used by the DataGridViewBand.<br />(Inherited from DataGridViewBand)</td></tr>
<tr>
<td>Dispose(Boolean)</td>
<td>Releases the unmanaged resources used by the DataGridViewBand and optionally releases the managed resources.<br />(Inherited from DataGridViewColumn)</td></tr>
<tr>
<td>Equals</td>
<td>Determines whether the specified object is equal to the current object.<br />(Inherited from Object)</td></tr>
<tr>
<td>Finalize</td>
<td>Releases the resources associated with the band.<br />(Inherited from DataGridViewBand)</td></tr>
<tr>
<td>GetHashCode</td>
<td>Serves as the default hash function.<br />(Inherited from Object)</td></tr>
<tr>
<td>GetPreferredWidth</td>
<td>Calculates the ideal width of the column based on the specified criteria.<br />(Inherited from DataGridViewColumn)</td></tr>
<tr>
<td>GetType</td>
<td>Gets the Type of the current instance.<br />(Inherited from Object)</td></tr>
<tr>
<td>MemberwiseClone</td>
<td>Creates a shallow copy of the current Object.<br />(Inherited from Object)</td></tr>
<tr>
<td>OnDataGridViewChanged</td>
<td>Called when the band is associated with a different DataGridView.<br />(Inherited from DataGridViewBand)</td></tr>
<tr>
<td>RaiseCellClick</td>
<td>Raises the CellClick event.<br />(Inherited from DataGridViewElement)</td></tr>
<tr>
<td>RaiseCellContentClick</td>
<td>Raises the CellContentClick event.<br />(Inherited from DataGridViewElement)</td></tr>
<tr>
<td>RaiseCellContentDoubleClick</td>
<td>Raises the CellContentDoubleClick event.<br />(Inherited from DataGridViewElement)</td></tr>
<tr>
<td>RaiseCellValueChanged</td>
<td>Raises the CellValueChanged event.<br />(Inherited from DataGridViewElement)</td></tr>
<tr>
<td>RaiseDataError</td>
<td>Raises the DataError event.<br />(Inherited from DataGridViewElement)</td></tr>
<tr>
<td>RaiseMouseWheel</td>
<td>Raises the MouseWheel event.<br />(Inherited from DataGridViewElement)</td></tr>
<tr>
<td><a href="c457da9f-6f04-5de4-c4fd-d7f1393a4733.md">ToString</a></td>
<td>Returns a String that represents the current Object.<br />(Overrides DataGridViewColumn.ToString())</td></tr>
</table>

## Events
<table>
<tr>
<td>Disposed</td>
<td>Occurs when the DataGridViewColumn is disposed.<br />(Inherited from DataGridViewColumn)</td></tr>
</table>

## See Also


#### Reference
<a href="79d2eac2-21f4-54ff-7552-b20c33c30600.md">Krypton.Toolkit Namespace</a>  
