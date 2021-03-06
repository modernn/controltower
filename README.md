![Control Tower](./artwork/control-tower-logo.png)

[![Verify code quality status](https://github.com/wmeints/controltower/workflows/Verify%20code%20quality/badge.svg)](https://github.com/wmeints/controltower/actions)

An [OctoPrint](https://octoprint.org/) inspired .NET Core based 3D Printer controller that runs from your Raspberry PI.

## Goals

- Provide a .NET Core based solution for controlling your 3D printer
- Demonstrate how easy it is to run .NET Core on Raspberry PI
- Demonstrate how to use Blazor to build rich clientside applications

## Getting started

Download one of the releases that matches your operating system and unpack it on your system.
Next, follow these steps for each individual os type:

### Running on Windows with the portable executable

From the directory where you've downloaded the controltower executable, run
the following command:

```powershell
dotnet controltower.dll
```

### Running on Raspbian

From the directory where you've downloaded the control tower executable, run
the following command:

```bash
./controltower
```

## Documentation

The overall architecture and other information can be found on the [Wiki](https://github.com/wmeints/controltower/wiki).

## Helping out

Want to chip in and write some code? I'd love to get some help with this project.
You can find a list of features I want to include in the product on the issues page. Can't find something you want? Let me know
by submitting new issues.
