IniSharp
========

C# INI Parser

###USAGE


'''csharp
var unrootedPath = "settings.ini"; //this create ini in application path
var rootedPath = Path.Combine(Enviroment.GetFolderPath(SpecialFolders.Desktop),"settings.ini"; //this use ini you provvide
var myIni = new IniFile(unrootedPath)
  or
var myIni = new IniFili(rootedPath);
'''
