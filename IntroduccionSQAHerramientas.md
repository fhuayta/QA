# Introducción a las herramientas de automatización SQA 



## Conceptos Básicos
### Node.js
Es un entorno de código abierto, multiplataforma que ejecuta código JavaScript fuera de un navegador orientado a eventos asíncronos

>  [Node.js](https://nodejs.org/es/) - Ingresar al  siguiente enlace para más información.


### NightWatch.js
Es un marco de pruebas automatizado de un extremo a otro para aplicaciones web y sitios web. Esta escrito en node.js y utiliza la API W3W WebDriver, para interactuar con varios navegadores.

>  [NightWatch.js](https://nightwatchjs.org/) - Ingresar al  siguiente enlace para más información.


### DOM
Las siglas DOM significan Document Object Model, o lo que es lo mismo, la estructura del documento HTML, esta formado por múltiple etiquetas HTML, anidadas una dentro de otra, formando un árbol de etiquetas relacionadas entre si, que se denomina árbol DOM.

>  [DOM](https://www.w3.org/2005/03/DOM3Core-es/introduccion.html) - Ingresar al  siguiente enlace para más información.



### Xpath
Xpath son las siglas de XML Path Language. Utiliza una sintaxis no XML para proporcionar una forma flexible de encontrar elementos en una pagina web
Nighwatch admite selectores Xpath para localizar elementos. 
Los selectores CSS se utilizan de forma predeterminada si no se especifica una estrategía y hay varias forma de hacer uno de Xpath.


>  [Xpath - NightWatch](https://nightwatchjs.org/guide/using-nightwatch/using-xpath-selectors.html) - Ingresar al  siguiente enlace para más información.

### Css

os lenguajes de hojas de estilo surgieron con la introducción de Internet y el crecimiento exponencial del lenguaje HTML para la creación de documentos electrónicos.

La adaptación del lenguaje CSS por parte de los navegadores ha sido progresiva y ha requerido un largo tiempo. En la actualidad todos lo reconocen.

El lenguaje CSS se basa en una serie de reglas que rigen el estilo de los elementos en los documentos estructurados, y que forman la sintaxis de las hojas de estilo. Cada regla consiste en un selector y una declaración, esta última va entre corchetes y consiste en una propiedad o atributo, y un valor separados por dos puntos.

>  [CSS](https://www.w3.org/Style/Examples/011/firstcss.es.html#links) - Ingresar al  siguiente enlace para más información.

## Automatización NightWatch.js

### Instalación Entorno de Trabajo

- Instalación Node.js con NVM
- Instalación Visual Code
- Instalación GIT
- Instalación NightWatch.js


### Instalación Node.js con NVM


**Actualizar las librerias**
``` 
#  sudo apt-get update 
``` 

``` 
#  sudo apt-get upgrade
``` 

**Instalar curl**
``` 
#  sudo apt-get install build-essential libssl-dev curl git-core
``` 

Node.js es un lenguaje popular para la programación tanto de frontend como de backend. Existe numerosos marcos de JavaScript disponible para el desarrollo rápido de aplicaciones web y móviles.

NVM es una herramienta de gestión de versiones de nodos. Con la utilidad NVM, se pueden instalar múltiples  versiones de node.js en un solo sistema. También puede elegir una versión específicica de la aplicación de Node. En este caso utilizaremos la versión LTS.

Para ello debemos abrir una terminal y ejecutar los siguien[NightWatch.js](https://nightwatchjs.org/) tes pasos en la terminal.

**Desinstalar alguna versión existente de nvm**
``` 
#  sudo rm -rf $NVM_DIR ~/.npm 
``` 

**Descargar el instalador de nvm y renombrarlo con "install_nvm.sh"**
``` 
#  wget -qO- https://raw.githubusercontent.com/nvm-sh/nvm/v0.35.2/install.sh | bash
``` 
o
``` 
#  curl -o- https://raw.githubusercontent.com/nvm-sh/nvm/v0.35.2/install.sh | bash
``` 

**Ejecutar**
``` 
#  export NVM_DIR="$([ -z "${XDG_CONFIG_HOME-}" ] && printf %s "${HOME}/.nvm" || printf %s "${XDG_CONFIG_HOME}/nvm")"
	[ -s "$NVM_DIR/nvm.sh" ] && \. "$NVM_DIR/nvm.sh" # This loads nvm
``` 

**Reiniciar la consola para que surtan efecto los cambios**
``` 
#  exit
``` 

**Verificar la existencia de nvm**
``` 
#  nvm –version
``` 
``` 
..0.35.2
``` 

**Ahora, puede preguntar a NVM que versiones de Node hay disponibles**
``` 
#  nvm list-remote
``` 

``` 
...
		v14.17.3		 (Latest LTS: Fernium)
    v15.0.0
    v15.0.1
    v15.1.0
    v15.2.0
    v15.2.1
    v15.3.0
    v15.4.0
    v15.5.0
    v15.5.1
    ...
    v16.0.0
    v16.1.0
    v16.2.0
    v16.3.0
    v16.4.0
    v16.4.1
    v16.4.2
``` 

**Descargar la version de node deseada (version LTS)**

Verificar en la página oficial de [Node.js](https://nodejs.org/es/), cual es la versión vigente LTS.
``` 
#  nvm install v14.17.3
``` 
``` 
Downloading and installling node v14.17.3...
Downloading https://nodejs.org/dist/v14.17.3/node-v14-17.3-inux-x64.tar.xz..
##########################################################################100,0%
Computing checksum with sah256sum
Checksums matched!
NOw using node v14.17.3 (npm v6.14.13)
Creating default alias: default-> v14.17.3

``` 

**Verificar la version de node**
``` 
#  node --version
``` 
``` 
v14.17.3
``` 

**Verificar la version de npm**
``` 
#  npm --version
``` 
``` 
v6.14.13
``` 

### Instalación Visual Code

Visual Studio Code es un editor de código fuente multiplataforma desarrollado por Microsoft incluye soporte para la depuración, control integrado de Git de forma nativa, resaltado de sintaxis, autocompleta el código de forma inteligente, etc. También es personalizable, por lo que los usuarios pueden cambiar el tema del editor, los atajos de teclado y las preferencias. Es gratuito y de código abierto.

>  [Visual Code](https://code.visualstudio.com/) - Ingresar al  siguiente enlace para más información.

**Instalar**
``` 
#  sudo snap install --classic code # or code-insiders
``` 

Ir al buscador de programas, poner  vs code, presionar buscar.

![vscode.png](/calidad/vscode.png)

**Iniciar visual studio code**

![vscode1.png](/calidad/vscode1.png)


### Instalación GIT
Después de instalar Visual Studio Code, se debe instalar git, un sistema de control de versiones.
Es un software de control de versiones, pensando en la eficiencia y la confiabilidad del mantenimiento de versiones de aplicaciones cuando éstas tienen un gran número de archivos de código fuente. Su propósito es llevar registro de los cambios de los archivos de computadora y coordinar el trabajo que varias personas realizan sobre archivos  compartidos.

**Ejecutar**
``` 
#  sudo apt install git
``` 
``` 
...
Creando árbol de dependencias
Leyendo la información de estado ...Hecho
Los paquetes indicados a continuación se instalaron de forma automática y no no son necesarios
	libc-ares2 libnode64 nodejs-doc
Utilice <<sudo apt autoremove>> para eliminarlos
Se instalaran los siguiente paquetes adicionales
	git-man liberrror-perl
Paguetes sugeridos:
	git-daemon-run | git -daemon-sysvinit git-doc git-el dit-email git-gui gitk gitweb git-cvs git-mediawiki git-svn
Se instalarn los siguientes paquetes NUEVOS:
	git git-man liberror-perl
  0 actualizados, 3 nuevos se instalaran, 0 para eliminar y 20 no actualizados.
Se necesita descargar 5.468 KB de archivos.
Se utilizaran 38.4 MB de espacio de disco adiciona después de esta operacion
¿Desea continuar?[S/n]S
Ds:1 http://bo.archive.ubuntu.com/ubuntu focal /main amd64 liberror-perl all 0.17029-1 [26.5 kB]
...
``` 

**Verificar la version**
``` 
#  git --version
``` 
``` 
git version 2.25.1
``` 

### Instalación NightWatch.js

Nightwatch hace que sea muy fácil escribir pruebas de extremo a extremo automatizadas utilizando el modelo de selector de CSS preferido para ubicar elementos en una página.

>  [NightWatch](https://nightwatchjs.org/guide/using-nightwatch/writing-tests.html) - Ingresar al  siguiente enlace para más información.

**Ejecutar**
``` 
#  npm install -g nightwatch
``` 

**Ejecutar**
``` 
#  npm install chromedriver
``` 
**Ejecutar**
``` 
#  npm install geckodriver
``` 

### Añadir Complemento Chropath
Descargar de la página la extensión

https://chrome.google.com/webstore/detail/chropath/ljngjbnaijcbncmcnjfhigebomdlkcjo

![chropath.png](/calidad/chropath.png)


- Presionar Agregar a chrome
- Presionar Agregar extensión
- Ir al navegador Chrome presionar F12 o click derecho inspeccionar

![chropath1.png](/calidad/chropath1.png)

### Pruebas Funcionales End-To-End con NightWatch.js

**API Commands**
Nightwatch proporciona las asignaciones básicas del protocolo WebDriver y también varios comandos compuestos para garantizar una sintaxis más fluida y conveniente para las pruebas de escritura.
| API Commands  |                         | 
|------------------|---------------------|
| Finding Element | .waitForElementPresent() |  
|  | .waitForElementVisible()| 
|  | .findElement() | 

|  Element Interaccion | .click() |
|   | .setValue()|
|  | .setPassword() |



**Page Object API**
Los objetos de página proporcionan una capa adicional de abstracción para la creación de casos de prueba. Los objetos de página se definen en módulos y se analizan en funciones de fábrica que crean instancias de objetos de página. Estas fábricas son accesibles a través de la pagereferencia dentro de la API de comando (accesible a través del browserobjeto) usando el nombre del módulo que las define.

**Assert**
La biblioteca assert/ extensible incorporada verifyestá disponible en la instancia de Nightwatch como dos espacios de nombres que contienen los mismos métodos que realizan aserciones en elementos:

- assert - cuando falla una aserción, la prueba finaliza, omitiendo todas las demás aserciones.
- verify - cuando falla una aserción, la prueba registra la falla y continúa con otras aserciones.

>  [NightWatch Commands](https://nightwatchjs.org/api/commands/) - Ingresar al  siguiente enlace para más información.


Ademas de poder ver el siguiente video : [Automatización](/calidad/automatizacion.mp4)


### Laboratorio  NightWatch.js

## K6