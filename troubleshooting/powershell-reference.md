# PowerShell / Windows Troubleshooting Reference

## Network
ipconfig /all
ping <address>
nslookup <name>
tracert <address>

## Connectivity
Test-NetConnection <host> -Port 443
Test-NetConnection <host> -Port 3389

## Processes
Get-Process | Sort-Object CPU -Descending | Select-Object -First 10

## Services
Get-Service
Get-Service | Where-Object Status -eq "Stopped"

## General
whoami
systeminfo
