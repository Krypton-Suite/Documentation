# ButtonValues Class


Storage for button content value information.



## Definition
**Namespace:** <a href="79d2eac2-21f4-54ff-7552-b20c33c30600.md">Krypton.Toolkit</a>  
**Assembly:** Krypton.Toolkit (in Krypton.Toolkit.dll) Version: 80.23.10.287+8d7660f9dc5efd033fabe008ebfb904beab6d444

**C#**
``` C#
public class ButtonValues : Storage, 
	IContentValues
```
**VB**
``` VB
Public Class ButtonValues
	Inherits Storage
	Implements IContentValues
```

<table><tr><td><strong>Inheritance</strong></td><td>Object  →  TypeConverter  →  ExpandableObjectConverter  →  <a href="9ef2ca3a-e03e-8927-105a-2f9a6fbdf849.md">GlobalId</a>  →  <a href="8406cf55-79a3-e579-4094-be084e489431.md">Storage</a>  →  ButtonValues</td></tr>
<tr><td><strong>Derived</strong></td><td><a href="fa8235db-a06c-959f-721b-d0ab8d7e276d.md">Krypton.Toolkit.CheckButtonValues</a><br /><a href="a3e45995-3c19-e319-20a3-26bcac780ea9.md">Krypton.Toolkit.UACShieldValues</a></td></tr>
<tr><td><strong>Implements</strong></td><td><a href="a3b0103b-df64-4b03-a61f-11688b6e75bf.md">IContentValues</a></td></tr>
</table>



## Constructors
<table>
<tr>
<td><a href="8abfe6e6-de2a-3fe7-07a6-6e51d9f15356.md">ButtonValues</a></td>
<td>Initialize a new instance of the ButtonValues class.</td></tr>
</table>

## Properties
<table>
<tr>
<td><a href="a8b34e9c-06a8-c1a6-0231-41391f01dab0.md">ExtraText</a></td>
<td>Gets and sets the button extra text.</td></tr>
<tr>
<td><a href="71a6846f-bfb6-fb58-b361-6b43ae0583a8.md">Id</a></td>
<td>Gets the unique identifier of the object.<br />(Inherited from <a href="9ef2ca3a-e03e-8927-105a-2f9a6fbdf849.md">GlobalId</a>)</td></tr>
<tr>
<td><a href="a97b3776-227f-0e02-6347-5d31c1f09fd6.md">Image</a></td>
<td>Gets and sets the button image.</td></tr>
<tr>
<td><a href="09728a58-d83c-060d-6185-d99012d894d7.md">ImageStates</a></td>
<td>Gets access to the state specific images for the button.</td></tr>
<tr>
<td><a href="e98c9955-4f71-f0cf-7c69-1e699ba93cc4.md">ImageTransparentColor</a></td>
<td>Gets and sets the label image transparent color.</td></tr>
<tr>
<td><a href="c470f10f-90b4-18b8-44d3-ef7d66c56d35.md">IsDefault</a></td>
<td>Gets a value indicating if all values are default.<br />(Overrides <a href="bbc0e831-9474-3bce-65dc-0625d793d8c1.md">Storage.IsDefault</a>)</td></tr>
<tr>
<td><a href="097a0f47-e60c-4bf7-802c-8391c6d8feff.md">NeedPaint</a></td>
<td>Gets and sets the need paint delegate for notifying paint requests.<br />(Inherited from <a href="8406cf55-79a3-e579-4094-be084e489431.md">Storage</a>)</td></tr>
<tr>
<td><a href="879ca7f2-32c5-8581-44f2-c7aee6491db2.md">NeedPaintDelegate</a></td>
<td>Gets access to the need paint delegate.<br />(Inherited from <a href="8406cf55-79a3-e579-4094-be084e489431.md">Storage</a>)</td></tr>
<tr>
<td><a href="cd8b16f0-6ce9-d8b9-0d23-a063bd0b0579.md">Text</a></td>
<td>Gets and sets the button text.</td></tr>
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
<td><a href="adaa4576-3119-1794-33a9-3cfd390637e8.md">CreateImageStates</a></td>
<td>Create the storage for the image states.</td></tr>
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
<td><a href="96f2b87d-1c76-8b8b-76c9-3a2bbe94bdbd.md">GetImage</a></td>
<td>Gets the content image.</td></tr>
<tr>
<td><a href="c5345cf1-b787-285a-d5e2-8a583392ac0c.md">GetImageTransparentColor</a></td>
<td>Gets the content image transparent color.</td></tr>
<tr>
<td><a href="125e53fc-ab58-0b05-e3f3-3ab420781907.md">GetLongText</a></td>
<td>Gets the content long text.</td></tr>
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
<td><a href="1a1f448e-8195-f761-f98f-26fcb769b3b7.md">GetShortText</a></td>
<td>Gets the content short text.</td></tr>
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
<td><a href="3b1833e6-8610-15f1-4d4e-5c793b8e4594.md">ResetExtraText</a></td>
<td>Resets the Description property to its default value.</td></tr>
<tr>
<td><a href="be87a2fc-4a78-18b2-fd3b-7eba4daabf64.md">ResetImage</a></td>
<td>Resets the Image property to its default value.</td></tr>
<tr>
<td><a href="0a7d3ee9-1ea3-b8db-bf7c-b4b3600493b6.md">ResetImageTransparentColor</a></td>
<td>Resets the ImageTransparentColor property to its default value.</td></tr>
<tr>
<td><a href="27fb93a0-5826-48b9-942b-df7af16903c6.md">ResetText</a></td>
<td>Resets the Text property to its default value.</td></tr>
<tr>
<td>SortProperties</td>
<td>Sorts a collection of properties.<br />(Inherited from TypeConverter)</td></tr>
<tr>
<td><a href="31789cc7-0872-ef6d-6baf-4c4cf2484b50.md">ToString</a></td>
<td>Returns a string that represents the current defaulted state.<br />(Inherited from <a href="8406cf55-79a3-e579-4094-be084e489431.md">Storage</a>)</td></tr>
</table>

## Events
<table>
<tr>
<td><a href="361c5438-b7e6-fa29-929b-7e9df85b2745.md">TextChanged</a></td>
<td>Occurs when the value of the Text property changes.</td></tr>
</table>

## See Also


#### Reference
<a href="79d2eac2-21f4-54ff-7552-b20c33c30600.md">Krypton.Toolkit Namespace</a>  
