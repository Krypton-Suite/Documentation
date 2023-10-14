# ViewDrawPanel Class


View element that can draw a panel (background but no border)



## Definition
**Namespace:** <a href="79d2eac2-21f4-54ff-7552-b20c33c30600.md">Krypton.Toolkit</a>  
**Assembly:** Krypton.Toolkit (in Krypton.Toolkit.dll) Version: 80.23.10.287+8d7660f9dc5efd033fabe008ebfb904beab6d444

**C#**
``` C#
public class ViewDrawPanel : ViewComposite
```
**VB**
``` VB
Public Class ViewDrawPanel
	Inherits ViewComposite
```

<table><tr><td><strong>Inheritance</strong></td><td>Object  →  TypeConverter  →  ExpandableObjectConverter  →  <a href="9ef2ca3a-e03e-8927-105a-2f9a6fbdf849.md">GlobalId</a>  →  <a href="309ac2d8-bfc5-c1a7-ab6a-4f4cf86a1ba6.md">ViewBase</a>  →  <a href="467f805c-296b-06ec-42f1-e965af0d0f04.md">ViewComposite</a>  →  ViewDrawPanel</td></tr>
<tr><td><strong>Derived</strong></td><td><a href="563f9cd9-f7c9-a2fb-0782-160a69b7a343.md">Krypton.Toolkit.ViewDrawBorderEdge</a><br /><a href="c4fe8079-0665-3daa-3153-8c8189a39b91.md">Krypton.Toolkit.ViewDrawTrackBar</a></td></tr>
</table>



## Constructors
<table>
<tr>
<td><a href="0dd5f378-b401-9389-21a6-3ed065996602.md">ViewDrawPanel()</a></td>
<td>Initialize a new instance of the ViewDrawPanel class.</td></tr>
<tr>
<td><a href="0bfab619-6a5b-0667-b214-f55d153a33b4.md">ViewDrawPanel(IPaletteBack)</a></td>
<td>Initialize a new instance of the ViewDrawPanel class.</td></tr>
</table>

