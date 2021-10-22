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
    + [Insalacion de Virtual Box](/Modulo001/Clase-10-Insalacion-de-virtual-box.html)
+ [Clase 011]()
9. Instalación de Ubuntu en una máguina virtual:
    + [Instalación de Ubuntu en máquina virtual](/Modulo001/Clase-11-Instalando-Ubuntu-en-una-maquina-virtual.html)
+ [Video 012](https://www.youtube.com/watch?v=_9sIkov6KCc)
10. Abrir **Windows Terminal**.
11. Modificar el archivo **C:\Users\bazop\AppData\Local\Packages\Microsoft.WindowsTerminal_8wekyb3d8bbwe\LocalState\settings.json** con VSCode para indicar la shell por defecto.
12. Cerrar y volver abrir la terminal.
13. En **Windows Terminal** ejecutar:
    + $ cd ~
    + $ cd personalProjects
    + $ cd proyectoDemoCursoPrework
    + $ code .
14. Diseñar el archivo index.html con el **VSCode**:
    ```html
    ```
15. Instalar la extensión Live Server en en VSCode de Ubuntu y levantar la página **index.html**.
16. Volver a la terminal y ejecutar:
    + $ cat index.html          (muestra el contenido de un archivo)
    + $ man cat                 (muestra información sobre el uso de cat)
    + $ cd ~
    + $ sudo apt-get update     (instala un repositorio de dependencias)
    + $ sudo apt-get upgrade    (para actulizar Ubuntu)
        + Do you want to continue? [Y/n]: **y**
    + $ sudo apt install nodejs (para instalar Node.js)
        + Do you want to continue? [Y/n]: **y**
    + $ node -v                 (ver la versión de Node.js)
    + $ sudo apt install npm    (instala Node Package Manager)
        + Do you want to continue? [Y/n]: **y**
+ [Video 013](https://www.youtube.com/watch?v=9NjnFEtgChE)
    + $ clear                   (limpiar pantalla)
    + $ cd personalProjects
    + $ npx create-react-app test
    + $ cd test
    + $ npm start               (crea un servidor para levantar la aplicación)
    + $ ^C                      (para finalizar el servicio y regresar a la consola)
17. Abrir otra terminal y ejecutar:
    + $ cd personalProjects
    + $ cd test
    + $ code .
18. En VSCode ir **Terminal > Nuevo terminal** y ejecutar:
    + $ npm start
    + **Nota**: en caso de no contar con los privilegios para ejecutar ciertas acciones:
        + Ir a una terminal de **Windows Terminal** y ejecutar:
            + $ sudo chown -R petrix ~personalProjects  (esta acción da permisos de administrador en la carpeta **personalProjects**)
+ [Video 014](https://www.youtube.com/watch?v=wOxVIArLsrg)
19. Cerrar VSCode.
20. En una terminal de **Windows Terminal** ejecutar:
    + $ rm -rf test
21. Comando básicos para borrar:
    + $ rm nombre_archivo.ext                   (borrar un archivo)
    + $ rm -d nombre_carpeta_vacia              (borrar una carpeta vacia)
    + $ rm -rf nombre_carpeta_con_contenido     (borrar una carpeta con contenido)
22. En una terminal de **Windows Terminal** ejecutar:
    + $ git --version                           (ver versión de Git en caso de estar instalado)
        + En caso de no tener git instalado:
            + $ sudo apt-get update
            + $ sudo apt-get upgrade
            + $ sudo apt install git
23. Ir a GitHub: https://github.com
+ [Video 015](https://www.youtube.com/watch?v=-6nbd2IDxMU)
24. Generar llave SSH:
    + Ir a **Windows Terminal**:
        + $ cd ~
        + $ ssh-keygen -t rsa -b 4096 bazo.pedro@gmail.com
            + Enter file in which to save the key (/home/petrix/.ssh/id_rsa): [ENTER]
            + Enter passphrase                          (empty for no passphrase): ***
        + $ eval "$(ssh-agent -s)"                      (Para evaluar el SSH agent)
        + $ ssh-copy-id bazo.pedro@gmail.com            (Para copiar la llave pública)
        + $ cd ~/.ssh
        + $ cat id_rsa.pub
    + Ir a [GitHub](https://github.com):
        + Ir a **Settings**.
        + Ir a **SSH and GPG keys**.
        + Dar clic en **New SSH key** y pegar las credenciales de la llave pública.
    + **Nota**: con estos pasos la terminal de Ubuntu queda enlazada con tu cuenta de GitHub.
+ [Video 016](https://www.youtube.com/watch?v=aFPTsulN00k)
+ [Video 017](https://www.youtube.com/watch?v=VSTM2MHd0qI)