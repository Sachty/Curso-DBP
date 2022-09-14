# Correr app con Flask


## Entorno Virtual 
### Crear entorno virtual:
python -m venv miEntornoVirtual

### Abrir la carpeta (entorno virtual)
cd .\miEntornoVirtual

### Listar los archivos del entorno virtual
ls

### Crear una carpeta "Scripts" dentro del entorno virtual
mkdir Scripts

### Dejar de restringir los procesos de windows
Set-ExecutionPolicy Unrestricted -Scope Process

### Activar el entorno virtual
.\miEntornoVirtual\Scripts\activate.ps1


###  Instalar los requerimientos:
pip install -r  requirements.txt


## Correr Flask

### Correr app con flask, se correra el archivo colocado en .flashenv
flask run



## Extras
.flaskenv: Sirve para correr la aplicacion con un primer archivo
