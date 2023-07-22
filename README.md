# cfgfunctions-generator-py
CfgFunctions generator script for Arma 3, written in Python. See also Visual Studio Code plugin for the same purpose: https://marketplace.visualstudio.com/items?itemName=Ezcoo.cfgfunctionsgeneratorarma3

## Usage:

- Create `functions` folder in the mission/mod directory.
- Download/pull and configure `generate.py` (add your personal tag defined in the file) and place it in the `functions` folder you created in the previous step.
- Run `generate.py` with Python runtime environment installed on your system from terminal/command line (see Requirements).

## Requirements

- Python (version >= 3.9) installed on your system.
- `Path` and `glob` Python packages installed as dependencies.
- Subfolders in `functions` folder of your project (they act as the names of the `CfgFunctions` categories).
- Function files must be placed in those category folders or their subfolders.
- Filenames have to start with `fn_` (and have `.sqf` as file extension naturally).
