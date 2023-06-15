# Edge Auto Disabler

is an service build over Visual Studio to be installed using any method to install services, examples as following:

on PowerShell using:

New-Service -Name "EdgeAutoDisabler" -BinaryPathName C:\Services\EdgeAutoDisabler.exe
Start-Service -Name "EdgeAutoDisabler"

on CMD using:

sc create EdgeAutoDisabler type=own start=auto error=normal binpath=C:\Services\EdgeAutoDisabler.exe displayname=EdgeAutoDisabler
