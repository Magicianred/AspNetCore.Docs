---
no-loc: [appsettings.json, "ASP.NET Core Identity", cookie, Cookie, Blazor, "Blazor Server", "Blazor WebAssembly", "Identity", "Let's Encrypt", Razor, SignalR]
---
<!-- Options common to Razor Pages and Controller -->
| Option               | Description|
| ----------------- | ------------ |
| --model or -m  | Model class to use. |
| --dataContext or -dc  | The `DbContext` class to use or the name of the class to generate. |
| --bootstrapVersion or -b  | Specifies the bootstrap version. Valid values are `3` or `4`. Default is `4`. If needed and not present, a *wwwroot* directory is created that includes the bootstrap files of the specified version. |
| --referenceScriptLibraries or -scripts |  Reference script libraries in the generated views. Adds `_ValidationScriptsPartial` to Edit and Create pages. |
| --layout or -l | Custom Layout page to use. |
| --useDefaultLayout or -udl | Use the default layout for the views. |
| --force or -f | Overwrite existing files. |
| --useSqlite or -sqlite | Flag to specify if `DbContext` should use SQLite instead of SQL Server. |