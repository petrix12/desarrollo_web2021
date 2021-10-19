# Escuela de Desarrollo Web

## 000. Antes de iniciar
1. Crear proyecto en la página de [GitHub](https://github.com) con el nombre: **desarrollo_web2021**.
    + **Description**: Estudios sobre el desarrollo web.
    + **Public**.
2. En la ubicación raíz del proyecto en la terminal de la máquina local:
    + $ git init
    + $ git add .
    + $ git commit -m "Antes de iniciar"
    + $ git branch -M main
    + $ git remote add origin https://github.com/petrix12/desarrollo_web2021.git
    + $ git push -u origin main

## 001. Curso de Prework - Configuración de Entorno de Desarrollo en Windows
+ [Video 001](https://www.youtube.com/watch?v=uFKbVrapVb8)
+ [Video 002](https://www.youtube.com/watch?v=MYkGg4OEEfg)
+ [Video 003](https://www.youtube.com/watch?v=6TBDuBAm5ik)
+ [Video 004](https://www.youtube.com/watch?v=qu7JdFqlUrY)
+ [Video 005](https://www.youtube.com/watch?v=ewkk-brrLG0)
1. Commit:
    + $ git add .
    + $ git commit -m "Commit al 15-10-2021"
    + $ git push -u origin main
+ [Video 006](https://www.youtube.com/watch?v=3nEyhMuGv5g)
+ [Video 007](https://www.youtube.com/watch?v=lP55Y5t5KGQ)
2. Ejecutar en una terminal de **Windows 10**:
    + $ winver
    + **Nota**: verificar que la versión de Windows 10 sea superior a:
        + Versión 2004 (compilación SO 19041.450)
+ [Video 008]()
3. Instalar **Windows Subsystem for Linux**:
    + Ejecutar **Windows PowerShell** como administrador.
    + > dism.exe /online /enable-feature /featurename:Microsoft-Windows-Subsystem-Linux /all /norestart
    + > dism.exe /online /enable-feature /featurename:VirtualMachinePlatform /all /norestart
    + > wsl --set-default-version 2
    + Salida:
    ```txt
    Uso: wsl.exe [Argumento]

    Argumentos:

        --install <Opciones>
            Instalar las características de subsistema de Windows para Linux. Si no se especifica ninguna opción,
            las características recomendadas se instalarán junto con la distribución predeterminada.

            Para ver la distribución predeterminada, así como una lista de otras distribuciones válidas,
            use 'wsl --list --online'.

            Opciones:
                --distribution, -d [Argumento]
                    Especifica la distribución que se va a descargar e instalar por nombre.

                    Argumentos:
                        Un nombre de distribución válido (no distingue mayúsculas de minúsculas).

                    Ejemplos:
                        wsl --install -d Ubuntu
                        wsl --install --distribution Debian

        --list,-l [Opciones]
            Muestra las distribuciones.

            Opciones:
                --online, -o
                    Muestra una lista de las distribuciones disponibles para instalar con 'wsl --install'.

        --help
            Mostrar la información de uso.
    ```
    + Descargar e instalar [Ubuntu 20.04 LTS](https://www.microsoft.com/es-ve/p/ubuntu-2004-lts/9n6svws3rx71?rtc=1#activetab=pivot:overviewtab)
        + Ir a **Microsoft Store** en **Windows 10** y buscar:
            + Ubuntu 20.04 LTS
+ [Video 009](https://www.youtube.com/watch?v=-NmfHECKlO8)
4. Ir a **Microsoft Store** en **Windows 10** y buscar, descargar e instalar:
    + Windows Terminal
5. Ejecutar **Ubuntu 20.04 LTS** en **Windows 10**:
    + Enter new UNIX username: petrix
    + New password: ***
6. Comandos básicos:
    + $ pwd                 (ruta actual)
    + $ cd ..               (cambia la ruta al directorio padre)
    + $ cd /home/petrix     (cambia la ruta /home/petrix)
    + $ cd /                (cambia la ruta al directorio raíz del sistema actual)
    + $ cd mnt              (cambia la ruta a Windows)
        + $ cd c            (cambia la ruta al disco local c)
    + $ ls                  (muestra lo que habita en la ubicación actual)
    + $ cd ~                (cambia la ruta al directorio raíz de Ubuntu)
    + $ mkdir carpeta       (crear una carpeta)
    + $ sudo mkdir carpeta  (crear una carpeta con permisos de administrador)
    + $ touch archivo.ext   (crea el archivo archivo.ext)
    + $ mv archivo.ext dir2 (mueve el archivo archivo.ext al directorio dir2, de igual forma se puede mover carpetas)
7. En ubuntu:
    + Ubicarse en el directorio de trabajo de ubunto:
        + $ cd ~
    + Crear directorios:
        + $ mkdir personalProjects
        + $ mkdir proyectoDemoCursoPrework
    + Crear archivo:
        + $ touch index.html
    + Mover index.html a proyectoDemoCursoPrework
        + $ mv index.html proyectoDemoCursoPrework
    + Mover proyectoDemoCursoPrework a personalProjects
        + $ mv proyectoDemoCursoPrework personalProjects
    + Abrir el proyecto **proyectoDemoCursoPrework** con **VSCode** desde **ubuntu**:
        + $ cd personalProjects/proyectoDemoCursoPrework
        + $ code .
    + Instalar extensión VSCode:
        + Remote - WSL v0.58.2
        + Microsoft
        + Open any folder in the Windows Subsystem for Linux (WSL) and take advantage of Visual Studio Code's full feature set.
+ [Clase 010]()
8. En caso de no poder instalar **Windows Subsystem for Linux**, a continuación las indicaciones para instalar entonces **VirtualBox**:
    + [Clase -10 Insalacion de virtual box_files](/Modulo001/Clase-10-Insalacion-de-virtual-box_files.html)
9.  ddddd
*** VOY POR ACÁ ***

+ [Clase 011]()
+ [Video 012](https://www.youtube.com/watch?v=_9sIkov6KCc)
+ [Video 013](https://www.youtube.com/watch?v=9NjnFEtgChE)
+ [Video 014](https://www.youtube.com/watch?v=wOxVIArLsrg)





1. Commit:
    + $ git add .
    + $ git commit -m "Commit al 15-10-2021"
    + $ git push -u origin main