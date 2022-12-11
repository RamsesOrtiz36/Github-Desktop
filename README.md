# Github-Desktop
Seguimiento a cambios en archivos de código de forma remota usando github desktop.

## Instalación de GitHub Desktop
Para la descarga nos basamos en la pagina oficila de github y buscamos como descargar [Github desktop para Ubuntu](https://gist.github.com/berkorbay/6feda478a00b0432d13f1fc0a50467f1), **siempre leean antes y despues de instalar.**

        sudo wget https://github.com/shiftkey/desktop/releases/download/release-3.1.1-linux1/GitHubDesktop-linux-3.1.1-linux1.deb
        ### Uncomment below line if you have not installed gdebi-core before
        sudo apt-get install gdebi-core 
        sudo gdebi GitHubDesktop-linux-3.1.1-linux1.deb

En la lista de aplicaciones aparecerá el icono de Github desktop

![](https://github.com/RamsesOrtiz36/Github-Desktop/blob/main/Github%20desktop.png)

Con este programa podran clonar las carpetas de GitHub de la nube a la computadora actual sin usar la ventana de terminal.

![](https://github.com/RamsesOrtiz36/Github-Desktop/blob/main/github%20desktop%20ventana.png)

## Github
Para poder realizar control de versiones de forma remota y colaborativa se usa GitHub.
**Crea cuenta en la pagina web de Github.**
**No olvidar la contraseña**

Crear repositorio con las siguientes caracteristicas:
* Nombre
* Descripción
* Tipo publico (el tipo privado debe tener cuenta de paga)
* Activar casilla README (adjunta un archivo de txto con formato markdown que sirve para instrucciones)
* Crear repositorio.

Crear repositorio.

![Crear repositorio](https://github.com/RamsesOrtiz36/Github-Desktop/blob/main/github%20%20repositorio.png)

Configurar repositorio.

![Configuar repositorio](https://github.com/RamsesOrtiz36/Github-Desktop/blob/main/Github%20new%20repositorio.png)

## Clonar repositorios
Enlazar las carpetas en as que se esta trabajando es el objetivo, para ello hay varias formas y se le llama **clonar repositorio**.

Para que el contenido del repositorio este disponible en la computadora se tiene que **clonar**
En la pagina principal del repositorio aparece un boton verde  **code** aparece la URL del repositorio que enlaza.

### Desde Terminal
Desde terminal de ubuntu colocarse en el directorio donde se colocara el repositorio

        git clone [URL copiada desde Github]
        
![Git Clone](https://github.com/RamsesOrtiz36/Github-Desktop/blob/main/Git%20clone.png)

### Desde GitHub Desktop
Github Desktop tampien pide la URL del repositorio a clonar, en caso de clonar repositorio de otra persona siempre usar URL, si es de tu propia cuenta ya esta enlazada.

![Clonar desde GitHub desktop](https://github.com/RamsesOrtiz36/Github-Desktop/blob/main/github%20desktop%20clone.png)
