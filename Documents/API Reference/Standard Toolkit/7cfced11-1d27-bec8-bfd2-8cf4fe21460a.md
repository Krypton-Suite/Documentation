# KryptonRibbonGroupCustomControl Class


Represents a ribbon group custom control.



## Definition
**Namespace:** <a href="1e9bc734-cff9-e9b8-f013-94cdac669794.md">Krypton.Ribbon</a>  
**Assembly:** Krypton.Ribbon (in Krypton.Ribbon.dll) Version: 80.23.10.287+8d7660f9dc5efd033fabe008ebfb904beab6d444

**C#**
``` C#
public class KryptonRibbonGroupCustomControl : KryptonRibbonGroupItem
```
**VB**
``` VB
Public Class KryptonRibbonGroupCustomControl
	Inherits KryptonRibbonGroupItem
```

<table><tr><td><strong>Inheritance</strong></td><td>Object  →  MarshalByRefObject  →  Component  →  <a href="42b4e823-3d0e-29bf-ca83-927a7a58295d.md">KryptonRibbonGroupItem</a>  →  KryptonRibbonGroupCustomControl</td></tr>
</table>



## Constructors
<table>
<tr>
<td><a href="a4f88575-d705-5dfb-2e8a-3e77bdc4d3ac.md">KryptonRibbonGroupCustomControl</a></td>
<td>Initialise a new instance of the KryptonRibbonGroupCustom class.</td></tr>
</table>

## Properties
<table>
<tr>
<td><a href="c9f41166-b541-4efc-c022-7bf3fad1b338.md">BindingContext</a></td>
<td><br />(Inherited from <a href="42b4e823-3d0e-29bf-ca83-927a7a58295d.md">KryptonRibbonGroupItem</a>)</td></tr>
<tr>
<td>CanRaiseEvents</td>
<td>Gets a value indicating whether the component can raise an event.<br />(Inherited from Component)</td></tr>
<tr>
<td><a href="302e2c6c-a240-ed7c-5bbf-0db525ef4a32.md">ChainVisible</a></td>
<td>Get a value indicating if all parent containers are visible.<br />(Inherited from <a href="42b4e823-3d0e-29bf-ca83-927a7a58295d.md">KryptonRibbonGroupItem</a>)</td></tr>
<tr>
<td>Container</td>
<td>Gets the IContainer that contains the Component.<br />(Inherited from Component)</td></tr>
<tr>
<td><a href="4bc2c6e0-3b11-87d8-aae9-01ff91aed22b.md">CustomControl</a></td>
<td>Gets and sets the custom control for display inside ribbon element.</td></tr>
<tr>
<td><a href="27c19a8c-9d52-40d5-9190-6d7fb79ce391.md">DataBindings</a></td>
<td>Retrieves the bindings for this control.<br />(Inherited from <a href="42b4e823-3d0e-29bf-ca83-927a7a58295d.md">KryptonRibbonGroupItem</a>)</td></tr>
<tr>
<td>DesignMode</td>
<td>Gets a value that indicates whether the Component is currently in design mode.<br />(Inherited from Component)</td></tr>
<tr>
<td><a href="fd7eda1a-32e4-8e25-fe4e-7c4aaba1c87b.md">Enabled</a></td>
<td>Gets and sets the enabled state of the custom control.</td></tr>
<tr>
<td>Events</td>
<td>Gets the list of event handlers that are attached to this Component.<br />(Inherited from Component)</td></tr>
<tr>
<td><a href="8cf8faf7-738d-c4bd-1d6b-959eb48578d4.md">KeyTip</a></td>
<td>Gets and sets the key tip for the ribbon group custom control.</td></tr>
<tr>
<td><a href="affdda5e-84bc-be1d-b02f-384a5a41778a.md">ShortcutKeys</a></td>
<td>Gets and sets the shortcut key combination.</td></tr>
<tr>
<td>Site</td>
<td>Gets or sets the ISite of the Component.<br />(Inherited from Component)</td></tr>
<tr>
<td><a href="8f0958de-84a9-b6c7-700f-32549d83cf88.md">Tag</a></td>
<td>Gets and sets user-defined data associated with the object.<br />(Inherited from <a href="42b4e823-3d0e-29bf-ca83-927a7a58295d.md">KryptonRibbonGroupItem</a>)</td></tr>
<tr>
<td><a href="2816977c-3d1a-0173-9bb8-4f2587b7ec5b.md">ToolTipValues</a></td>
<td>Gets access to the Wrapped Controls Tooltips.<br />(Overrides <a href="ab122b1c-b5e5-dfd9-e66a-286ea03ea3cb.md">KryptonRibbonGroupItem.ToolTipValues</a>)</td></tr>
<tr>
<td><a href="7b11033f-20e2-0969-2a01-7366c8a1f2b6.md">Visible</a></td>
<td>Gets and sets the visible state of the custom control.<br />(Overrides KryptonRibbonGroupItem.Visible)</td></tr>
</table>

