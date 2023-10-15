# PaletteNavigator Class


Implement storage for normal and disable navigator appearance.



## Definition
**Namespace:** <a href="a21ac074-d119-3dc6-bd1c-d3a12c0128bc.md">Krypton.Navigator</a>  
**Assembly:** Krypton.Navigator (in Krypton.Navigator.dll) Version: 80.23.10.287+8d7660f9dc5efd033fabe008ebfb904beab6d444

**C#**
``` C#
public class PaletteNavigator : PaletteDoubleMetric
```
**VB**
``` VB
Public Class PaletteNavigator
	Inherits PaletteDoubleMetric
```

<table><tr><td><strong>Inheritance</strong></td><td>Object  →  TypeConverter  →  ExpandableObjectConverter  →  <a href="9ef2ca3a-e03e-8927-105a-2f9a6fbdf849.md">GlobalId</a>  →  <a href="8406cf55-79a3-e579-4094-be084e489431.md">Storage</a>  →  <a href="36787411-db48-4574-51dd-2d4d3139f187.md">PaletteDouble</a>  →  <a href="2b86d5df-ad2d-fa2c-ef8d-2ac7e7ed808c.md">PaletteDoubleMetric</a>  →  PaletteNavigator</td></tr>
</table>



## Constructors
<table>
<tr>
<td><a href="f1771b77-fb4d-de8c-7b69-fdd948a2dbbb.md">PaletteNavigator</a></td>
<td>Initialize a new instance of the PaletteNavigatorNormabled class.</td></tr>
</table>

