# TALLER_2
 Crear un diccionario con tres elementos (clave-valor) y mostrar el valor de una clave específica.

## **Índice**
1. [**Descripción**](#descripción)
2. [**Instalación**](#instalación)
3. [**Uso**](#uso)
4. [**Estructura del Código**](#estructura-del-código)
5. [**Requisitos**](#requisitos)
6. [**Licencia**](#licencia)
7. [**Autor**](#autor)

## **Descripción**
Este código crea una aplicación gráfica en Python usando Tkinter. Permite al usuario ingresar y almacenar datos personales (nombre, edad, ciudad) asociados a una clave específica. También puede mostrar los valores almacenados para una clave dada y tiene botones para agregar datos, mostrar resultados y salir.

## **Instalación**

Para instalar y ejecutar el código, primero asegúrate de tener Python instalado desde [python.org](https://www.python.org/downloads/). Tkinter generalmente viene preinstalado, pero si es necesario, en Linux puedes instalarlo con `sudo apt-get install python3-tk`. Luego, guarda el código en un archivo, por ejemplo, `app.py`, y ejecútalo desde la terminal con `python app.py`. Esto abrirá la ventana de la aplicación gráfica.

## **Uso**

Al ejecutar el código, se abrirá una ventana gráfica. Para usar la aplicación, sigue estos pasos:

1. Ingresa el **nombre**, **edad** y **ciudad** en los campos correspondientes.
2. Escribe una **clave específica** para asociar estos datos.
3. Haz clic en el botón **"Agregar datos"** para almacenar la información.
4. Para consultar los datos almacenados, ingresa la misma clave específica y haz clic en **"Mostrar valor"**; el resultado aparecerá en la etiqueta inferior.
5. Haz clic en **"Salir"** para cerrar la aplicación.

## **Estructura del Código**

La estructura del código es la siguiente:

1. **Importación de Tkinter**: 
   ```
   import tkinter as tk
   ```

2. **Clase `Application`**: Hereda de `tk.Frame` y maneja la interfaz gráfica.
   - **Método `__init__`**: Inicializa la aplicación, empaqueta el frame y llama a `create_widgets`.
   - **Método `create_widgets`**: Crea los elementos gráficos (etiquetas, entradas de texto y botones).
   - **Método `agregar_datos`**: Almacena los datos ingresados bajo una clave específica en el diccionario `claves_especificas`.
   - **Método `mostrar_valor`**: Busca y muestra los datos almacenados para la clave ingresada en el campo correspondiente.

3. **Diccionarios**:
   - `datos_persona`: No se utiliza en este caso.
   - `claves_especificas`: Guarda la información ingresada bajo claves específicas.

4. **Ejecutar la aplicación**:
   - Se crea una instancia de `Application` y se ejecuta el bucle principal con `app.mainloop()`.

## Requisitos

Los requisitos para ejecutar este código son:

1. **Python 3.x**: Necesario para ejecutar el script.
2. **Tkinter**: Viene preinstalado con Python, pero asegúrate de tenerlo disponible. En Linux, puede instalarse con `sudo apt-get install python3-tk`.
3. **Sistema operativo**: Funciona en Windows, macOS y Linux. 

## Licencia

Este proyecto está licenciado bajo la **MIT License.**

## Autor

[Smauel Salas Echeverry](https://github.com/SamuelSalas23?tab=repositories.)
