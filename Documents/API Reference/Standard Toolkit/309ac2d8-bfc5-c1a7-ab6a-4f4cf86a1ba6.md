# ViewBase Class


Base class from which all view types derive.



## Definition
**Namespace:** <a href="79d2eac2-21f4-54ff-7552-b20c33c30600.md">Krypton.Toolkit</a>  
**Assembly:** Krypton.Toolkit (in Krypton.Toolkit.dll) Version: 80.23.10.287+8d7660f9dc5efd033fabe008ebfb904beab6d444

**C#**
``` C#
public abstract class ViewBase : GlobalId, 
	IDisposable, IList<ViewBase>, ICollection<ViewBase>, 
	IEnumerable<ViewBase>, IEnumerable
```
**VB**
``` VB
Public MustInherit Class ViewBase
	Inherits GlobalId
	Implements IDisposable, IList(Of ViewBase), 
	ICollection(Of ViewBase), IEnumerable(Of ViewBase), IEnumerable
```

<table><tr><td><strong>Inheritance</strong></td><td>Object  →  TypeConverter  →  ExpandableObjectConverter  →  <a href="9ef2ca3a-e03e-8927-105a-2f9a6fbdf849.md">GlobalId</a>  →  ViewBase</td></tr>
<tr><td><strong>Derived</strong></td><td><a href="467f805c-296b-06ec-42f1-e965af0d0f04.md">Krypton.Toolkit.ViewComposite</a><br /><a href="5bfdac14-2f95-17b3-c641-94bca28b9f8c.md">Krypton.Toolkit.ViewDecorator</a><br /><a href="5fd2165a-8129-c3a0-963b-890d1eb48565.md">Krypton.Toolkit.ViewLeaf</a></td></tr>
<tr><td><strong>Implements</strong></td><td>ICollection(ViewBase), IEnumerable(ViewBase), IList(ViewBase), IEnumerable, IDisposable</td></tr>
</table>



## Constructors
<table>
<tr>
<td><a href="85895f29-df7a-59a3-6f9a-559a2ecc1f5c.md">ViewBase</a></td>
<td>Initialize a new instance of the ViewBase class.</td></tr>
</table>