## Properties
<table>
<tr>
<td><a href="356c87d5-0ea0-090d-9f63-8e608fc9a677.md">Back</a></td>
<td>Gets access to the background palette details.<br />(Overrides <a href="06d72b68-465f-5556-6467-b4c283a2d52e.md">PaletteDouble.Back</a>)</td></tr>
<tr>
<td><a href="b7fa944d-5581-8070-6820-49743186ab2b.md">Border</a></td>
<td>Gets access to the border palette details.<br />(Overrides <a href="590357cc-de70-8cf1-59d8-1ea06b2cb30e.md">PaletteDouble.Border</a>)</td></tr>
<tr>
<td><a href="9e733e52-7441-3a84-a68e-aeeb1d7a7eeb.md">BorderEdge</a></td>
<td>Gets access to the border edge appearance entries.</td></tr>
<tr>
<td><a href="414b1808-5384-d0d0-d767-02f49edda358.md">CheckButton</a></td>
<td>Gets access to the check button appearance entries.</td></tr>
<tr>
<td><a href="e580a9e2-5edc-01b5-e777-a038fecd4a1d.md">HeaderGroup</a></td>
<td>Gets access to the header group appearance entries.</td></tr>
<tr>
<td><a href="71a6846f-bfb6-fb58-b361-6b43ae0583a8.md">Id</a></td>
<td>Gets the unique identifier of the object.<br />(Inherited from <a href="9ef2ca3a-e03e-8927-105a-2f9a6fbdf849.md">GlobalId</a>)</td></tr>
<tr>
<td><a href="6f298219-417d-72ca-f66f-e4a057c5cf0d.md">IsDefault</a></td>
<td>Gets a value indicating if all values are default.<br />(Overrides <a href="1063cdd3-9307-d921-f497-8a95d88eeed6.md">PaletteDouble.IsDefault</a>)</td></tr>
<tr>
<td><a href="b9b9cece-9372-dd33-c150-7c908018bb9b.md">MiniButton</a></td>
<td>Gets access to the outlook mini button appearance entries.</td></tr>
<tr>
<td><a href="097a0f47-e60c-4bf7-802c-8391c6d8feff.md">NeedPaint</a></td>
<td>Gets and sets the need paint delegate for notifying paint requests.<br />(Inherited from <a href="8406cf55-79a3-e579-4094-be084e489431.md">Storage</a>)</td></tr>
<tr>
<td><a href="879ca7f2-32c5-8581-44f2-c7aee6491db2.md">NeedPaintDelegate</a></td>
<td>Gets access to the need paint delegate.<br />(Inherited from <a href="8406cf55-79a3-e579-4094-be084e489431.md">Storage</a>)</td></tr>
<tr>
<td><a href="c4ddd8c3-f958-3297-317b-ea13cb018519.md">OverflowButton</a></td>
<td>Gets access to the outlook overflow button appearance entries.</td></tr>
<tr>
<td><a href="ce382ee0-543a-33d9-7f78-1a7a7d6de60d.md">Page</a></td>
<td>Gets access to the page appearance entries.</td></tr>
<tr>
<td><a href="f3cc1070-7d80-03ea-bee9-47742b918030.md">PaletteBack</a></td>
<td>Gets the background palette.<br />(Overrides <a href="4dcf0a7e-e864-972a-5e45-98bfd70e601e.md">PaletteDouble.PaletteBack</a>)</td></tr>
<tr>
<td><a href="aec9f3fa-19a8-5b24-18ec-8a30b6b17f93.md">PaletteBorder</a></td>
<td>Gets the border palette.<br />(Overrides <a href="b6273d29-1cda-4e45-a9bc-7fbcff4473f4.md">PaletteDouble.PaletteBorder</a>)</td></tr>
<tr>
<td><a href="ba3630b9-403b-c599-6fb5-0950cf1f5ff0.md">Panel</a></td>
<td>Gets access to the panel palette details.</td></tr>
<tr>
<td><a href="9f20eef5-566a-a63e-be33-cdced783ed3a.md">RibbonTab</a></td>
<td>Gets access to the ribbon tab appearance entries.</td></tr>
<tr>
<td><a href="ba7075b9-7202-16eb-02bc-39b8c1dcf664.md">Separator</a></td>
<td>Get access to the overrides for defining separator appearance.</td></tr>
<tr>
<td><a href="1de8ef0f-40bf-54de-2fa9-928ff6ed1bbf.md">Tab</a></td>
<td>Gets access to the tab appearance entries.</td></tr>
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
<td><a href="7d8d35ca-3401-de8c-8b31-ada9fdca8170.md">GetMetricBool</a></td>
<td>Gets a boolean metric value.<br />(Inherited from <a href="2b86d5df-ad2d-fa2c-ef8d-2ac7e7ed808c.md">PaletteDoubleMetric</a>)</td></tr>
<tr>
<td><a href="fda9e222-29a2-7805-bbcb-0647a2679c81.md">GetMetricInt</a></td>
<td>Gets an integer metric value.<br />(Inherited from <a href="2b86d5df-ad2d-fa2c-ef8d-2ac7e7ed808c.md">PaletteDoubleMetric</a>)</td></tr>
<tr>
<td><a href="daf1d6ce-80cb-854d-e8ca-deca656f13eb.md">GetMetricPadding</a></td>
<td>Gets a padding metric value.<br />(Inherited from <a href="2b86d5df-ad2d-fa2c-ef8d-2ac7e7ed808c.md">PaletteDoubleMetric</a>)</td></tr>
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
<td><a href="8d702a6a-ca6a-455a-f88e-58af01f4c4d8.md">OnNeedPaint(Object, Boolean)</a></td>
<td>Handle a change event from palette source.<br />(Inherited from <a href="36787411-db48-4574-51dd-2d4d3139f187.md">PaletteDouble</a>)</td></tr>
<tr>
<td><a href="302d526d-0f27-d317-712d-92aab66d2d2e.md">OnNeedPaint(Object, NeedLayoutEventArgs)</a></td>
<td>Raises the NeedPaint event.<br />(Inherited from <a href="8406cf55-79a3-e579-4094-be084e489431.md">Storage</a>)</td></tr>
<tr>
<td><a href="f8c3c184-f848-40c6-b2dc-e91f3d27a8c3.md">PerformNeedPaint()</a></td>
<td>Fires the NeedPaint event.<br />(Inherited from <a href="8406cf55-79a3-e579-4094-be084e489431.md">Storage</a>)</td></tr>
<tr>
<td><a href="63b9f5a4-a5f3-fc40-d0db-feeb82c11ac0.md">PerformNeedPaint(Boolean)</a></td>
<td>Fires the NeedPaint event.<br />(Inherited from <a href="8406cf55-79a3-e579-4094-be084e489431.md">Storage</a>)</td></tr>
<tr>
<td><a href="ef8242fe-a521-f1bf-c864-b5a3a84482da.md">PopulateFromBase</a></td>
<td>Populate values from the base palette.<br />(Inherited from <a href="36787411-db48-4574-51dd-2d4d3139f187.md">PaletteDouble</a>)</td></tr>
<tr>
<td><a href="5931f4a8-e843-d800-364c-aafc9bf13df2.md">SetInherit(IPaletteDouble)</a></td>
<td>Sets the inheritance parent.<br />(Inherited from <a href="36787411-db48-4574-51dd-2d4d3139f187.md">PaletteDouble</a>)</td></tr>
<tr>
<td><a href="9aac2fa8-254d-ece0-70f4-1c1ced15b7c8.md">SetInherit(PaletteDoubleMetricRedirect)</a></td>
<td>Sets the inheritance parent.<br />(Inherited from <a href="2b86d5df-ad2d-fa2c-ef8d-2ac7e7ed808c.md">PaletteDoubleMetric</a>)</td></tr>
<tr>
<td><a href="9a7d8dec-a98a-b1ed-8518-8bbb989c412b.md">SetInherit(PaletteNavigator)</a></td>
<td>Sets the inheritance parent.</td></tr>
<tr>
<td>SortProperties</td>
<td>Sorts a collection of properties.<br />(Inherited from TypeConverter)</td></tr>
<tr>
<td><a href="31789cc7-0872-ef6d-6baf-4c4cf2484b50.md">ToString</a></td>
<td>Returns a string that represents the current defaulted state.<br />(Inherited from <a href="8406cf55-79a3-e579-4094-be084e489431.md">Storage</a>)</td></tr>
</table>

## See Also


#### Reference
<a href="a21ac074-d119-3dc6-bd1c-d3a12c0128bc.md">Krypton.Navigator Namespace</a>  
