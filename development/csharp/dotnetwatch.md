# dotnet watch

**Source**: [dotnet watch (like nodemon for NodeJS)](https://davidemanske.com/dotnet-watch-like-nodemon-for-nodejs/)

## To Install

```console
foo@bar:~$ dotnet add package Microsoft.DotNet.Watcher.Tools
```

## Add to Your .csproj File

```xml
<ItemGroup>
    <DotNetCliToolReference Include="Microsoft.DotNet.Watcher.Tools" Version="2.0.2" />
</ItemGroup>
```

## To Run

```console
foo@bar:~$ dotnet watch run
```

## Ignoring files

```xml
<ItemGroup> <!-- extends watching group to include *.js files -->
    <Watch Include="**\*.js" Exclude="node_modules\**\*.js;$(DefaultExcludes)" />
</ItemGroup>
```
