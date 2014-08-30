IniSharp
========

C# INI Parser

'''cs
var unrootedPath = "settings.ini"; //this create ini in application path
var myIni = new IniFile(unrootedPath)
'''

'''cs
var rootedPath = Path.Combine(Enviroment.GetFolderPath(SpecialFolders.Desktop),"settings.ini"; //this use ini you provvide
var myIni = new IniFili(rootedPath);
'''
