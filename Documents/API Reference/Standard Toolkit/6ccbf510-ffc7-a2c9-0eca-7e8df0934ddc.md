# XmlAttributeToText Method


Read the named attribute value but if no attribute is found then return the provided default.



## Definition
**Namespace:** <a href="79d2eac2-21f4-54ff-7552-b20c33c30600.md">Krypton.Toolkit</a>  
**Assembly:** Krypton.Toolkit (in Krypton.Toolkit.dll) Version: 80.23.10.287+8d7660f9dc5efd033fabe008ebfb904beab6d444

**C#**
``` C#
public static string XmlAttributeToText(
	XmlReader xmlReader,
	string name,
	string defaultValue = ""
)
```
**VB**
``` VB
Public Shared Function XmlAttributeToText ( 
	xmlReader As XmlReader,
	name As String,
	Optional defaultValue As String = ""
) As String
```



#### Parameters
<dl><dt>  XmlReader</dt><dd>Xml reader to load information from.</dd><dt>  String</dt><dd>Attribute name.</dd><dt>  String  (Optional)</dt><dd>Default value.</dd></dl>

#### Return Value
String  
\[Missing &lt;returns&gt; documentation for "M:Krypton.Toolkit.XmlHelper.XmlAttributeToText(System.Xml.XmlReader,System.String,System.String)"\]

## See Also


#### Reference
<a href="51091e9d-6423-049a-ae4f-e48900b46077.md">XmlHelper Class</a>  
<a href="79d2eac2-21f4-54ff-7552-b20c33c30600.md">Krypton.Toolkit Namespace</a>  
