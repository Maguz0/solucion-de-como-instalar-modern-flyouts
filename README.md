# solucion-de-como-instalar-modern-flyouts
indicacion de como instalar nuevamente el modern flyouts aunque haya vencido paso a paso
lo primero ir a: https://github.com/ModernFlyouts-Community/ModernFlyouts/releases y descargar la beta: v0.10.0-beta.5 el mixsbundled y firma 
lo 2do es abrir CMD O POWERSHELL COMO ADMINISTRADOR y pegar: Set-Date -Date "01/09/2025"
(dato importante haber desactivado ESTABLECER LA HORA AUTOMATICO en la hora) 
una vez descargado los 2 archivos instalar la firma y supongo que va a quedar en descarga moverlo a escritorio 
pegar esto en powershell: Add-AppxPackage -Path "C:\Users\PC\Desktop\ModernFlyouts.Package_0.9.8622.0_x86_x64_arm64.msixbundle" reemplaza en tu caso 
el archivo misxbundled dar click derecho - copiar como ruta de acceso pa pegarlo deberia funciona 
esperar un momento en lo que pasa la instalacion y luego usar: w32tm /resync o reactivar: ESTABLECER LA HORA AUTOMATICO 
