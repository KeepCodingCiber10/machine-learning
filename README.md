# Instrucciones

Instalamos git en windows si todavia no lo tenemos. https://git-scm.com/downloads

Instala nuestro gestor de python, [uv](https://github.com/astral-sh/uv). Para ello ejecuta

```
# On macOS and Linux.
curl -LsSf https://astral.sh/uv/install.sh | sh
```

```
# On Windows.
powershell -c "irm https://astral.sh/uv/install.ps1 | iex"
```

Una vez se haya instalado, inicializamos el proyecto con todas sus dependencias ejecutando

```
uv sync
```

Y finalmente, para ejecutar el entorno de jupyter donde trabajaremos ejecutamos

```
uv run --with jupyter jupyter lab
```

Esto nos abrirá una pestaña en el navegador con el entorno. Si no lo hace, ve a la url que te habrá escrito en la terminal.

# Empezar

Ahora ya estas listo para empezar a trabajar. Si no conoces que es jupyter puedes aprender más [aquí](https://jupyterlab.readthedocs.io/en/stable/getting_started/overview.html) y más importante, [aquí](https://jupyterlab.readthedocs.io/en/stable/user/notebook.html#notebook).

Una vez hayas entendido que es jupyter, puedes seguir las explicaciones de los notebooks dentro de la carpeta [Introduction](./Introduction) para conocer las librerias y técnicas básicas que usaremos.
