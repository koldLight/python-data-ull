# ULL - Introducción a Python para tratamiento de datos

## Opción recomendable - Entorno local

### 1. Descarga del material (Notebooks)

Descárgalo en tu ordenador, preferiblemente en una ruta sin espacios.

Para descargarlo en un zip, puedes hacer click en code / download zip (o lo equivalente en el idioma de tu navegador), o directamente haciendo click [aquí](https://github.com/koldLight/python-data-ull/archive/refs/heads/main.zip).

### 2. Instrucciones para poner a punto el entorno

Puedes utilizar `uv`. Si aún no lo tienes instalado, puedes hacerlo así:

En Mac y Linux:

```
curl -LsSf https://astral.sh/uv/install.sh | sh
```

En Windows

```
powershell -ExecutionPolicy ByPass -c "irm https://astral.sh/uv/install.ps1 | iex"
```

Tendrás que abrir la terminal de tu sistema operativo y navegar hasta donde hayas descomprimido el material. Por ejemplo, si está en el escritorio:

En Mac:

```
cd /Users/<tu_nombre_de_usuario>/Desktop/python-data-ull
```

En Windows (con cmd.exe):

```
cd C:\Usuarios\<tu_nombre_de_usuario>\Escritorio
```

La ruta la tendrás que sustituir por lo que corresponda.

Para instalar los paquetes necesarios con `uv`, haz:

```
uv sync
```

Necesitas crear el kernel de jupyter, hazlo así:

En mac / linux:

```
./.venv/bin/python -m ipykernel install --user --name=ull-python-data --display-name "ULL Python Data"
```

En Windows:

```
.\.venv\Scripts\python.exe -m ipykernel install --user --name=ull-python-data --display-name "ULL Python Data"
```

Y para lanzar los jupyter notebooks, estando en la carpeta donde están tus notebooks (donde descomprimiste el material), haz:

```
uv run jupyter notebook .
```

## Opción alternativa - Sin entorno local - Google Colab

Si esto te falla, o no eres administrador de tu ordenador, puedes lanzar el contenido en Google Colab. Para ello, abre:

https://colab.research.google.com/github/koldLight/python-data-ull/blob/main/

Y haz click en el notebook que vayamos a ver. Te tocará descomentar la celda inicial que trae cada notebook para poder bajar datos e imágenes necesarias para su correcta ejecución.

## Licencia

[![](http://i.creativecommons.org/l/by-sa/4.0/88x31.png)](http://creativecommons.org/licenses/by-sa/4.0/)

Puedes utilizar libremente este material, con las siguientes condiciones:

* Atribuir la autoría a este repositorio.
* Si lo utilizas y haces cambios, deberás liberarlo también bajo la misma licencia.
