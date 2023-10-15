# PaletteContextMenuRedirect Class


Redirect storage for KryptonContextMenu common values.



## Definition
**Namespace:** <a href="79d2eac2-21f4-54ff-7552-b20c33c30600.md">Krypton.Toolkit</a>  
**Assembly:** Krypton.Toolkit (in Krypton.Toolkit.dll) Version: 80.23.10.287+8d7660f9dc5efd033fabe008ebfb904beab6d444

**C#**
``` C#
public class PaletteContextMenuRedirect : Storage
```
**VB**
``` VB
Public Class PaletteContextMenuRedirect
	Inherits Storage
```

<table><tr><td><strong>Inheritance</strong></td><td>Object  →  TypeConverter  →  ExpandableObjectConverter  →  <a href="9ef2ca3a-e03e-8927-105a-2f9a6fbdf849.md">GlobalId</a>  →  <a href="8406cf55-79a3-e579-4094-be084e489431.md">Storage</a>  →  PaletteContextMenuRedirect</td></tr>
</table>



## Constructors
<table>
<tr>
<td><a href="1cfc1a60-9d96-0296-45b8-2ff3a85d87cf.md">PaletteContextMenuRedirect</a></td>
<td>Initialize a new instance of the PaletteContextMenuRedirect class.</td></tr>
</table>

## Properties
<table>
<tr>
<td><a href="86b15b06-f926-b329-0c43-5391b393d84b.md">ControlInner</a></td>
<td>Gets access to the inner control window appearance entries.</td></tr>
<tr>
<td><a href="0f09f6f0-d0e8-0315-f2b3-ac77ef1dfcc3.md">ControlOuter</a></td>
<td>Gets access to the outer control window appearance entries.</td></tr>
<tr>
<td><a href="8f8a41e8-bf9d-6120-fc60-ddceebc9932f.md">HasShadow</a></td>
<td>Gets access to the outer control window appearance entries.</td></tr>
<tr>
<td><a href="b4164085-738d-f693-270c-f505d17ca470.md">Heading</a></td>
<td>Gets access to the heading entry appearance entries.</td></tr>
<tr>
<td><a href="71a6846f-bfb6-fb58-b361-6b43ae0583a8.md">Id</a></td>
<td>Gets the unique identifier of the object.<br />(Inherited from <a href="9ef2ca3a-e03e-8927-105a-2f9a6fbdf849.md">GlobalId</a>)</td></tr>
<tr>
<td><a href="3bc9cab0-0a1a-8abd-1986-31f28d5a29de.md">IsDefault</a></td>
<td>Gets a value indicating if all values are default.<br />(Overrides <a href="bbc0e831-9474-3bce-65dc-0625d793d8c1.md">Storage.IsDefault</a>)</td></tr>
<tr>
<td><a href="35b37ff0-c1cd-78fc-6745-fc06c8e3a037.md">ItemHighlight</a></td>
<td>Gets access to the item highlight appearance entries.</td></tr>
<tr>
<td><a href="f8a9f246-314b-0800-74d4-ce076d787e29.md">ItemImage</a></td>
<td>Gets access to the item image appearance entries.</td></tr>
<tr>
<td><a href="1bd25933-e568-b8bc-2b69-90d77f3d8628.md">ItemImageColumn</a></td>
<td>Gets access to the item image column appearance entries.</td></tr>
<tr>
<td><a href="b2cc0684-fb0a-9b53-4d45-79181a00c6f6.md">ItemShortcutText</a></td>
<td>Gets access to the item shortcut text appearance entries.</td></tr>
<tr>
<td><a href="636021ec-51ca-e78f-9eba-7c441766a8f2.md">ItemSplit</a></td>
<td>Gets access to the item split appearance entries.</td></tr>
<tr>
<td><a href="43291a93-0ffe-0cbd-182f-a9fc6f83406d.md">ItemTextAlternate</a></td>
<td>Gets access to the alternate item text appearance entries.</td></tr>
<tr>
<td><a href="5b87f376-b1c1-3815-6e1b-96dd4da4ff98.md">ItemTextStandard</a></td>
<td>Gets access to the standard item text appearance entries.</td></tr>
<tr>
<td><a href="097a0f47-e60c-4bf7-802c-8391c6d8feff.md">NeedPaint</a></td>
<td>Gets and sets the need paint delegate for notifying paint requests.<br />(Inherited from <a href="8406cf55-79a3-e579-4094-be084e489431.md">Storage</a>)</td></tr>
<tr>
<td><a href="879ca7f2-32c5-8581-44f2-c7aee6491db2.md">NeedPaintDelegate</a></td>
<td>Gets access to the need paint delegate.<br />(Inherited from <a href="8406cf55-79a3-e579-4094-be084e489431.md">Storage</a>)</td></tr>
<tr>
<td><a href="1a0eb01f-9b40-a3f8-65cd-1f18f3bbd502.md">Separator</a></td>
<td>Gets access to the separator items appearance entries.</td></tr>
</table>