## Properties
<table>
<tr>
<td><a href="8ca1086e-f2a1-e3aa-0550-e17de8d4d705.md">ClientHeight</a></td>
<td>Gets and sets the height of the view.</td></tr>
<tr>
<td><a href="adf2b0f9-71eb-d32c-2ec0-ac09568593fa.md">ClientLocation</a></td>
<td>Gets and sets the location of the view inside the parent view.</td></tr>
<tr>
<td><a href="26daf885-2412-02b5-dc52-e6e5f8121280.md">ClientRectangle</a></td>
<td>Gets and sets the rectangle bounding the client area.</td></tr>
<tr>
<td><a href="aab48de6-57c1-8040-9e53-80d7379b3269.md">ClientRectangleF</a></td>
<td> </td></tr>
<tr>
<td><a href="c7ce4247-0421-c87f-bef9-93ca9c8d0710.md">ClientSize</a></td>
<td>Gets and sets the size of the view.</td></tr>
<tr>
<td><a href="8e43df91-01e4-3d85-b2c7-6f37025e7632.md">ClientWidth</a></td>
<td>Gets and sets the width of the view.</td></tr>
<tr>
<td><a href="a0853610-b2de-7dec-2285-f2d884fc0231.md">Component</a></td>
<td>Gets the component associated with the element.</td></tr>
<tr>
<td><a href="6d876c80-aa75-bf56-696a-8d604371aa20.md">Count</a></td>
<td>Gets the number of views in collection.</td></tr>
<tr>
<td><a href="45b74146-9308-269a-0625-9558884a95b2.md">DependantEnabledState</a></td>
<td>Get and set the view the enabled state of this view element is dependant on.</td></tr>
<tr>
<td><a href="1631dbf1-7432-b0c3-508a-cc76fd85b428.md">ElementState</a></td>
<td>Gets and sets the visual state of the element.</td></tr>
<tr>
<td><a href="ab081600-b6ff-5a6b-58b1-096a470ecd35.md">Enabled</a></td>
<td>Gets and sets the enabled state of the element.</td></tr>
<tr>
<td><a href="026ae658-3cdc-1c85-8625-fc598f0183a8.md">FactorDpiX</a></td>
<td>Gets the DpiX of the view.</td></tr>
<tr>
<td><a href="0c4492bd-aee6-2147-f951-fcd5893011ed.md">FactorDpiY</a></td>
<td>Gets the DpiY of the view.</td></tr>
<tr>
<td><a href="428afb96-cbad-d267-10d1-93533a7f9589.md">FixedState</a></td>
<td>Set a fixed state to override usual behavior and appearance</td></tr>
<tr>
<td><a href="71a6846f-bfb6-fb58-b361-6b43ae0583a8.md">Id</a></td>
<td>Gets the unique identifier of the object.<br />(Inherited from <a href="9ef2ca3a-e03e-8927-105a-2f9a6fbdf849.md">GlobalId</a>)</td></tr>
<tr>
<td><a href="b8132097-e81f-af8f-9edb-3cb79ba26d45.md">IsDisposed</a></td>
<td>Gets a value indicating if the view has been disposed.</td></tr>
<tr>
<td><a href="2051812a-d6aa-0b59-07f6-d0aaf5425a45.md">IsEnableDependant</a></td>
<td>Gets a value indicating if view enabled state is dependent on another view.</td></tr>
<tr>
<td><a href="ae00d504-ee78-dc0c-547f-47ccf010c8f3.md">IsFixed</a></td>
<td>Gets a value indicating if view is using a fixed state.</td></tr>
<tr>
<td><a href="1359c544-d62a-40dc-68ae-2cf918c7cb0c.md">IsReadOnly</a></td>
<td>Gets a value indicating whether the collection is read-only.</td></tr>
<tr>
<td><a href="2ae1d790-b155-9872-2cf3-4682570e1eba.md">Item</a></td>
<td>Gets or sets the view at the specified index.</td></tr>
<tr>
<td><a href="8c0c18fc-2c53-4c1c-c120-964c3bc82e99.md">KeyController</a></td>
<td>Gets and sets the associated key controller.</td></tr>
<tr>
<td><a href="d5761a42-75a6-b244-b305-631dbf54d295.md">MouseController</a></td>
<td>Gets and sets the associated mouse controller.</td></tr>
<tr>
<td><a href="c732fcd5-3e0d-98cb-17df-e574d4733f53.md">OwningControl</a></td>
<td>Gets and sets a reference to the control instance that contains this view element.</td></tr>
<tr>
<td><a href="b34c2e84-eb23-0078-5656-e854d6f41638.md">Parent</a></td>
<td>Gets the parent view.</td></tr>
<tr>
<td><a href="354d206d-5772-7294-dc86-25ae526ef09d.md">SourceController</a></td>
<td>Gets and sets the associated source controller.</td></tr>
<tr>
<td><a href="97b91260-605d-f086-e86c-7ad32f06d42b.md">State</a></td>
<td>Gets the visual state taking into account the owning controls state.</td></tr>
<tr>
<td><a href="c6f3a2c1-5079-abb9-07ab-be74628e34be.md">Visible</a></td>
<td>Gets and sets the enabled state of the element.</td></tr>
</table>

