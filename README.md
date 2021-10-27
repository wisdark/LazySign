# LazySign
Create fake certs for binaries using windows binaries and the power of bat files

Over the years, several cool tools have been released that are capeable of stealing or forging fake signatures for binary files. 
All of these tools however, have additional dependencies which require Go,python,... 

This repo gives you the opportunity of fake signing with 0 additional dependencies, all of the binaries used are part of Microsoft's own devkits. 
I took the liberty of writing a bat file to make things easy.

The `Invoke-LazySign.ps1` PowerShell script is another option, which doesn't require additional dependencies nor binaries, just clean and dry PowerShell cmdlets.

So if you are lazy like me, just clone the git, run either the bat or the PowerShell script, follow the instructions and enjoy your new fake signed binary. 
With some adjustments it could even be used to sign using valid certs as well ¯\\_(ツ)_/¯

 