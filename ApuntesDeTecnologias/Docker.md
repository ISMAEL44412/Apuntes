# Docker Soluciones

## 1 - Virtualization Support Not Detected
1. Abrimos power Shell como administrador y escribimos lo siguiente
```shell
dism.exe /online /enable-feature /featurename:Microsoft-Windows-Subsystem-Linux /all /norestart
```
y cuando termine escribimos
```shell
dism.exe /online /enable-feature /featurename:VirtualMachinePlatform /all /norestart
```