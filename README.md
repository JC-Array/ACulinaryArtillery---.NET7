# BUILD

1) Install dotnet sdk 7.0.x  https://dotnet.microsoft.com/en-us/download/dotnet/7.0
2) Set VINTAGE_STORY environment variable as detailed in modding documentation: https://wiki.vintagestory.at/index.php/Modding:Setting_up_your_Development_Environment#Setup_the_Environment
2a) After being set, you need to close and reopen powershell/terminal for the environment variable to be loaded into your terminal again
3) Run 
```bash
dotnet build .\ACulinaryArtillery.csproj
```
4) Navigate to .\bin\Debug\Mods
5) Zip all the files in that folder
6) Rename Mods.zip to "ACulinaryArtillery 1.2.1.zip"
6) Add zip to your mods folders.  If playing multiplayer, users need to manually install this version of the modding
6a) To help enforce the manuall install, you can update modinfo.json to a version not yet released, which will cause a popup ingame stating a manuall install is needed.
