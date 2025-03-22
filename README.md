# Kex8
Windows 8.1 API Extensions

For now, only kernel32.dll and user32.dll wrappers dll.
To use it, change kernel32.dll to kernelmu.dll and user32.dll to userex.dll in application import directory (sometimes user32.dll may be in delay loaded table, it can be changed via HEX editor)
