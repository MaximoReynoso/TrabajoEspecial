# Trabajo Practico Especial FCD

Este repositorio contiene un análisis de calidad de agua del rio de la plata en un archivo `.ipynb`. Las instrucciones a continuación guiarán a los usuarios para configurar el entorno, instalar los requerimientos y ejecutar el archivo en su IDE fde preferencia.

## Requisitos Previos

1. **Python 3.11+**: Asegúrate de tener instalado Python en tu sistema. Puedes verificar tu versión ejecutando el siguiente comando en tu terminal o línea de comandos:

    ```bash
    python --version
    ```

2. **pip**: pip debe estar instalado junto con Python:


3. **IDE**: Puedes ejecutar el archivo `.ipynb` en cualquier IDE compatible con Jupyter Notebooks, como:
   - [Jupyter Notebook](https://jupyter.org/)
   - [JupyterLab](https://jupyterlab.readthedocs.io/)
   - [Visual Studio Code](https://code.visualstudio.com/) (con extensión de Jupyter)
   - [PyCharm Professional](https://www.jetbrains.com/pycharm/) (con soporte para Jupyter Notebooks)

## Instrucciones de Instalación

Sigue los pasos a continuación para instalar las dependencias y ejecutar el archivo `.ipynb`.

### 1. Clonar el Repositorio

Clona este repositorio en tu máquina local. Abre una terminal y ejecuta:

```bash
git clone https://github.com/MaximoReynoso/TrabajoEspecial.git
cd tu-repositorio
```

### 2. Crear un Entorno Virtual (Opcional pero Recomendado)
```bash
# Crear el entorno virtual
python -m venv env

# Activar el entorno virtual
# En Windows:
env\Scripts\activate

# En MacOS y Linux:
source env/bin/activate
```

### 3. Instalar las Dependencias
### Usando pip ejecuta el siguiente comando en la terminal, asegurate de controlar donde se descargaran:
```bash
pip install -r requirements.txt
```

### 4. Abrir y Ejecutar el Archivo .ipynb
- **Jupyter Notebook o JupyterLab**: 
    - Inicia Jupyter Notebook o JupyterLab con el comando:
    ```bash
    jupyter notebook
    ``` 
    - Navega hasta el archivo .ipynb y ábrelo.
- **Visual Studio Code**:
    - Abre Visual Studio Code y navega hasta la carpeta del proyecto.
    - Instala la extensión de Jupyter si no lo has hecho aún.
    - Abre el archivo .ipynb y ejecuta las celdas.
- **PyCharm Professional**: 
    - Abre el proyecto en PyCharm.
    - Abre el archivo .ipynb y ejecuta las celdas.

#  Notas Adicionales
- Si prefieres no utilizar un entorno virtual, puedes omitir el paso 2 y realizar la instalación directamente en tu entorno global de Python.
- Recuerda activar el entorno virtual cada vez que trabajes en el proyecto si optaste por crear uno.
