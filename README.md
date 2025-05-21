# RAW

Este repositorio incluye una colección de scripts de PowerShell y otros recursos relacionados.

## Limpieza

- Limpiar cuadro de diálogos (Win + R)
  - [Script de PowerShell](/scripts/Limpieza/CuadroDialogos.ps1)

- Limpiar historial de comandos PowerShell
  - Versión 1: [Eliminación del archivo de logs](/scripts/Limpieza/LimpiarPowerShellHistorialComandos.ps1)
  - Versión 2: [Vaciado del archivo de logs](/scripts/Limpieza/LimpiarPowershellConVaciado.ps1)


Get-WmiObject -Class Win32_ComputerSystem | Select-Object Name, SystemType

