# IsInputChar Method


Determines if a character is an input character that the control recognizes.



## Definition
**Namespace:** <a href="79d2eac2-21f4-54ff-7552-b20c33c30600.md">Krypton.Toolkit</a>  
**Assembly:** Krypton.Toolkit (in Krypton.Toolkit.dll) Version: 80.23.10.287+8d7660f9dc5efd033fabe008ebfb904beab6d444

**C#**
``` C#
protected override bool IsInputChar(
	char charCode
)
```
**VB**
``` VB
Protected Overrides Function IsInputChar ( 
	charCode As Char
) As Boolean
```



#### Parameters
<dl><dt>  Char</dt><dd>The character to test.</dd></dl>

#### Return Value
Boolean  
true if the character should be sent directly to the control and not preprocessed; otherwise, false.

## See Also


#### Reference
<a href="d5f4ef00-45c7-03b8-460f-4b57e8740f0e.md">KryptonDateTimePicker Class</a>  
<a href="79d2eac2-21f4-54ff-7552-b20c33c30600.md">Krypton.Toolkit Namespace</a>  
