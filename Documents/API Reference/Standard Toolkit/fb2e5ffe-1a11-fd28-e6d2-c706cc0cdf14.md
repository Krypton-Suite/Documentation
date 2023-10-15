# KryptonControlCollection Class


Base class for krypton specific control collections.



## Definition
**Namespace:** <a href="79d2eac2-21f4-54ff-7552-b20c33c30600.md">Krypton.Toolkit</a>  
**Assembly:** Krypton.Toolkit (in Krypton.Toolkit.dll) Version: 80.23.10.287+8d7660f9dc5efd033fabe008ebfb904beab6d444

**C#**
``` C#
public class KryptonControlCollection : Control.ControlCollection
```
**VB**
``` VB
Public Class KryptonControlCollection
	Inherits Control.ControlCollection
```

<table><tr><td><strong>Inheritance</strong></td><td>Object  →  ArrangedElementCollection  →  Control.ControlCollection  →  KryptonControlCollection</td></tr>
<tr><td><strong>Derived</strong></td><td><a href="e47799f9-df1c-39e9-3be8-dc25877312de.md">Krypton.Navigator.KryptonNavigatorControlCollection</a><br /><a href="b418cb55-7d6e-a665-d48f-6a7500dc5687.md">Krypton.Toolkit.KryptonReadOnlyControls</a></td></tr>
</table>



## Constructors
<table>
<tr>
<td><a href="481bf9d4-e5be-2432-ff2f-0a9f1f974e57.md">KryptonControlCollection</a></td>
<td>Initialize a new instance of the KryptonControlCollection class.</td></tr>
</table>

## Properties
<table>
<tr>
<td>Count</td>
<td>Gets the number of elements in the collection.<br />(Inherited from ArrangedElementCollection)</td></tr>
<tr>
<td>IsReadOnly</td>
<td>Gets a value indicating whether the collection is read-only.<br />(Inherited from ArrangedElementCollection)</td></tr>
<tr>
<td>Item(Int32)</td>
<td>Indicates the Control at the specified indexed location in the collection.<br />(Inherited from Control.ControlCollection)</td></tr>
<tr>
<td>Item(String)</td>
<td>Indicates a Control with the specified key in the collection.<br />(Inherited from Control.ControlCollection)</td></tr>
<tr>
<td>Owner</td>
<td>Gets the control that owns this Control.ControlCollection.<br />(Inherited from Control.ControlCollection)</td></tr>
</table>

## Methods
<table>
<tr>
<td>Add</td>
<td>Adds the specified control to the control collection.<br />(Inherited from Control.ControlCollection)</td></tr>
<tr>
<td>AddRange</td>
<td>Adds an array of control objects to the collection.<br />(Inherited from Control.ControlCollection)</td></tr>
<tr>
<td>Clear</td>
<td>Removes all controls from the collection.<br />(Inherited from Control.ControlCollection)</td></tr>
<tr>
<td>Contains</td>
<td>Determines whether the specified control is a member of the collection.<br />(Inherited from Control.ControlCollection)</td></tr>
<tr>
<td>ContainsKey</td>
<td>Determines whether the Control.ControlCollection contains an item with the specified key.<br />(Inherited from Control.ControlCollection)</td></tr>
<tr>
<td>CopyTo</td>
<td>Copies the entire contents of this collection to a compatible one-dimensional Array, starting at the specified index of the target array.<br />(Inherited from ArrangedElementCollection)</td></tr>
<tr>
<td>Equals</td>
<td>Determines whether two ArrangedElementCollection instances are equal.<br />(Inherited from ArrangedElementCollection)</td></tr>
<tr>
<td>Finalize</td>
<td>Allows an object to try to free resources and perform other cleanup operations before it is reclaimed by garbage collection.<br />(Inherited from Object)</td></tr>
<tr>
<td>Find</td>
<td>Searches for controls by their Name property and builds an array of all the controls that match.<br />(Inherited from Control.ControlCollection)</td></tr>
<tr>
<td>GetChildIndex(Control)</td>
<td>Retrieves the index of the specified child control within the control collection.<br />(Inherited from Control.ControlCollection)</td></tr>
<tr>
<td>GetChildIndex(Control, Boolean)</td>
<td>Retrieves the index of the specified child control within the control collection, and optionally raises an exception if the specified control is not within the control collection.<br />(Inherited from Control.ControlCollection)</td></tr>
<tr>
<td>GetEnumerator</td>
<td>Retrieves a reference to an enumerator object that is used to iterate over a Control.ControlCollection.<br />(Inherited from Control.ControlCollection)</td></tr>
<tr>
<td>GetHashCode</td>
<td>Returns the hash code for this instance.<br />(Inherited from ArrangedElementCollection)</td></tr>
<tr>
<td>GetType</td>
<td>Gets the Type of the current instance.<br />(Inherited from Object)</td></tr>
<tr>
<td>IndexOf</td>
<td>Retrieves the index of the specified control in the control collection.<br />(Inherited from Control.ControlCollection)</td></tr>
<tr>
<td>IndexOfKey</td>
<td>Retrieves the index of the first occurrence of the specified item within the collection.<br />(Inherited from Control.ControlCollection)</td></tr>
<tr>
<td>MemberwiseClone</td>
<td>Creates a shallow copy of the current Object.<br />(Inherited from Object)</td></tr>
<tr>
<td>Remove</td>
<td>Removes the specified control from the control collection.<br />(Inherited from Control.ControlCollection)</td></tr>
<tr>
<td>RemoveAt</td>
<td>Removes a control from the control collection at the specified indexed location.<br />(Inherited from Control.ControlCollection)</td></tr>
<tr>
<td>RemoveByKey</td>
<td>Removes the child control with the specified key.<br />(Inherited from Control.ControlCollection)</td></tr>
<tr>
<td>SetChildIndex</td>
<td>Sets the index of the specified child control in the collection to the specified index value.<br />(Inherited from Control.ControlCollection)</td></tr>
<tr>
<td>ToString</td>
<td>Returns a string that represents the current object.<br />(Inherited from Object)</td></tr>
</table>

## See Also


#### Reference
<a href="79d2eac2-21f4-54ff-7552-b20c33c30600.md">Krypton.Toolkit Namespace</a>  
