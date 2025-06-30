# python-final


# Python - Final 


Hoy vamos a hacer actividad en Python en un día como programadores:

1. Abrir la terminal de Git Bash o terminal en Linux, debe ser como administrador en Window

2. Creamos una carpeta o directorio: 

```bash
mkdir python-final
```

3. Entramos en ella:
   
```bash
cd python-final
```

4. Iniciamos el repositorio:

```bash
git init
```

5. Creamos un archivo:
   
```bash
touch finales.py
```

6. Abrimos VSC:

```bash
code .
```

7. En terminal ingresamos el comando para saber la versión de Python que tenemos instalada:

```bash
python -V
```

```bash
python3 -V
```

8. Creamos el entorno virtual en Python:

```bash
python3 -m venv venv #Creamos el entorno virtual
```

9. Activamos el entorno virtual:

```bash
source venv/bin/activate #Activamos el entorno virtual en Linux
```

```bash
venv/scripts/activate #En windows
```

10. Hacemos actualización del pip de Python

```bash
python3 -m pip install --upgrade pip #Actualizamos el pip
```

11. Investigar ¿Qué es el pip y porque lo actualizamos?
    
13. Hacer al primer commit de este trabajo y unirlo al repositorio remoto.

14. Enviar el enlace del repositorio remoto donde tiene que tener un README.md con todos los detalles de lo que les fui mostrando en comandos, y las respuesta del punto 11 de más arriba.


## ¿Qué es pip y por qué actualizarlo?

pip es una herramienta fundamental para el desarrollo de software en Python. Es una herramienta de línea de comandos que se utiliza para instalar, actualizar y gestionar paquetes de software escritos en Python. El nombre "pip" es un acrónimo recursivo que significa "pip installs packages" (pip instala paquetes).

Funciones principales de pip:

Instalar paquetes: Puedes instalar cualquier paquete disponible en el Python Package Index (PyPI) usando un comando como:
```bash
pip install nombre_paquete
```

Actualizar paquetes: Permite actualizar un paquete a su versión más reciente con:

```bash
pip install --upgrade nombre_paquete
```
Desinstalar paquetes: Puedes desinstalar paquetes con:

```bash
pip uninstall nombre_paquete
```

Listar paquetes instalados: Muestra todos los paquetes instalados en el entorno con:

```bash
pip list
```
Mostrar información de un paquete: Puedes obtener detalles sobre un paquete específico usando:

```bash
pip show nombre_paquete
```

## ¿Por qué actualizar pip?

Actualizar pip es importante por varias razones:

Nuevas funcionalidades: Las nuevas versiones de pip a menudo incluyen nuevas características que pueden hacer que la gestión de paquetes sea más fácil y más eficiente.

Corrección de errores: Cada versión de pip puede incluir correcciones de errores y fallos que estaban presentes en versiones anteriores.

Mejoras de seguridad: Las actualizaciones de pip pueden incluir parches de seguridad importantes que protegen tu entorno de desarrollo de vulnerabilidades.

Compatibilidad: Las nuevas versiones pueden asegurar mejor compatibilidad con las versiones más recientes de Python y con los paquetes de PyPI.