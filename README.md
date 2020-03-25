# VictorHugoRoman
Problemas de aceleración de hardware, Emulador Android Visual Studio
En este tutorial se asume que tenemos configurado el emulador de android pero la aceleracion de hardware no handa bien,
La configuracion se hicieron en la siguiente maquina:

IDE: Visual Studio Community 2017 (Dev Android Xamarin)
Procesador:	Intel(R) Core(TM) i5-7400 CPU @ 3.00GHz, 3001 Mhz, 4 procesadores principales, 4 procesadores lógicos
Memoria física instalada (RAM)	8.00 GB
Windows 10 Pro
PC Compatible Hyper-V

La configuracion puede funcionar en cualquier maquina siempre y cuando cumpla con los requisitos para emular android

Versiones de windows que tienen Hyper-V instalado:
Windows 10 Enterprise
Windows 10 Pro
Windows 10 Education

Las tecnologías de virtualización siguientes están disponibles para la aceleración de Android Emulator:
Hyper-V y Windows Hypervisor Platform (WHPX) de Microsoft. Hyper-V es una característica de virtualización de Windows que permite ejecutar 
sistemas de equipos virtualizados en un equipo host físico, en algunas compilaciones de windows 10 la configuracion WHPX viene separada de hyper-v en mi caso q es windows 10 pro Versión	10.0.18363 compilación 18363 viene de forma nativa en la configuracion hyper-v, aunque me tocó configurarla por separa desde powerShell.

Hardware Accelerated Execution Manager (HAXM) de Intel. HAXM es un motor de virtualización para los equipos que ejecutan CPU de Intel.
