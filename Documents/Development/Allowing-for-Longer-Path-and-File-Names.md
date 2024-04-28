# How to allow longer path/file names

As of V90.##, you will need to allow for longer path/file names, as this is not enabled by default in Windows. Failure to do so will result in the [MSB3553](https://learn.microsoft.com/en-us/visualstudio/msbuild/errors/msb3553?view=vs-2022) compiler error.

There are two ways that you can do this. They are:-

1. Via `gpedit`
2. Via an elevated PowerShell prompt