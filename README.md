IniSharp
========

C# INI Parser

  ```csharp
    var unrootedPath = "settings.ini";
    var myIni = new IniFile(unrootedPath)
  ```
  or

  ```csharp
    var rootedPath = Path.Combine(Enviroment.GetFolderPath(SpecialFolders.Desktop),"settings.ini";
    var myIni = new IniFili(rootedPath);
  ```


