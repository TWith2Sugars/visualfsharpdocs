# Core.CompilationSourceNameAttribute Class (F#)

This attribute is inserted automatically by the F# compiler to tag methods which are given the [CompiledName](http://msdn.microsoft.com/en-us/library/fb4ca03a-86ae-4334-b6a0-3de01e98904d) attribute. It is not intended for use from user code.

**Namespace/Module Path:** Microsoft.FSharp.Core

**Assembly:** FSharp.Core (in FSharp.Core.dll)


## CAPS_SYNTAX_MD

```
[<AttributeUsage(AttributeTargets.All, AllowMultiple = false)>]
[<Sealed>]
type CompilationSourceNameAttribute =
class
new CompilationSourceNameAttribute : string -> CompilationSourceNameAttribute
member this.SourceName :  string
end
```

## CAPS_REMARKS_MD
You can also use the short form of the name, **CompilationSourceName**.


## Constructors


|Member|Description|
|------|-----------|
|[new](http://msdn.microsoft.com/en-us/library/d27cb025-94af-4f28-801b-98e181ecea4d)|Creates an instance of the attribute.|

## Instance Members


|Member|Description|
|------|-----------|
|[SourceName](http://msdn.microsoft.com/en-us/library/9796f386-b537-467b-b832-00d9f111f512)|Indicates the name of the entity in F# source code.|

## Platforms
Windows 8, Windows 7, Windows Server 2012, Windows Server 2008 R2


## Version Information
**F# Core Library Versions**

Supported in: 2.0, 4.0, Portable




## See Also
[Microsoft.FSharp.Core Namespace &#40;F&#35;&#41;](Microsoft.FSharp.Core+Namespace+%28F%23%29.md)
