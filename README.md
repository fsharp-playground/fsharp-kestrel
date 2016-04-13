### Demo of using Kestrel with F♯

Working with `dotnet cli 1.0.0-beta-002071`

### How to run

1. Run `dotnet restore` to restore packages
1. Run `dotnet run` to compile and start server

### Issue

```bash
$ dotnet build                                                                                                                                                                                    1 ↵
Compiling fsharp-kestrel for .NETStandardApp,Version=v1.5
No executable found matching command "dotnet-compile-fsc"
/usr/local/share/dotnet/dotnet compile-fsc @/Users/wk/Source/fsharp/fsharp-kestrel/obj/Debug/netstandardapp1.5/dotnet-compile.rsp returned Exit Code 1

Compilation failed.
    0 Warning(s)
    0 Error(s)

Time elapsed 00:00:01.4789595
```
