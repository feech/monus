# monus
time management data collector


to collect data from win32 systems
Get-Process |where {$_.mainWindowTItle} |format-table id,name,mainwindowtitle,processname –AutoSize

detailed info at
https://docs.microsoft.com/en-us/powershell/module/microsoft.powershell.management/get-process?view=powershell-6
https://docs.microsoft.com/en-us/dotnet/api/system.diagnostics.process?view=netframework-4.7.2
