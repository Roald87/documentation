# RenderContentConverter.Convert Method 
 

Converts an object that derives form IVortexObject or IValueTag into UI representation following 'PresentationType' pipeline.

**Namespace:**&nbsp;<a href="N_Vortex_Presentation_Wpf.md">Vortex.Presentation.Wpf</a><br />**Assembly:**&nbsp;Vortex.Presentation.Wpf (in Vortex.Presentation.Wpf.dll) Version: 1.3.21+Branch.tags/v1.3.21.Sha.d2d012c69d12da922e6e4a18ad43e5435cbba0f0

## Syntax

**C#**<br />
``` C#
public virtual Object Convert(
	Object value,
	Type targetType,
	Object parameter,
	CultureInfo culture
)
```


#### Parameters
&nbsp;<dl><dt>value</dt><dd>Type: <a href="https://docs.microsoft.com/dotnet/api/system.object" target="_blank">System.Object</a><br />object IVortexObject or IValueTag</dd><dt>targetType</dt><dd>Type: <a href="https://docs.microsoft.com/dotnet/api/system.type" target="_blank">System.Type</a><br />Target type</dd><dt>parameter</dt><dd>Type: <a href="https://docs.microsoft.com/dotnet/api/system.object" target="_blank">System.Object</a><br />Presentation type</dd><dt>culture</dt><dd>Type: <a href="https://docs.microsoft.com/dotnet/api/system.globalization.cultureinfo" target="_blank">System.Globalization.CultureInfo</a><br />Culture</dd></dl>

#### Return Value
Type: <a href="https://docs.microsoft.com/dotnet/api/system.object" target="_blank">Object</a><br /><a href="https://docs.microsoft.com/dotnet/api/system.windows.frameworkelement" target="_blank">FrameworkElement</a>

#### Implements
<a href="https://docs.microsoft.com/dotnet/api/system.windows.data.ivalueconverter.convert#System_Windows_Data_IValueConverter_Convert_System_Object_System_Type_System_Object_System_Globalization_CultureInfo_" target="_blank">IValueConverter.Convert(Object, Type, Object, CultureInfo)</a><br />

## See Also


#### Reference
<a href="T_Vortex_Presentation_Wpf_RenderContentConverter.md">RenderContentConverter Class</a><br /><a href="N_Vortex_Presentation_Wpf.md">Vortex.Presentation.Wpf Namespace</a><br />