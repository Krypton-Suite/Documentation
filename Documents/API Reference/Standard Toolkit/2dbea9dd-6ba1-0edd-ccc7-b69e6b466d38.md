# AccurateText Class


Provide accurate text measuring and drawing capability.



## Definition
**Namespace:** <a href="79d2eac2-21f4-54ff-7552-b20c33c30600.md">Krypton.Toolkit</a>  
**Assembly:** Krypton.Toolkit (in Krypton.Toolkit.dll) Version: 80.23.10.287+8d7660f9dc5efd033fabe008ebfb904beab6d444

**C#**
``` C#
public class AccurateText : GlobalId
```
**VB**
``` VB
Public Class AccurateText
	Inherits GlobalId
```

<table><tr><td><strong>Inheritance</strong></td><td>Object  →  TypeConverter  →  ExpandableObjectConverter  →  <a href="9ef2ca3a-e03e-8927-105a-2f9a6fbdf849.md">GlobalId</a>  →  AccurateText</td></tr>
</table>



## Constructors
<table>
<tr>
<td><a href="143ae2d4-a652-fe25-740e-8cdb4774c15c.md">AccurateText</a></td>
<td>Initializes a new instance of the AccurateText class</td></tr>
</table>

## Properties
<table>
<tr>
<td><a href="71a6846f-bfb6-fb58-b361-6b43ae0583a8.md">Id</a></td>
<td>Gets the unique identifier of the object.<br />(Inherited from <a href="9ef2ca3a-e03e-8927-105a-2f9a6fbdf849.md">GlobalId</a>)</td></tr>
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
<td><a href="122dee5b-085d-fcd7-8866-a86a182b1b7b.md">DrawCompositionGlowingText</a></td>
<td>Draw text with a glowing background, for use on a composition element.</td></tr>
<tr>
<td><a href="aa2e65f3-8b3d-5445-11ef-a3a131b32624.md">DrawCompositionText</a></td>
<td>Draw text without a glowing background, for use on a composition element.</td></tr>
<tr>
<td><a href="e57e3811-49d1-324e-b6b6-59deea7a3660.md">DrawString</a></td>
<td>Pixel accurate drawing of the requested text memento information.</td></tr>
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
<td><a href="e218ee03-a13c-d292-13fb-c67e7660dc01.md">MeasureString</a></td>
<td>Pixel accurate measure of the specified string when drawn with the specified Font object.</td></tr>
<tr>
<td>MemberwiseClone</td>
<td>Creates a shallow copy of the current Object.<br />(Inherited from Object)</td></tr>
<tr>
<td>SortProperties</td>
<td>Sorts a collection of properties.<br />(Inherited from TypeConverter)</td></tr>
<tr>
<td>ToString</td>
<td>Returns a string that represents the current object.<br />(Inherited from Object)</td></tr>
</table>

## See Also


#### Reference
<a href="79d2eac2-21f4-54ff-7552-b20c33c30600.md">Krypton.Toolkit Namespace</a>  
