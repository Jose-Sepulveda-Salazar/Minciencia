# Minciencia
* Sugerir descargar miniconda y trabajar desde el simbolo del sistema para el trabajo con env.
    * https://docs.anaconda.com/free/miniconda/index.html 
* Al crear un entorno virtual ejecutar el siguiente Script, considerar que debe estar alojado el archivo .yml en la misma carpeta.
    * conda env create -f Env.yml
    * El archivo .yml contiene las librarías y versiones necesarias para la ejecución del programa.
* También configurar la acredencial_login para conectarse al SGBD
* Enlace vscode: https://code.visualstudio.com/download

1. Instalar Anaconda (o Miniconda)
Asegúrate de tener Anaconda o Miniconda instalado en tu sistema. Durante la instalación, es recomendable agregar Anaconda al PATH del sistema, aunque la opción no esté recomendada por defecto en el instalador de Anaconda.

2. Instalar la Extensión de Python en VS Code
Abre VS Code y ve al marketplace de extensiones. Busca y instala la extensión oficial de Python proporcionada por Microsoft. Esta extensión proporciona soporte para el lenguaje Python, incluyendo características como IntelliSense, linting, debugging, code navigation, code formatting, Jupyter notebook support, refactoring, variable explorer, test explorer, y más.

3. Seleccionar el Intérprete de Python
Para seleccionar un intérprete de Python proveniente de un entorno Conda, sigue estos pasos dentro de VS Code:

Abre el Command Palette (Ctrl+Shift+P en Windows/Linux, Cmd+Shift+P en macOS).
Escribe y selecciona Python: Select Interpreter.
Verás una lista de intérpretes disponibles. Los entornos Conda suelen comenzar con conda. Selecciona el entorno Conda que deseas usar.
Si no ves tu entorno Conda, asegúrate de que Conda esté agregado a tu PATH o que hayas inicializado Conda en tu shell según las instrucciones de la documentación de Conda. Puedes hacer esto ejecutando conda init <SHELL_NAME> en tu terminal, donde <SHELL_NAME> es el nombre de tu shell, como bash, zsh, etc.
