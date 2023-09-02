# Wiindows-Update
Created this PowerShell to install windows updates

Set-ExecutionPolicy Unrestricted

Set-ExecutionPolicy RemoteSigned

Install-Module -Name PSWindowsUpdate

Get-WindowsUpdate -AcceptAll -Install -AutoReboot -RecurseCycle 5 -MicrosoftUpdate

Start-Sleep -Prompt "Press Enter To Exit"
