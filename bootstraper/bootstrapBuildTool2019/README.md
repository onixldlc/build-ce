for compiling .net

```
vs_BuildTool.exe `
  --add Microsoft.Component.MSBuild `
  --add Microsoft.VisualStudio.Component.CoreBuildTools `
  --add Microsoft.VisualStudio.Component.Roslyn.Compiler `
  `
  --add Microsoft.NetCore.Component.SDK `
  --add Microsoft.NetCore.Component.Runtime.3.1 `
  --add Microsoft.Net.Component.4.TargetingPack `
  --add Microsoft.Net.Component.4.6.1.TargetingPack `
  --add Microsoft.NetCore.Component.Runtime.5.0 `
  `
  --add Microsoft.VisualStudio.Component.VC.v141.x86.x64`
  --add Microsoft.VisualStudio.Component.VC.14.29.16.10.x86.x64
```