## Properties
<table>
<tr>
<td><a href="8ca1086e-f2a1-e3aa-0550-e17de8d4d705.md">ClientHeight</a></td>
<td>Gets and sets the height of the view.<br />(Inherited from <a href="309ac2d8-bfc5-c1a7-ab6a-4f4cf86a1ba6.md">ViewBase</a>)</td></tr>
<tr>
<td><a href="adf2b0f9-71eb-d32c-2ec0-ac09568593fa.md">ClientLocation</a></td>
<td>Gets and sets the location of the view inside the parent view.<br />(Inherited from <a href="309ac2d8-bfc5-c1a7-ab6a-4f4cf86a1ba6.md">ViewBase</a>)</td></tr>
<tr>
<td><a href="26daf885-2412-02b5-dc52-e6e5f8121280.md">ClientRectangle</a></td>
<td>Gets and sets the rectangle bounding the client area.<br />(Inherited from <a href="309ac2d8-bfc5-c1a7-ab6a-4f4cf86a1ba6.md">ViewBase</a>)</td></tr>
<tr>
<td><a href="aab48de6-57c1-8040-9e53-80d7379b3269.md">ClientRectangleF</a></td>
<td><br />(Inherited from <a href="309ac2d8-bfc5-c1a7-ab6a-4f4cf86a1ba6.md">ViewBase</a>)</td></tr>
<tr>
<td><a href="c7ce4247-0421-c87f-bef9-93ca9c8d0710.md">ClientSize</a></td>
<td>Gets and sets the size of the view.<br />(Inherited from <a href="309ac2d8-bfc5-c1a7-ab6a-4f4cf86a1ba6.md">ViewBase</a>)</td></tr>
<tr>
<td><a href="8e43df91-01e4-3d85-b2c7-6f37025e7632.md">ClientWidth</a></td>
<td>Gets and sets the width of the view.<br />(Inherited from <a href="309ac2d8-bfc5-c1a7-ab6a-4f4cf86a1ba6.md">ViewBase</a>)</td></tr>
<tr>
<td><a href="a0853610-b2de-7dec-2285-f2d884fc0231.md">Component</a></td>
<td>Gets the component associated with the element.<br />(Inherited from <a href="309ac2d8-bfc5-c1a7-ab6a-4f4cf86a1ba6.md">ViewBase</a>)</td></tr>
<tr>
<td><a href="b1b7ced2-1168-f3c3-1a93-e397fded25bc.md">Count</a></td>
<td>Gets the number of views in collection.<br />(Inherited from <a href="467f805c-296b-06ec-42f1-e965af0d0f04.md">ViewComposite</a>)</td></tr>
<tr>
<td><a href="45b74146-9308-269a-0625-9558884a95b2.md">DependantEnabledState</a></td>
<td>Get and set the view the enabled state of this view element is dependant on.<br />(Inherited from <a href="309ac2d8-bfc5-c1a7-ab6a-4f4cf86a1ba6.md">ViewBase</a>)</td></tr>
<tr>
<td><a href="1631dbf1-7432-b0c3-508a-cc76fd85b428.md">ElementState</a></td>
<td>Gets and sets the visual state of the element.<br />(Inherited from <a href="309ac2d8-bfc5-c1a7-ab6a-4f4cf86a1ba6.md">ViewBase</a>)</td></tr>
<tr>
<td><a href="ab081600-b6ff-5a6b-58b1-096a470ecd35.md">Enabled</a></td>
<td>Gets and sets the enabled state of the element.<br />(Inherited from <a href="309ac2d8-bfc5-c1a7-ab6a-4f4cf86a1ba6.md">ViewBase</a>)</td></tr>
<tr>
<td><a href="026ae658-3cdc-1c85-8625-fc598f0183a8.md">FactorDpiX</a></td>
<td>Gets the DpiX of the view.<br />(Inherited from <a href="309ac2d8-bfc5-c1a7-ab6a-4f4cf86a1ba6.md">ViewBase</a>)</td></tr>
<tr>
<td><a href="0c4492bd-aee6-2147-f951-fcd5893011ed.md">FactorDpiY</a></td>
<td>Gets the DpiY of the view.<br />(Inherited from <a href="309ac2d8-bfc5-c1a7-ab6a-4f4cf86a1ba6.md">ViewBase</a>)</td></tr>
<tr>
<td><a href="1afc0445-4412-fd78-bc12-cd70b02efd18.md">FixedState</a></td>
<td>Set a fixed state to override usual behavior and appearance<br />(Inherited from <a href="467f805c-296b-06ec-42f1-e965af0d0f04.md">ViewComposite</a>)</td></tr>
<tr>
<td><a href="71a6846f-bfb6-fb58-b361-6b43ae0583a8.md">Id</a></td>
<td>Gets the unique identifier of the object.<br />(Inherited from <a href="9ef2ca3a-e03e-8927-105a-2f9a6fbdf849.md">GlobalId</a>)</td></tr>
<tr>
<td><a href="1f17e987-dcc9-b808-1030-a189570afe59.md">IgnoreRender</a></td>
<td>Gets and sets the rendering status.</td></tr>
<tr>
<td><a href="b8132097-e81f-af8f-9edb-3cb79ba26d45.md">IsDisposed</a></td>
<td>Gets a value indicating if the view has been disposed.<br />(Inherited from <a href="309ac2d8-bfc5-c1a7-ab6a-4f4cf86a1ba6.md">ViewBase</a>)</td></tr>
<tr>
<td><a href="2051812a-d6aa-0b59-07f6-d0aaf5425a45.md">IsEnableDependant</a></td>
<td>Gets a value indicating if view enabled state is dependent on another view.<br />(Inherited from <a href="309ac2d8-bfc5-c1a7-ab6a-4f4cf86a1ba6.md">ViewBase</a>)</td></tr>
<tr>
<td><a href="ae00d504-ee78-dc0c-547f-47ccf010c8f3.md">IsFixed</a></td>
<td>Gets a value indicating if view is using a fixed state.<br />(Inherited from <a href="309ac2d8-bfc5-c1a7-ab6a-4f4cf86a1ba6.md">ViewBase</a>)</td></tr>
<tr>
<td><a href="1359c544-d62a-40dc-68ae-2cf918c7cb0c.md">IsReadOnly</a></td>
<td>Gets a value indicating whether the collection is read-only.<br />(Inherited from <a href="309ac2d8-bfc5-c1a7-ab6a-4f4cf86a1ba6.md">ViewBase</a>)</td></tr>
<tr>
<td><a href="66c58f19-a9b5-0f2f-7dba-f86ab9d13d7f.md">Item</a></td>
<td>Gets or sets the view at the specified index.<br />(Inherited from <a href="467f805c-296b-06ec-42f1-e965af0d0f04.md">ViewComposite</a>)</td></tr>
<tr>
<td><a href="8c0c18fc-2c53-4c1c-c120-964c3bc82e99.md">KeyController</a></td>
<td>Gets and sets the associated key controller.<br />(Inherited from <a href="309ac2d8-bfc5-c1a7-ab6a-4f4cf86a1ba6.md">ViewBase</a>)</td></tr>
<tr>
<td><a href="d5761a42-75a6-b244-b305-631dbf54d295.md">MouseController</a></td>
<td>Gets and sets the associated mouse controller.<br />(Inherited from <a href="309ac2d8-bfc5-c1a7-ab6a-4f4cf86a1ba6.md">ViewBase</a>)</td></tr>
<tr>
<td><a href="c732fcd5-3e0d-98cb-17df-e574d4733f53.md">OwningControl</a></td>
<td>Gets and sets a reference to the control instance that contains this view element.<br />(Inherited from <a href="309ac2d8-bfc5-c1a7-ab6a-4f4cf86a1ba6.md">ViewBase</a>)</td></tr>
<tr>
<td><a href="b34c2e84-eb23-0078-5656-e854d6f41638.md">Parent</a></td>
<td>Gets the parent view.<br />(Inherited from <a href="309ac2d8-bfc5-c1a7-ab6a-4f4cf86a1ba6.md">ViewBase</a>)</td></tr>
<tr>
<td><a href="fe8c3e05-4391-689a-ac07-e976cddc0b2b.md">ReverseRenderOrder</a></td>
<td>Gets and sets the use of reverse order when rendering.<br />(Inherited from <a href="467f805c-296b-06ec-42f1-e965af0d0f04.md">ViewComposite</a>)</td></tr>
<tr>
<td><a href="354d206d-5772-7294-dc86-25ae526ef09d.md">SourceController</a></td>
<td>Gets and sets the associated source controller.<br />(Inherited from <a href="309ac2d8-bfc5-c1a7-ab6a-4f4cf86a1ba6.md">ViewBase</a>)</td></tr>
<tr>
<td><a href="97b91260-605d-f086-e86c-7ad32f06d42b.md">State</a></td>
<td>Gets the visual state taking into account the owning controls state.<br />(Inherited from <a href="309ac2d8-bfc5-c1a7-ab6a-4f4cf86a1ba6.md">ViewBase</a>)</td></tr>
<tr>
<td><a href="c6f3a2c1-5079-abb9-07ab-be74628e34be.md">Visible</a></td>
<td>Gets and sets the enabled state of the element.<br />(Inherited from <a href="309ac2d8-bfc5-c1a7-ab6a-4f4cf86a1ba6.md">ViewBase</a>)</td></tr>
<tr>
<td><a href="5b122f02-75c6-d00c-380e-2fd05023d5b3.md">VisualOrientation</a></td>
<td>Gets and sets the orientation of the panel.</td></tr>
</table>

