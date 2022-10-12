# Lua Remote DeBugger for Visual Studio Code

Allows debugging embedded Lua VMs through Visual Studio Code.

It requires a Lua remote debugger extension on the VM to work:
- [Lua remote debugger](https://github.com/satoren/LRDB)
- [Garry's mod remote debugger](https://github.com/danielga/gm_rdb)

![Lua debug](images/demo.gif)

Please also see the [developer docs](Readme_devs.md) if you want to work on it.

## Features

- Supports Windows, macOS and Linux
- Add/remove breakpoints
- Conditional breakpoints
- Continue, pause, step over, step in, step out
- Local, global, \_ENV, upvalue variables and arguments
- Watch window
- Evaluate expressions
- Remote debugging over TCP

## Requirements

One of those lua Remote Debugger:
- [Garry's Mod Lua Remote Debugger](https://github.com/danielga/gm_rdb/releases)
- [Lua Remote Debugger](https://github.com/satoren/vscode-lrdb)

## Usage

Start the debugger server in your embedded Lua, then attach VS Code to it.

How to use:
- in [BeamNG](Readme_BeamNG.md)
- in [Garry's Mod](Readme_GM.md)

# Credits

Thank you so much to everyone working on this tech in team effort! :)

Based on the work from:
- [danielga/vscode-gmrdb](https://github.com/danielga/vscode-gmrdb)
- [satoren/vscode-lrdb](https://github.com/satoren/vscode-lrdb)
- [kapecp/vscode-lrdb](https://github.com/kapecp/vscode-lrdb)

