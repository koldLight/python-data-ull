# ULL - Introducción a Python para tratamiento de datos

## Opción recomendable - Entorno local

### 1. Descarga del material (Notebooks)

Descárgalo en tu ordenador, preferiblemente en una ruta sin espacios.

Para descargarlo en un zip, puedes hacer click en code / download zip (o lo equivalente en el idioma de tu navegador), o directamente haciendo click [aquí](https://github.com/koldLight/python-data-ull/archive/refs/heads/main.zip).

### 2. Instrucciones para poner a punto el entorno

Puedes instalar la última versión de Anaconda para Python 3 para tu sistema operativo desde aquí. Fíjate bien que instales la de Python 3 (y no la de Python 2). Si te sale una ventana que te pide el email, busca y haz clic debajo en la opción "skip registration" / "saltar registro" o similar.

Aquí tienes un tutorial paso a paso de cómo hacerlo:

    Windows. Fíjate bien en el paso en el que debes marcar que añada anaconda al PATH. Aunque esté desmarcado y salga como no recomendado, esa casilla debe quedar marcada.
    Mac.

Una vez instalado, nuestra terminal debería reconocer los comandos conda (el gestor de paquetes), jupyter (la herramienta de notebooks) y python, gracias a que hemos añadido anaconda a nuestro PATH. Esto quiere decir que, cuando escribamos uno de estos comandos, nuestro sistema lo buscará en la carpeta de anaconda. Para comprobarlo, abre una consola. Esto se puede hacer:

    En Windows, abriendo el menú inicio y escribiendo cmd.exe. Si necesitas ayuda, mira más opciones aquí.
    En Mac, abre una terminal. Si necesitas ayuda sobre cómo abrirla, mira aquí.
    En Ubuntu / Debian, abre una terminal. Si necesitas ayuda, mira aquí.

Una vez abierta, ejecuta los siguientes comandos para ver que todo funciona bien:

python --version

conda --version

jupyter --version

Si nos dice que no reconoce el comando, es que no se ha añadido correctamente anaconda al PATH. Los tutoriales referenciados tienen buenas soluciones a este problema habitual.

Aprovecha a instalar la librería folium que utilizaremos más adelante en el curso:

conda install -c conda-forge folium

Y finalmente, para abrir los notebooks, que debes descargar del campus virtual (modifica la ruta dependiendo de dónde los hayas descargado):

- En Windows, puedes hacer, desde la consola (cmd.exe):

jupyter notebook --notebook-dir='C:\mi\ruta\con\notebooks\'

- En Mac o Linux, con la terminal:

jupyter notebook --notebook-dir='/mi/ruta/con/notebooks'


## Opción alternativa - Sin entorno local - Google Colab

Si esto te falla, o no eres administrador de tu ordenador, puedes lanzar el contenido en Google Colab. Para ello, abre:

https://colab.research.google.com/github/koldLight/python-data-ull/blob/main/

Y haz click en el notebook que vayamos a ver. Te tocará descomentar la celda inicial que trae cada notebook para poder bajar datos e imágenes necesarias para su correcta ejecución.

## Licencia

[![](http://i.creativecommons.org/l/by-sa/4.0/88x31.png)](http://creativecommons.org/licenses/by-sa/4.0/)

Puedes utilizar libremente este material, con las siguientes condiciones:

* Atribuir la autoría a este repositorio.
* Si lo utilizas y haces cambios, deberás liberarlo también bajo la misma licencia.
