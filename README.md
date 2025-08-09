# Tris to Quads Windows

## Overview

Add a proper command line arguments for Windows Powershell cli to install PulP python external package into Blender working environment. More specifically to tackle missing PulP package issue in Windows operating system when using Tris to Quads addon originally made by Tsutomu Saito

*copy this cli args to windows powershell, and change ***YourName*** with your actual user name:*

## Proper PulP Installation
```
& "C:\Program Files\Blender Foundation\Blender 4.5\4.5\python\bin\python.exe" -m pip install pulp --target "C:\Users\YourName\AppData\Roaming\Blender Foundation\Blender\4.5\scripts\modules"
```

*additionaly you can check if folder name pulp exists in this specific directory*

```
C:\Users\YourName\AppData\Roaming\Blender Foundation\Blender\4.5\scripts\modules
```
if installed correctly "PulP is Installed" will shown on ***Rulesobeyer Optimized Tris to Quads Converter*** addons preferences menu.

## Credits

- **Original Author**: Tsutomu Saito (https://github.com/SaitoTsutomu/Tris-Quads-Ex)
- **Improved Version**: Rulesobeyer (https://github.com/Rulesobeyer/)