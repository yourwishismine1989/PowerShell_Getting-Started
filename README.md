# PowerShell_Getting-Started
A quick how to with your first script example

##__install PowerShell__
 
### Setup linux distro (tested on Ubuntu 22.04 on 09/26/2023)
#### https://learn.microsoft.com/en-us/powershell/scripting/install/installing-powershell-on-linux?view=powershell-7.3

 
### Setup Windows (tested on Windows 11 on 09/26/2023)
#### https://learn.microsoft.com/en-us/powershell/scripting/install/installing-powershell-on-windows?view=powershell-7.3

##__hello-world__ (tested on Ubuntu 22.04 on 09/26/2023)
/usr/bin/pwsh 
touch hello-world.ps1 
nano ./hello-world.ps1 
[String]$message = "Hello World" 
Write-Host -BackgroundColor $bgClr -ForegroundColor $fgClr "$message" 
CTRL-o -> ENTER 
CTRL-x 
./hello-world.ps1 
