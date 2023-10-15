# FindString(String, Int32) Method


Finds the first item after the given index which starts with the given string. The search is not case sensitive.



## Definition
**Namespace:** <a href="79d2eac2-21f4-54ff-7552-b20c33c30600.md">Krypton.Toolkit</a>  
**Assembly:** Krypton.Toolkit (in Krypton.Toolkit.dll) Version: 80.23.10.287+8d7660f9dc5efd033fabe008ebfb904beab6d444

**C#**
``` C#
public int FindString(
	string str,
	int startIndex
)
```
**VB**
``` VB
Public Function FindString ( 
	str As String,
	startIndex As Integer
) As Integer
```



#### Parameters
<dl><dt>  String</dt><dd>The String to search for.</dd><dt>  Int32</dt><dd>The zero-based index of the item before the first item to be searched. Set to -1 to search from the beginning of the control.</dd></dl>

#### Return Value
Int32  
The zero-based index of the first item found; returns -1 if no match is found, or 0 if the s parameter specifies Empty.

## See Also


#### Reference
<a href="6e3c34ba-a54b-38d7-c887-9815158b827f.md">KryptonComboBox Class</a>  
<a href="d66cb3dd-0fd4-5c7b-fe25-324190ba079c.md">FindString Overload</a>  
<a href="79d2eac2-21f4-54ff-7552-b20c33c30600.md">Krypton.Toolkit Namespace</a>  