## Methods
<table>
<tr>
<td>Dispose()</td>
<td>Releases all resources used by the Component.<br />(Inherited from Component)</td></tr>
<tr>
<td><a href="167d4637-8252-4866-c11d-eefdad1d1e2f.md">Dispose(Boolean)</a></td>
<td>Clean up any resources being used.<br />(Overrides Component.Dispose(Boolean))</td></tr>
<tr>
<td>Equals</td>
<td>Determines whether the specified object is equal to the current object.<br />(Inherited from Object)</td></tr>
<tr>
<td>Finalize</td>
<td>Releases unmanaged resources and performs other cleanup operations before the Component is reclaimed by garbage collection.<br />(Inherited from Component)</td></tr>
<tr>
<td>GetHashCode</td>
<td>Serves as the default hash function.<br />(Inherited from Object)</td></tr>
<tr>
<td>GetLifetimeService</td>
<td>Retrieves the current lifetime service object that controls the lifetime policy for this instance.<br />(Inherited from MarshalByRefObject)<br /><strong>Obsolete.</strong></td></tr>
<tr>
<td>GetService</td>
<td>Returns an object that represents a service provided by the Component or by its Container.<br />(Inherited from Component)</td></tr>
<tr>
<td>GetType</td>
<td>Gets the Type of the current instance.<br />(Inherited from Object)</td></tr>
<tr>
<td><a href="ff1341b3-cbdc-1a79-556e-f7478a8da9f4.md">Hide</a></td>
<td>Make the ribbon group hidden.</td></tr>
<tr>
<td>InitializeLifetimeService</td>
<td>Obtains a lifetime service object to control the lifetime policy for this instance.<br />(Inherited from MarshalByRefObject)<br /><strong>Obsolete.</strong></td></tr>
<tr>
<td>MemberwiseClone()</td>
<td>Creates a shallow copy of the current Object.<br />(Inherited from Object)</td></tr>
<tr>
<td>MemberwiseClone(Boolean)</td>
<td>Creates a shallow copy of the current MarshalByRefObject object.<br />(Inherited from MarshalByRefObject)</td></tr>
<tr>
<td><a href="b727631d-fde9-d7bf-b117-9e5b0db807e0.md">OnPropertyChanged</a></td>
<td>Raises the PropertyChanged event.</td></tr>
<tr>
<td><a href="3de897b4-b192-eaab-fc36-4704b56e343c.md">ResetShortcutKeys</a></td>
<td>Resets the ShortcutKeys property to its default value.</td></tr>
<tr>
<td><a href="4c31e104-2033-89a2-6523-f8f6d16791ca.md">ResetToolTipValues</a></td>
<td>Resets the ToolTipValues property to its default value.<br />(Inherited from <a href="42b4e823-3d0e-29bf-ca83-927a7a58295d.md">KryptonRibbonGroupItem</a>)</td></tr>
<tr>
<td><a href="4ed3c001-5bc0-9e13-f1fe-efe385b02f34.md">Show</a></td>
<td>Make the ribbon group visible.</td></tr>
<tr>
<td>ToString</td>
<td>Returns a String containing the name of the Component, if any. This method should not be overridden.<br />(Inherited from Component)</td></tr>
</table>

## Events
<table>
<tr>
<td>Disposed</td>
<td>Occurs when the component is disposed by a call to the Dispose() method.<br />(Inherited from Component)</td></tr>
<tr>
<td><a href="863b4d85-805f-1f70-cf14-74e863021b98.md">PropertyChanged</a></td>
<td>Occurs after the value of a property has changed.</td></tr>
</table>

## Fields
<table>
<tr>
<td><a href="2b4a688f-28a6-a1ec-8dcf-1006667ef77f.md">_toolTipValues</a></td>
<td><br />(Inherited from <a href="42b4e823-3d0e-29bf-ca83-927a7a58295d.md">KryptonRibbonGroupItem</a>)</td></tr>
</table>

## See Also


#### Reference
<a href="1e9bc734-cff9-e9b8-f013-94cdac669794.md">Krypton.Ribbon Namespace</a>  