## Methods
<table>
<tr>
<td><a href="55be5aff-de6d-f57c-4e49-91e60199b657.md">Add</a></td>
<td>Append a view to the collection.<br />(Inherited from <a href="467f805c-296b-06ec-42f1-e965af0d0f04.md">ViewComposite</a>)</td></tr>
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
<td><a href="c6c0a8f0-d220-45a2-54f7-9aecf110f3af.md">Clear</a></td>
<td>Remove all views from the collection.<br />(Inherited from <a href="467f805c-296b-06ec-42f1-e965af0d0f04.md">ViewComposite</a>)</td></tr>
<tr>
<td><a href="a15ecf08-8e78-e740-f773-5ba5b1b2e18b.md">ClearFixedState</a></td>
<td>Clear down the use of the fixed state<br />(Inherited from <a href="467f805c-296b-06ec-42f1-e965af0d0f04.md">ViewComposite</a>)</td></tr>
<tr>
<td><a href="5f00ebaf-3467-b886-4780-ad04107282a7.md">Contains</a></td>
<td>Determines whether the collection contains the view.<br />(Inherited from <a href="467f805c-296b-06ec-42f1-e965af0d0f04.md">ViewComposite</a>)</td></tr>
<tr>
<td><a href="9b6cb380-3abe-8e4e-d7a8-60e8c9b19ce2.md">ContainsRecurse</a></td>
<td>Determines whether any part of the view hierarchy is the specified view.<br />(Inherited from <a href="467f805c-296b-06ec-42f1-e965af0d0f04.md">ViewComposite</a>)</td></tr>
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
<td><a href="b02ce1e5-0a59-24c5-41d6-f5ccab96d7b5.md">CopyTo</a></td>
<td>Copies views to specified array starting at particular index.<br />(Inherited from <a href="467f805c-296b-06ec-42f1-e965af0d0f04.md">ViewComposite</a>)</td></tr>
<tr>
<td>CreateInstance(IDictionary)</td>
<td>Re-creates an Object given a set of property values for the object.<br />(Inherited from TypeConverter)</td></tr>
<tr>
<td>CreateInstance(ITypeDescriptorContext, IDictionary)</td>
<td>Creates an instance of the type that this TypeConverter is associated with, using the specified context, given a set of property values for the object.<br />(Inherited from TypeConverter)</td></tr>
<tr>
<td><a href="56e77af8-2279-414f-d419-9e0428f318da.md">Dispose()</a></td>
<td>Release managed and unmanaged resources.<br />(Inherited from <a href="309ac2d8-bfc5-c1a7-ab6a-4f4cf86a1ba6.md">ViewBase</a>)</td></tr>
<tr>
<td><a href="6982653b-9ad7-e2a3-e1fe-5a4d8e7c83ac.md">Dispose(Boolean)</a></td>
<td>Clean up any resources being used.<br />(Overrides <a href="56751793-8e06-28d3-111f-7cce0a28e55d.md">ViewComposite.Dispose(Boolean)</a>)</td></tr>
<tr>
<td><a href="95398135-79d1-2dcf-a20f-c6ff362ade91.md">DoubleClick</a></td>
<td>Left mouse button has been double clicked.<br />(Inherited from <a href="309ac2d8-bfc5-c1a7-ab6a-4f4cf86a1ba6.md">ViewBase</a>)</td></tr>
<tr>
<td>Equals</td>
<td>Determines whether the specified object is equal to the current object.<br />(Inherited from Object)</td></tr>
<tr>
<td><a href="4e72d959-20e3-17a4-2d19-647d886eebe2.md">EvalTransparentPaint</a></td>
<td>Evaluate the need for drawing transparent areas.<br />(Overrides <a href="d7dd0d33-a4de-71af-37ad-7ae81c608b42.md">ViewComposite.EvalTransparentPaint(ViewContext)</a>)</td></tr>
<tr>
<td><a href="906b1d4f-3979-9407-ae58-de235976e067.md">Finalize</a></td>
<td>Release resources.<br />(Inherited from <a href="309ac2d8-bfc5-c1a7-ab6a-4f4cf86a1ba6.md">ViewBase</a>)</td></tr>
<tr>
<td><a href="fa2eff88-157f-82f0-361c-8adb76577c30.md">FindMouseController</a></td>
<td>Mouse has entered the view.<br />(Inherited from <a href="309ac2d8-bfc5-c1a7-ab6a-4f4cf86a1ba6.md">ViewBase</a>)</td></tr>
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
<td><a href="b19d1692-c30c-5c91-dcfb-d8d453628da0.md">GetEnumerator</a></td>
<td>Shallow enumerate forward over children of the element.<br />(Inherited from <a href="467f805c-296b-06ec-42f1-e965af0d0f04.md">ViewComposite</a>)</td></tr>
<tr>
<td>GetHashCode</td>
<td>Serves as the default hash function.<br />(Inherited from Object)</td></tr>
<tr>
<td><a href="89e12ae6-8c39-39e5-7203-1d923d947e43.md">GetPalette</a></td>
<td>Gets the palette used for drawing the panel.</td></tr>
<tr>
<td><a href="9e6fdfdd-1b7a-a10e-cf5c-477460b4c117.md">GetPreferredSize</a></td>
<td>Discover the preferred size of the element.<br />(Inherited from <a href="467f805c-296b-06ec-42f1-e965af0d0f04.md">ViewComposite</a>)</td></tr>
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
<td>Source control has got the focus.<br />(Inherited from <a href="309ac2d8-bfc5-c1a7-ab6a-4f4cf86a1ba6.md">ViewBase</a>)</td></tr>
<tr>
<td><a href="e7ac2645-5527-80b2-4421-216f076ecdea.md">IndexOf</a></td>
<td>Determines the index of the specified view in the collection.<br />(Inherited from <a href="467f805c-296b-06ec-42f1-e965af0d0f04.md">ViewComposite</a>)</td></tr>
<tr>
<td><a href="2211559c-df64-5ec1-f926-b49e3488829f.md">Insert</a></td>
<td>Inserts a view to the collection at the specified index.<br />(Inherited from <a href="467f805c-296b-06ec-42f1-e965af0d0f04.md">ViewComposite</a>)</td></tr>
<tr>
<td>IsValid(Object)</td>
<td>Returns whether the given value object is valid for this type.<br />(Inherited from TypeConverter)</td></tr>
<tr>
<td>IsValid(ITypeDescriptorContext, Object)</td>
<td>Returns whether the given value object is valid for this type and for the specified context.<br />(Inherited from TypeConverter)</td></tr>
<tr>
<td><a href="375695e4-351a-d41e-2a9c-849557307230.md">KeyDown</a></td>
<td>Key has been pressed down.<br />(Inherited from <a href="309ac2d8-bfc5-c1a7-ab6a-4f4cf86a1ba6.md">ViewBase</a>)</td></tr>
<tr>
<td><a href="b20e4dcf-0fd8-7bb5-03a8-0c77b0168719.md">KeyPress</a></td>
<td>Key has been pressed.<br />(Inherited from <a href="309ac2d8-bfc5-c1a7-ab6a-4f4cf86a1ba6.md">ViewBase</a>)</td></tr>
<tr>
<td><a href="0ee22a65-620c-6f78-ab66-7af58ee22bc3.md">KeyUp</a></td>
<td>Key has been released.<br />(Inherited from <a href="309ac2d8-bfc5-c1a7-ab6a-4f4cf86a1ba6.md">ViewBase</a>)</td></tr>
<tr>
<td><a href="31531b8d-41a3-9794-2d3c-9d01b86788c9.md">Layout</a></td>
<td>Perform a layout of the elements.<br />(Overrides <a href="23813921-9378-7d7e-4aec-e4bd375b938f.md">ViewComposite.Layout(ViewLayoutContext)</a>)</td></tr>
<tr>
<td><a href="70dabc71-fb88-4c6f-8428-7c3ef87e8351.md">LostFocus</a></td>
<td>Source control has lost the focus.<br />(Inherited from <a href="309ac2d8-bfc5-c1a7-ab6a-4f4cf86a1ba6.md">ViewBase</a>)</td></tr>
<tr>
<td>MemberwiseClone</td>
<td>Creates a shallow copy of the current Object.<br />(Inherited from Object)</td></tr>
<tr>
<td><a href="f85042cd-bd95-bd0e-2bf4-46cdc723c1af.md">MouseDown</a></td>
<td>Mouse button has been pressed in the view.<br />(Inherited from <a href="309ac2d8-bfc5-c1a7-ab6a-4f4cf86a1ba6.md">ViewBase</a>)</td></tr>
<tr>
<td><a href="38bba82f-9309-fc1b-1525-9f3f606bddfb.md">MouseEnter</a></td>
<td>Mouse has entered the view.<br />(Inherited from <a href="309ac2d8-bfc5-c1a7-ab6a-4f4cf86a1ba6.md">ViewBase</a>)</td></tr>
<tr>
<td><a href="3f0f21f8-e7fe-e45b-44b8-b5729b578e83.md">MouseLeave</a></td>
<td>Mouse has left the view.<br />(Inherited from <a href="309ac2d8-bfc5-c1a7-ab6a-4f4cf86a1ba6.md">ViewBase</a>)</td></tr>
<tr>
<td><a href="3891df9a-e10f-835d-bf0c-8e6d87e22df8.md">MouseMove</a></td>
<td>Mouse has moved inside the view.<br />(Inherited from <a href="309ac2d8-bfc5-c1a7-ab6a-4f4cf86a1ba6.md">ViewBase</a>)</td></tr>
<tr>
<td><a href="7ec191d5-ec44-9277-55cf-37ad06e7bfa4.md">MouseUp</a></td>
<td>Mouse button has been released in the view.<br />(Inherited from <a href="309ac2d8-bfc5-c1a7-ab6a-4f4cf86a1ba6.md">ViewBase</a>)</td></tr>
<tr>
<td><a href="321fbaec-a98f-43a3-4bfe-2f9a902b48ac.md">Recurse</a></td>
<td>Deep enumerate forward over children of the element.<br />(Inherited from <a href="467f805c-296b-06ec-42f1-e965af0d0f04.md">ViewComposite</a>)</td></tr>
<tr>
<td><a href="7c86dd65-8858-12ae-faa9-3955293dd2f4.md">Remove</a></td>
<td>Removes first occurrence of specified view.<br />(Inherited from <a href="467f805c-296b-06ec-42f1-e965af0d0f04.md">ViewComposite</a>)</td></tr>
<tr>
<td><a href="70b976ad-0b38-e25a-ac99-0f3ccb20838e.md">RemoveAt</a></td>
<td>Removes the view at the specified index.<br />(Inherited from <a href="467f805c-296b-06ec-42f1-e965af0d0f04.md">ViewComposite</a>)</td></tr>
<tr>
<td><a href="322b8970-6c40-2658-4e2e-34baa2377193.md">Render</a></td>
<td>Perform a render of the elements.<br />(Inherited from <a href="467f805c-296b-06ec-42f1-e965af0d0f04.md">ViewComposite</a>)</td></tr>
<tr>
<td><a href="0d72a0f3-fa00-f3f2-5015-7242f2b1ed8d.md">RenderAfter</a></td>
<td>Perform rendering after child elements are rendered.<br />(Inherited from <a href="309ac2d8-bfc5-c1a7-ab6a-4f4cf86a1ba6.md">ViewBase</a>)</td></tr>
<tr>
<td><a href="eaf4253b-79b4-29b9-eba4-b4f30feaa28d.md">RenderBefore</a></td>
<td>Perform rendering before child elements are rendered.<br />(Overrides <a href="0a5f30f4-0b1b-cf5e-adb7-1fab2b73a1d2.md">ViewBase.RenderBefore(RenderContext)</a>)</td></tr>
<tr>
<td><a href="fe98e7b1-69ec-b237-aa20-950affde8075.md">Reverse</a></td>
<td>Shallow enumerate backwards over children of the element.<br />(Inherited from <a href="467f805c-296b-06ec-42f1-e965af0d0f04.md">ViewComposite</a>)</td></tr>
<tr>
<td><a href="79b12670-919e-bc98-a571-046753f2d410.md">ReverseRecurse</a></td>
<td>Deep enumerate backwards over children of the element.<br />(Inherited from <a href="467f805c-296b-06ec-42f1-e965af0d0f04.md">ViewComposite</a>)</td></tr>
<tr>
<td><a href="a9620dfd-15c9-e3ce-a423-21f19e86e5e8.md">SetPalettes</a></td>
<td>Update the source palettes for drawing.</td></tr>
<tr>
<td>SortProperties</td>
<td>Sorts a collection of properties.<br />(Inherited from TypeConverter)</td></tr>
<tr>
<td><a href="3ab1d00f-2383-bda7-0e04-87cc578d4032.md">ToString</a></td>
<td>Obtains the String representation of this instance.<br />(Overrides <a href="e2b8320e-96b4-0e06-6e9f-da8f24b134e3.md">ViewComposite.ToString()</a>)</td></tr>
<tr>
<td><a href="1e5423e8-9273-25bc-6fe5-ea38a9b12a34.md">ViewFromPoint</a></td>
<td>Find the view that contains the specified point.<br />(Inherited from <a href="467f805c-296b-06ec-42f1-e965af0d0f04.md">ViewComposite</a>)</td></tr>
</table>

## See Also


#### Reference
<a href="79d2eac2-21f4-54ff-7552-b20c33c30600.md">Krypton.Toolkit Namespace</a>  
