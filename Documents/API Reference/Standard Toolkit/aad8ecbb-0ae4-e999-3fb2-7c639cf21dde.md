# NavigatorOutlookFull Methods




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
<td><a href="9d13d4ca-3596-a40c-19b0-b4b7055855e0.md">ResetOverflowMapExtraText</a></td>
<td>Resets the OverflowMapExtraText property to its default value.</td></tr>
<tr>
<td><a href="847d5bc9-1413-58f1-5ebd-de0d91953dad.md">ResetOverflowMapImage</a></td>
<td>Resets the OverflowMapImage property to its default value.</td></tr>
<tr>
<td><a href="03508eb5-eaea-6c05-95a1-1191e3d8e9e1.md">ResetOverflowMapText</a></td>
<td>Resets the OverflowMapText property to its default value.</td></tr>
<tr>
<td><a href="ec88e44b-648e-94b2-91fc-2dab8f850126.md">ResetStackMapExtraText</a></td>
<td>Resets the StackMapExtraText property to its default value.</td></tr>
<tr>
<td><a href="8f60c346-f7a3-3d4b-dea6-959213e0e62a.md">ResetStackMapImage</a></td>
<td>Resets the StackMapImage property to its default value.</td></tr>
<tr>
<td><a href="2ad142fe-97c9-7a96-8bca-9d3711336592.md">ResetStackMapText</a></td>
<td>Resets the StackMapText property to its default value.</td></tr>
<tr>
<td>SortProperties</td>
<td>Sorts a collection of properties.<br />(Inherited from TypeConverter)</td></tr>
<tr>
<td><a href="31789cc7-0872-ef6d-6baf-4c4cf2484b50.md">ToString</a></td>
<td>Returns a string that represents the current defaulted state.<br />(Inherited from <a href="8406cf55-79a3-e579-4094-be084e489431.md">Storage</a>)</td></tr>
</table>

## See Also


#### Reference
<a href="99496126-1401-f11e-14dd-8c71c4ea719b.md">NavigatorOutlookFull Class</a>  
<a href="a21ac074-d119-3dc6-bd1c-d3a12c0128bc.md">Krypton.Navigator Namespace</a>  
