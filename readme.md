> This is a fork of [**AvaloniaVS**](https://github.com/AvaloniaUI/AvaloniaVS) repo with everything up until
> it changed its license and became a commercial product.
>
> This code is distributed under the original **MIT** license that was in effect at the time of the split.

---
# Avalonia for Visual Studio
This repository is used to generate Avalonia Visual Studio extensions.
Avalonia Visual Studio extension adds such capabilities to your Visual Studio:
- XAML code completion.
- XAML previewer.
- It bundles Avalonia templates in your Visual Studio.
- Icons for axaml files.

### VSIX package for Visual Studio 2022/2026

Download latest release for [Releases](https://github.com/fgsfds/AvaloniaVS_MIT/releases) and run **.vsix** file.

# Debugging
If you want to debug Avalonia previewer extension the *easiest* way to do that is [VS Experimental instance](https://docs.microsoft.com/en-us/visualstudio/extensibility/the-experimental-instance?view=vs-2019).
To run it you simply need to set **AvaloniaVS.csproj** as startup project and run it,it will open VS Experimental instance,you can run here your repro and put the breakpoints in the original VS in AvaloniaVS project.

**Note:**

This way to debug application will only help you if your issue is directly in AvaloniaVS project,if your issue is somewhere in Avalonia code,but it is reproducible only with Avalonia Previewer please consider this article - [https://docs.avaloniaui.net/docs/0.10.x/guides/developer-guides/debugging-previewer](https://docs.avaloniaui.net/docs/0.10.x/guides/developer-guides/debugging-previewer)
