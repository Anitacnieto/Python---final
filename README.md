# Python---final

# Python Final Project
Pasos para configurar un entorno de desarrollo en Python y utilizar Git para el control de versiones.

## Pasos para configurar el entorno de desarrollo

1. **Abrir la terminal de Git Bash o terminal en Linux.** Si usas Windows, asegúrate de abrirla como administrador.

2. **Crear una carpeta o directorio:**
   ```bash
   mkdir python-final
   ```

3. **Entrar en la carpeta que creaste:**
   ```bash
   cd python-final
   ```

4. **Iniciar un repositorio Git en esa carpeta:**
   ```bash
   git init
   ```

5. **Crear un archivo llamado `finales.py`:**
   ```bash
   touch finales.py
   ```

6. **Abrir Visual Studio Code (VSC):**
   ```bash
   code .
   ```

7. **Verificar la versión de Python instalada:**
   ```bash
   python -V (esta utilicé yo)
   python3 -V
   ```

8. **Crear un entorno virtual en Python:**
   ```bash
   python -m venv venv
   ```

9. **Activar el entorno virtual:**
   - En Git Bash (Windows):
     ```bash
     source venv/Scripts/activate
     ```
   - En Linux/Mac:
     ```bash
     source venv/bin/activate
     ```

10. **Actualizar `pip`, que es el gestor de paquetes de Python:**
    ```bash
    python -m pip install --upgrade pip
    ```

12. **Hacer el primer commit y unirlo al repositorio remoto:**
    - Primero, agregar los archivos al área de preparación (staging area):
      ```bash
      git add .
      ```
    - Luego, hacer el primer commit:
      ```bash
      git commit -m "Primer commit"
      ```
    - Conectar tu repositorio local a un repositorio remoto (por ejemplo, en GitHub):
      ```bash
      git remote add origin https://github.com/tuusuario/tu-repo.git
      ```
    - Subir los cambios al repositorio remoto:
      ```bash
      git push -u origin master
      ```

## Respuesta del punto 11

**¿Qué es `pip` y por qué lo actualizamos?**

- **Pip** es una herramienta de gestión de paquetes para Python. Permite instalar, actualizar y desinstalar paquetes de software. La actualizamos para asegurarnos de tener las versiones más recientes de las herramientas y bibliotecas, lo que nos brinda acceso a las últimas funcionalidades y mejoras de seguridad. Actualizar `pip` nos ayuda a evitar problemas de compatibilidad y mantener un entorno de desarrollo seguro y eficiente.
