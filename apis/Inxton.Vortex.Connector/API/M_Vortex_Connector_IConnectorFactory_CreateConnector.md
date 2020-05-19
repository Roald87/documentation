# IConnectorFactory.CreateConnector Method 
 

Creates new instance of connector.

**Namespace:**&nbsp;<a href="N_Vortex_Connector.md">Vortex.Connector</a><br />**Assembly:**&nbsp;Vortex.Connector (in Vortex.Connector.dll) Version: 1.0.0+Branch.master.Sha.24c869c7af4ddc9e28426985d5ac87eee1422bb2

## Syntax

**C#**<br />
``` C#
public abstract IConnector CreateConnector(
	Object[] parameters
)
```


#### Parameters
&nbsp;<dl><dt>parameters</dt><dd>Type: <a href="https://docs.microsoft.com/dotnet/api/system.object" target="_blank">System.Object</a>[]<br />Connector parameters</dd></dl>

#### Return Value
Type: <a href="T_Vortex_Connector_IConnector.md">IConnector</a><br />

## Remarks
This class is typically used by the 'vortex builder' to create value types (tags) for given connector.

## See Also


#### Reference
<a href="T_Vortex_Connector_IConnectorFactory.md">IConnectorFactory Class</a><br /><a href="N_Vortex_Connector.md">Vortex.Connector Namespace</a><br />