## Methods
<table>
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
<td>CreateInstance(IDictionary)</td>
<td>Re-creates an Object given a set of property values for the object.<br />(Inherited from TypeConverter)</td></tr>
<tr>
<td>CreateInstance(ITypeDescriptorContext, IDictionary)</td>
<td>Creates an instance of the type that this TypeConverter is associated with, using the specified context, given a set of property values for the object.<br />(Inherited from TypeConverter)</td></tr>
<tr>
<td>Equals</td>
<td>Determines whether the specified object is equal to the current object.<br />(Inherited from Object)</td></tr>
<tr>
<td>Finalize</td>
<td>Allows an object to try to free resources and perform other cleanup operations before it is reclaimed by garbage collection.<br />(Inherited from Object)</td></tr>
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
<td>GetHashCode</td>
<td>Serves as the default hash function.<br />(Inherited from Object)</td></tr>
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
<td>IsValid(Object)</td>
<td>Returns whether the given value object is valid for this type.<br />(Inherited from TypeConverter)</td></tr>
<tr>
<td>IsValid(ITypeDescriptorContext, Object)</td>
<td>Returns whether the given value object is valid for this type and for the specified context.<br />(Inherited from TypeConverter)</td></tr>
<tr>
<td>MemberwiseClone</td>
<td>Creates a shallow copy of the current Object.<br />(Inherited from Object)</td></tr>
<tr>
<td><a href="302d526d-0f27-d317-712d-92aab66d2d2e.md">OnNeedPaint</a></td>
<td>Raises the NeedPaint event.<br />(Inherited from <a href="8406cf55-79a3-e579-4094-be084e489431.md">Storage</a>)</td></tr>
<tr>
<td><a href="f8c3c184-f848-40c6-b2dc-e91f3d27a8c3.md">PerformNeedPaint()</a></td>
<td>Fires the NeedPaint event.<br />(Inherited from <a href="8406cf55-79a3-e579-4094-be084e489431.md">Storage</a>)</td></tr>
<tr>
<td><a href="63b9f5a4-a5f3-fc40-d0db-feeb82c11ac0.md">PerformNeedPaint(Boolean)</a></td>
<td>Fires the NeedPaint event.<br />(Inherited from <a href="8406cf55-79a3-e579-4094-be084e489431.md">Storage</a>)</td></tr>
<tr>
<td><a href="741960f9-5b65-f221-0791-86d8b66a5e80.md">PopulateFromBase</a></td>
<td>Populate values from the base palette.</td></tr>
<tr>
<td><a href="865d0c4d-e1d0-68b8-af42-b5a056acdd1d.md">SetRedirector</a></td>
<td>Update the redirector with new reference.</td></tr>
<tr>
<td>SortProperties</td>
<td>Sorts a collection of properties.<br />(Inherited from TypeConverter)</td></tr>
<tr>
<td><a href="31789cc7-0872-ef6d-6baf-4c4cf2484b50.md">ToString</a></td>
<td>Returns a string that represents the current defaulted state.<br />(Inherited from <a href="8406cf55-79a3-e579-4094-be084e489431.md">Storage</a>)</td></tr>
</table>

## See Also


#### Reference
<a href="79d2eac2-21f4-54ff-7552-b20c33c30600.md">Krypton.Toolkit Namespace</a>  
