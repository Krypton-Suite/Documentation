# KryptonPaletteImagesRadioButton Class


Storage for palette radio button images.



## Definition
**Namespace:** <a href="79d2eac2-21f4-54ff-7552-b20c33c30600.md">Krypton.Toolkit</a>  
**Assembly:** Krypton.Toolkit (in Krypton.Toolkit.dll) Version: 80.23.10.287+8d7660f9dc5efd033fabe008ebfb904beab6d444

**C#**
``` C#
public class KryptonPaletteImagesRadioButton : Storage
```
**VB**
``` VB
Public Class KryptonPaletteImagesRadioButton
	Inherits Storage
```

<table><tr><td><strong>Inheritance</strong></td><td>Object  →  TypeConverter  →  ExpandableObjectConverter  →  <a href="9ef2ca3a-e03e-8927-105a-2f9a6fbdf849.md">GlobalId</a>  →  <a href="8406cf55-79a3-e579-4094-be084e489431.md">Storage</a>  →  KryptonPaletteImagesRadioButton</td></tr>
</table>



## Constructors
<table>
<tr>
<td><a href="7a2cf983-eec8-8893-27ab-9ce0933cabfd.md">KryptonPaletteImagesRadioButton</a></td>
<td>Initialize a new instance of the KryptonPaletteImagesRadioButton class.</td></tr>
</table>

## Properties
<table>
<tr>
<td><a href="0399b526-7990-68ff-1aee-6fb03fdc80f8.md">CheckedDisabled</a></td>
<td>Gets and sets the image for use when the check box is checked but disabled.</td></tr>
<tr>
<td><a href="23345901-6321-727a-50e5-aafb9019e45e.md">CheckedNormal</a></td>
<td>Gets and sets the image for use when the check box is checked.</td></tr>
<tr>
<td><a href="188be466-526d-7948-4921-bfb9b254e016.md">CheckedPressed</a></td>
<td>Gets and sets the image for use when the check box is checked and pressed.</td></tr>
<tr>
<td><a href="1c1b94f8-8362-e030-e611-ac368a97c87b.md">CheckedTracking</a></td>
<td>Gets and sets the image for use when the check box is checked and hot tracking.</td></tr>
<tr>
<td><a href="94528784-89e3-9955-8435-92db624c7887.md">Common</a></td>
<td>Gets and sets the common image that other check box images inherit from.</td></tr>
<tr>
<td><a href="71a6846f-bfb6-fb58-b361-6b43ae0583a8.md">Id</a></td>
<td>Gets the unique identifier of the object.<br />(Inherited from <a href="9ef2ca3a-e03e-8927-105a-2f9a6fbdf849.md">GlobalId</a>)</td></tr>
<tr>
<td><a href="f2dbb9d4-fffb-8d81-15ec-ec19aba51d1f.md">IsDefault</a></td>
<td>Gets a value indicating if all values are default.<br />(Overrides <a href="bbc0e831-9474-3bce-65dc-0625d793d8c1.md">Storage.IsDefault</a>)</td></tr>
<tr>
<td><a href="097a0f47-e60c-4bf7-802c-8391c6d8feff.md">NeedPaint</a></td>
<td>Gets and sets the need paint delegate for notifying paint requests.<br />(Inherited from <a href="8406cf55-79a3-e579-4094-be084e489431.md">Storage</a>)</td></tr>
<tr>
<td><a href="879ca7f2-32c5-8581-44f2-c7aee6491db2.md">NeedPaintDelegate</a></td>
<td>Gets access to the need paint delegate.<br />(Inherited from <a href="8406cf55-79a3-e579-4094-be084e489431.md">Storage</a>)</td></tr>
<tr>
<td><a href="74920ae7-59b2-8aff-5101-2c35e49a465b.md">UncheckedDisabled</a></td>
<td>Gets and sets the image for use when the check box is not checked and disabled.</td></tr>
<tr>
<td><a href="cf42eaeb-de99-4bf0-5a23-dae6449e4372.md">UncheckedNormal</a></td>
<td>Gets and sets the image for use when the check box is unchecked.</td></tr>
<tr>
<td><a href="c605d02b-799e-f8b1-ebee-4cbcf498d493.md">UncheckedPressed</a></td>
<td>Gets and sets the image for use when the check box is unchecked and pressed.</td></tr>
<tr>
<td><a href="cdf5a814-3595-6d4b-9ba3-a93c282c0aaf.md">UncheckedTracking</a></td>
<td>Gets and sets the image for use when the check box is unchecked and hot tracking.</td></tr>
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
<td><a href="1fadb838-f2b1-a480-590b-f7e053e97898.md">PopulateFromBase</a></td>
<td>Populate values from the base palette.</td></tr>
<tr>
<td><a href="de40996e-b4cb-842a-7dd8-32fab48ff56b.md">ResetCheckedDisabled</a></td>
<td>Resets the CheckedDisabled property to its default value.</td></tr>
<tr>
<td><a href="6aa2a2c0-ddb2-ffbb-0f72-7be49c3ef61c.md">ResetCheckedNormal</a></td>
<td>Resets the CheckedNormal property to its default value.</td></tr>
<tr>
<td><a href="af03e1f3-5f28-9f17-896d-e20e192dd836.md">ResetCheckedPressed</a></td>
<td>Resets the CheckedPressed property to its default value.</td></tr>
<tr>
<td><a href="943bf508-c3d2-96c5-ef93-8d34fe621dbf.md">ResetCheckedTracking</a></td>
<td>Resets the CheckedTracking property to its default value.</td></tr>
<tr>
<td><a href="769957cb-ecf0-fcad-ee1e-1fee0ae3842e.md">ResetCommon</a></td>
<td>Resets the Common property to its default value.</td></tr>
<tr>
<td><a href="5c1deb75-f80b-eb87-fc25-26be2c1cca95.md">ResetUncheckedDisabled</a></td>
<td>Resets the UncheckedDisabled property to its default value.</td></tr>
<tr>
<td><a href="daa831a9-7c7f-b221-d89a-587ea45fc8e4.md">ResetUncheckedNormal</a></td>
<td>Resets the UncheckedNormal property to its default value.</td></tr>
<tr>
<td><a href="4b335a4f-36c8-f5b9-a56c-00e195f0dfbc.md">ResetUncheckedPressed</a></td>
<td>Resets the UncheckedPressed property to its default value.</td></tr>
<tr>
<td><a href="ffacae76-d80a-0e8c-8efb-4e79648855a5.md">ResetUncheckedTracking</a></td>
<td>Resets the UncheckedTracking property to its default value.</td></tr>
<tr>
<td><a href="f22eb463-d546-7268-e8d8-830f1d762e0b.md">SetRedirector</a></td>
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