## Methods
<table>
<tr>
<td><a href="e289d32b-5415-ca6c-5f9a-5500d799503a.md">Add</a></td>
<td>Append a view to the collection.</td></tr>
<tr>
<td>CanConvertFrom(Type)</td>
<td>Returns whether this converter can convert an object of the given type to the type of this converter.<br />(Inherited from TypeConverter)</td></tr>
<tr>
<td>CanConvertFrom(ITypeDescriptorContext, Type)</td>
<td>Returns whether this converter can convert an object of the given type to the type of this converter, using the specified context.<br />(Inherited from TypeConverter)</td></tr>
<tr>
<td>CanConvertTo(Type)</td>
<td>Returns whether this converter can convert the object to the specified type.<br />(Inherited from TypeConverter)</td></tr>
<tr>
<td>CanConvertTo(ITypeDescriptorContext, Type)</td>
<td>Returns whether this converter can convert the object to the specified type, using the specified context.<br />(Inherited from TypeConverter)</td></tr>
<tr>
<td><a href="788ee9d5-9663-da93-da9d-071c3a049f9b.md">Clear</a></td>
<td>Remove all views from the collection.</td></tr>
<tr>
<td><a href="07da82a4-8c30-f77f-1a25-29fcbbc3b028.md">ClearFixedState</a></td>
<td>Clear down the use of the fixed state</td></tr>
<tr>
<td><a href="533b860a-849d-6576-7b74-6718097aa51c.md">Contains</a></td>
<td>Determines whether the collection contains the view.</td></tr>
<tr>
<td><a href="5911ba18-61e9-5338-ee4d-10e470040668.md">ContainsRecurse</a></td>
<td>Determines whether any part of the view hierarchy is the specified view.</td></tr>
<tr>
<td>ConvertFrom(Object)</td>
<td>Converts the given value to the type of this converter.<br />(Inherited from TypeConverter)</td></tr>
<tr>
<td>ConvertFrom(ITypeDescriptorContext, CultureInfo, Object)</td>
<td>Converts the given object to the type of this converter, using the specified context and culture information.<br />(Inherited from TypeConverter)</td></tr>
<tr>
<td>ConvertFromInvariantString(String)</td>
<td>Converts the given string to the type of this converter, using the invariant culture.<br />(Inherited from TypeConverter)</td></tr>
<tr>
<td>ConvertFromInvariantString(ITypeDescriptorContext, String)</td>
<td>Converts the given string to the type of this converter, using the invariant culture and the specified context.<br />(Inherited from TypeConverter)</td></tr>
<tr>
<td>ConvertFromString(String)</td>
<td>Converts the specified text to an object.<br />(Inherited from TypeConverter)</td></tr>
<tr>
<td>ConvertFromString(ITypeDescriptorContext, String)</td>
<td>Converts the given text to an object, using the specified context.<br />(Inherited from TypeConverter)</td></tr>
<tr>
<td>ConvertFromString(ITypeDescriptorContext, CultureInfo, String)</td>
<td>Converts the given text to an object, using the specified context and culture information.<br />(Inherited from TypeConverter)</td></tr>
<tr>
<td>ConvertTo(Object, Type)</td>
<td>Converts the given value object to the specified type, using the arguments.<br />(Inherited from TypeConverter)</td></tr>
<tr>
<td>ConvertTo(ITypeDescriptorContext, CultureInfo, Object, Type)</td>
<td>Converts the given value object to the specified type, using the specified context and culture information.<br />(Inherited from TypeConverter)</td></tr>
<tr>
<td>ConvertToInvariantString(Object)</td>
<td>Converts the specified value to a culture-invariant string representation.<br />(Inherited from TypeConverter)</td></tr>
<tr>
<td>ConvertToInvariantString(ITypeDescriptorContext, Object)</td>
<td>Converts the specified value to a culture-invariant string representation, using the specified context.<br />(Inherited from TypeConverter)</td></tr>
<tr>
<td>ConvertToString(Object)</td>
<td>Converts the specified value to a string representation.<br />(Inherited from TypeConverter)</td></tr>
<tr>
<td>ConvertToString(ITypeDescriptorContext, Object)</td>
<td>Converts the given value to a string representation, using the given context.<br />(Inherited from TypeConverter)</td></tr>
<tr>
<td>ConvertToString(ITypeDescriptorContext, CultureInfo, Object)</td>
<td>Converts the given value to a string representation, using the specified context and culture information.<br />(Inherited from TypeConverter)</td></tr>
<tr>
<td><a href="a7bc3db2-f559-6a05-afe6-799b3d37f5ac.md">CopyTo</a></td>
<td>Copies views to specified array starting at particular index.</td></tr>
<tr>
<td>CreateInstance(IDictionary)</td>
<td>Re-creates an Object given a set of property values for the object.<br />(Inherited from TypeConverter)</td></tr>
<tr>
<td>CreateInstance(ITypeDescriptorContext, IDictionary)</td>
<td>Creates an instance of the type that this TypeConverter is associated with, using the specified context, given a set of property values for the object.<br />(Inherited from TypeConverter)</td></tr>
<tr>
<td><a href="56e77af8-2279-414f-d419-9e0428f318da.md">Dispose()</a></td>
<td>Release managed and unmanaged resources.</td></tr>
<tr>
<td><a href="7ca2f86d-2f69-4d14-c97d-85f0a27272af.md">Dispose(Boolean)</a></td>
<td>Release unmanaged and optionally managed resources.</td></tr>
<tr>
<td><a href="95398135-79d1-2dcf-a20f-c6ff362ade91.md">DoubleClick</a></td>
<td>Left mouse button has been double clicked.</td></tr>
<tr>
<td>Equals</td>
<td>Determines whether the specified object is equal to the current object.<br />(Inherited from Object)</td></tr>
<tr>
<td><a href="04c0ed13-8242-119a-b145-12abfdc0841b.md">EvalTransparentPaint</a></td>
<td>Evaluate the need for drawing transparent areas.</td></tr>
<tr>
<td><a href="906b1d4f-3979-9407-ae58-de235976e067.md">Finalize</a></td>
<td>Release resources.<br />(Overrides Object.Finalize())</td></tr>
<tr>
<td><a href="fa2eff88-157f-82f0-361c-8adb76577c30.md">FindMouseController</a></td>
<td>Mouse has entered the view.</td></tr>
<tr>
<td>GetConvertFromException</td>
<td>Returns an exception to throw when a conversion cannot be performed.<br />(Inherited from TypeConverter)</td></tr>
<tr>
<td>GetConvertToException</td>
<td>Returns an exception to throw when a conversion cannot be performed.<br />(Inherited from TypeConverter)</td></tr>
<tr>
<td>GetCreateInstanceSupported()</td>
<td>Returns whether changing a value on this object requires a call to the CreateInstance(IDictionary) method to create a new value.<br />(Inherited from TypeConverter)</td></tr>
<tr>
<td>GetCreateInstanceSupported(ITypeDescriptorContext)</td>
<td>Returns whether changing a value on this object requires a call to CreateInstance(IDictionary) to create a new value, using the specified context.<br />(Inherited from TypeConverter)</td></tr>
<tr>
<td><a href="6afea767-f15f-1be4-9f5f-1cc7ec56ed21.md">GetEnumerator</a></td>
<td>Shallow enumerate forward over children of the element.</td></tr>
<tr>
<td>GetHashCode</td>
<td>Serves as the default hash function.<br />(Inherited from Object)</td></tr>
<tr>
<td><a href="9d104908-676e-3601-1d35-e082205664a7.md">GetPreferredSize</a></td>
<td>Discover the preferred size of the element.</td></tr>
<tr>
<td>GetProperties(Object)</td>
<td>Returns a collection of properties for the type of array specified by the value parameter.<br />(Inherited from TypeConverter)</td></tr>
<tr>
<td>GetProperties(ITypeDescriptorContext, Object)</td>
<td>Returns a collection of properties for the type of array specified by the value parameter, using the specified context.<br />(Inherited from TypeConverter)</td></tr>
<tr>
<td>GetProperties(ITypeDescriptorContext, Object, Attribute[])</td>
<td>Gets a collection of properties for the type of object specified by the value parameter.<br />(Inherited from ExpandableObjectConverter)</td></tr>
<tr>
<td>GetPropertiesSupported()</td>
<td>Returns whether this object supports properties.<br />(Inherited from TypeConverter)</td></tr>
<tr>
<td>GetPropertiesSupported(ITypeDescriptorContext)</td>
<td>Gets a value indicating whether this object supports properties using the specified context.<br />(Inherited from ExpandableObjectConverter)</td></tr>
<tr>
<td>GetStandardValues()</td>
<td>Returns a collection of standard values from the default context for the data type this type converter is designed for.<br />(Inherited from TypeConverter)</td></tr>
<tr>
<td>GetStandardValues(ITypeDescriptorContext)</td>
<td>Returns a collection of standard values for the data type this type converter is designed for when provided with a format context.<br />(Inherited from TypeConverter)</td></tr>
<tr>
<td>GetStandardValuesExclusive()</td>
<td>Returns whether the collection of standard values returned from GetStandardValues() is an exclusive list.<br />(Inherited from TypeConverter)</td></tr>
<tr>
<td>GetStandardValuesExclusive(ITypeDescriptorContext)</td>
<td>Returns whether the collection of standard values returned from GetStandardValues() is an exclusive list of possible values, using the specified context.<br />(Inherited from TypeConverter)</td></tr>
<tr>
<td>GetStandardValuesSupported()</td>
<td>Returns whether this object supports a standard set of values that can be picked from a list.<br />(Inherited from TypeConverter)</td></tr>
<tr>
<td>GetStandardValuesSupported(ITypeDescriptorContext)</td>
<td>Returns whether this object supports a standard set of values that can be picked from a list, using the specified context.<br />(Inherited from TypeConverter)</td></tr>
<tr>
<td>GetType</td>
<td>Gets the Type of the current instance.<br />(Inherited from Object)</td></tr>
<tr>
<td><a href="5cb28b55-86bb-f1da-3c6f-dfb902f2b452.md">GotFocus</a></td>
<td>Source control has got the focus.</td></tr>
<tr>
<td><a href="6e57a51c-d1ef-f0ba-cf1b-fea08a474499.md">IndexOf</a></td>
<td>Determines the index of the specified view in the collection.</td></tr>
<tr>
<td><a href="286d59a5-799e-884a-f469-26f22a4b7692.md">Insert</a></td>
<td>Inserts a view to the collection at the specified index.</td></tr>
<tr>
<td>IsValid(Object)</td>
<td>Returns whether the given value object is valid for this type.<br />(Inherited from TypeConverter)</td></tr>
<tr>
<td>IsValid(ITypeDescriptorContext, Object)</td>
<td>Returns whether the given value object is valid for this type and for the specified context.<br />(Inherited from TypeConverter)</td></tr>
<tr>
<td><a href="375695e4-351a-d41e-2a9c-849557307230.md">KeyDown</a></td>
<td>Key has been pressed down.</td></tr>
<tr>
<td><a href="b20e4dcf-0fd8-7bb5-03a8-0c77b0168719.md">KeyPress</a></td>
<td>Key has been pressed.</td></tr>
<tr>
<td><a href="0ee22a65-620c-6f78-ab66-7af58ee22bc3.md">KeyUp</a></td>
<td>Key has been released.</td></tr>
<tr>
<td><a href="f29deeb6-c5bd-6dc1-3bb9-ee317c67bb24.md">Layout</a></td>
<td>Perform a layout of the elements.</td></tr>
<tr>
<td><a href="70dabc71-fb88-4c6f-8428-7c3ef87e8351.md">LostFocus</a></td>
<td>Source control has lost the focus.</td></tr>
<tr>
<td>MemberwiseClone</td>
<td>Creates a shallow copy of the current Object.<br />(Inherited from Object)</td></tr>
<tr>
<td><a href="f85042cd-bd95-bd0e-2bf4-46cdc723c1af.md">MouseDown</a></td>
<td>Mouse button has been pressed in the view.</td></tr>
<tr>
<td><a href="38bba82f-9309-fc1b-1525-9f3f606bddfb.md">MouseEnter</a></td>
<td>Mouse has entered the view.</td></tr>
<tr>
<td><a href="3f0f21f8-e7fe-e45b-44b8-b5729b578e83.md">MouseLeave</a></td>
<td>Mouse has left the view.</td></tr>
<tr>
<td><a href="3891df9a-e10f-835d-bf0c-8e6d87e22df8.md">MouseMove</a></td>
<td>Mouse has moved inside the view.</td></tr>
<tr>
<td><a href="7ec191d5-ec44-9277-55cf-37ad06e7bfa4.md">MouseUp</a></td>
<td>Mouse button has been released in the view.</td></tr>
<tr>
<td><a href="22d165ea-0221-3079-0c24-6a70e59e3c9e.md">Recurse</a></td>
<td>Deep enumerate forward over children of the element.</td></tr>
<tr>
<td><a href="6f2c5598-cb9c-2efa-434a-2834efa431bf.md">Remove</a></td>
<td>Removes first occurrence of specified view.</td></tr>
<tr>
<td><a href="39b163d5-65b2-7814-a177-a0e4649f6f2e.md">RemoveAt</a></td>
<td>Removes the view at the specified index.</td></tr>
<tr>
<td><a href="2f8809c0-58d8-c2cd-6764-40bd5ed1bd67.md">Render</a></td>
<td>Perform a render of the elements.</td></tr>
<tr>
<td><a href="0d72a0f3-fa00-f3f2-5015-7242f2b1ed8d.md">RenderAfter</a></td>
<td>Perform rendering after child elements are rendered.</td></tr>
<tr>
<td><a href="0a5f30f4-0b1b-cf5e-adb7-1fab2b73a1d2.md">RenderBefore</a></td>
<td>Perform rendering before child elements are rendered.</td></tr>
<tr>
<td><a href="7651909a-b15b-986a-2d8a-9d33ccb451ce.md">Reverse</a></td>
<td>Shallow enumerate backwards over children of the element.</td></tr>
<tr>
<td><a href="52b3e8ae-d012-0270-63ce-ff6c9b5dbd94.md">ReverseRecurse</a></td>
<td>Deep enumerate backwards over children of the element.</td></tr>
<tr>
<td>SortProperties</td>
<td>Sorts a collection of properties.<br />(Inherited from TypeConverter)</td></tr>
<tr>
<td><a href="40106e64-63b0-4bab-1e07-4eb6689b30cc.md">ToString</a></td>
<td>Obtains the String representation of this instance.<br />(Overrides Object.ToString())</td></tr>
<tr>
<td><a href="92b234bc-72ad-cb8a-5253-f9ac9632b4ea.md">ViewFromPoint</a></td>
<td>Find the view that contains the specified point.</td></tr>
</table>

## See Also


#### Reference
<a href="79d2eac2-21f4-54ff-7552-b20c33c30600.md">Krypton.Toolkit Namespace</a>  
